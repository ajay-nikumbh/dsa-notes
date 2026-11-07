# 12. Dynamic Programming

Dynamic Programming (DP) sounds scary. It is not. **DP is recursion that remembers its answers.**

> "Those who cannot remember the past are condemned to repeat it."

Plain recursion keeps solving the same small problem again and again. DP solves each small problem once, writes the answer down, and reads it back next time.

This page teaches the idea once, slowly. Every problem note in this folder then follows the same four steps.

## Contents

1. [The Big Idea in One Picture](#1-the-big-idea-in-one-picture)
2. [How to Spot a DP Problem](#2-how-to-spot-a-dp-problem)
3. [The Five Words You Need](#3-the-five-words-you-need)
4. [The 4-Step Ladder](#4-the-4-step-ladder)
5. [Step 1: Recursion](#5-step-1-recursion)
6. [Step 2: Memoization (Top-Down)](#6-step-2-memoization-top-down)
7. [Step 3: Tabulation (Bottom-Up)](#7-step-3-tabulation-bottom-up)
8. [Step 4: Space Optimization](#8-step-4-space-optimization)
9. [The Three 1D DP Families](#9-the-three-1d-dp-families)
10. [Common Traps](#10-common-traps)
11. [Problems](#11-problems)
12. [What Comes Next](#12-what-comes-next)

## 1. The Big Idea in One Picture

Let us compute Fibonacci `f(5)` with plain recursion. `f(n) = f(n-1) + f(n-2)`.

```mermaid
flowchart TD
    A("f(5)") --> B("f(4)")
    A --> C("f(3)")
    B --> D("f(3)")
    B --> E("f(2)")
    C --> F("f(2)")
    C --> G("f(1)")
    D --> H("f(2)")
    D --> I("f(1)")
    E --> J("f(1)")
    E --> K("f(0)")
    F --> L("f(1)")
    F --> M("f(0)")
    H --> N("f(1)")
    H --> O("f(0)")

    classDef rep fill:#78350f,stroke:#f59e0b,color:#fef3c7
    classDef norm fill:#1f2937,stroke:#6b7280,color:#e5e7eb
    class C,D,E,F,H rep
    class A,B,G,I,J,K,L,M,N,O norm
```

Look at the gold boxes:

- `f(3)` is computed **2 times**.
- `f(2)` is computed **3 times**.

For `f(30)`, plain recursion makes about **2.7 million calls**. But there are only **31 different questions** (`f(0)` to `f(30)`). Everything else is repeated work.

**DP fix:** keep a notebook. Before solving `f(k)`, look in the notebook. If the answer is there, use it. If not, solve it once and write it down.

## 2. How to Spot a DP Problem

Ask two questions:

| Question | Name | Example |
|:---|:---|:---|
| Does the big problem use answers of smaller versions of itself? | **Optimal substructure** | Ways to reach stair 5 = ways to reach stair 4 + ways to reach stair 3 |
| Do the same smaller problems show up again and again? | **Overlapping subproblems** | `f(3)` appears twice in the tree above |

If both answers are yes, it is DP.

**Words in the question that hint at DP:**

- "count the number of ways"
- "minimum cost" / "maximum profit"
- "can you reach" / "is it possible"
- "longest" / "shortest" with choices at every step
- "you cannot pick two adjacent ones"

**Greedy vs DP.** Greedy picks the best-looking choice right now and never looks back. DP tries every choice and keeps the best. If a small example shows greedy giving a wrong answer, you need DP. The [Frog Jump](01.%20One%20Dimensional%20DP/03.%20Frog%20Jump.md) and [House Robber](01.%20One%20Dimensional%20DP/05.%20198.%20House%20Robber.md) notes each show one such example.

## 3. The Five Words You Need

| Word | Simple meaning | Fibonacci example |
|:---|:---|:---|
| **Subproblem** | A smaller version of the same question | "What is `f(3)`?" |
| **State** | The few numbers that describe one subproblem | `i` (which Fibonacci number) |
| **Recurrence** | The rule that builds a big answer from smaller answers | `f(i) = f(i-1) + f(i-2)` |
| **Base case** | The smallest answers you know without any work | `f(0) = 0`, `f(1) = 1` |
| **Memo / dp table** | The notebook where answers are saved | `dp[i]` holds `f(i)` |

**Golden rule:** say what `dp[i]` means in one plain sentence before you write any code. For example: "`dp[i]` is the minimum energy the frog needs to reach stone `i`." If you cannot say it, you are not ready to code.

## 4. The 4-Step Ladder

Every note in this folder climbs the same ladder.

```mermaid
---
config:
  layout: dagre
  flowchart:
    curve: basis
---
flowchart LR
    R("Step 1<br/>Recursion<br/>O(2ⁿ)"):::a --> M("Step 2<br/>Memoization<br/>top-down<br/>O(n)"):::b
    M --> T("Step 3<br/>Tabulation<br/>bottom-up<br/>O(n)"):::c
    T --> S("Step 4<br/>Space optimized<br/>O(1) space"):::d

    classDef a fill:#7f1d1d,stroke:#ef4444,color:#fee2e2
    classDef b fill:#78350f,stroke:#f59e0b,color:#fef3c7
    classDef c fill:#1e3a5f,stroke:#3b82f6,color:#dbeafe
    classDef d fill:#065f46,stroke:#10b981,color:#ecfdf5
    linkStyle default stroke:#94a3b8,stroke-width:2.5px
```

| Step | What you do | Time | Extra space |
|:---|:---|:---:|:---|
| 1 · Recursion | Write the recurrence as a function | Exponential | Recursion stack `O(n)` |
| 2 · Memoization | Same function + a notebook | `O(n)` | Notebook `O(n)` + stack `O(n)` |
| 3 · Tabulation | Fill the notebook with a loop, small to big | `O(n)` | Table `O(n)`, no stack |
| 4 · Space optimized | Keep only the cells you still need | `O(n)` | `O(1)` (or `O(k)`) |

In an interview, always start at step 1 out loud. It shows you understand the problem. Then climb.

## 5. Step 1: Recursion

Write three things:

1. **The function's meaning.** `f(i)` = answer for the first `i` things (or for position `i`).
2. **Base cases.** The smallest `i` you can answer directly.
3. **The recurrence.** Try every choice, combine the smaller answers (add them for counting, `min` for cost, `max` for profit).

```python
# Plain recursion for Fibonacci
def f(i):

    # Base cases: f(0) = 0, f(1) = 1
    if i <= 1:
        return i

    # Recurrence: the sum of the two previous answers
    return f(i - 1) + f(i - 2)
```

It is correct but slow, because the tree repeats work.

## 6. Step 2: Memoization (Top-Down)

"Top-down" means you still start from the big question `f(n)` and go down. You only add a notebook. **Three steps:**

1. **Declare:** `dp = [-1] * (n + 1)`. `-1` means "not solved yet".
2. **Check:** at the start of `f(i)`, if `dp[i] != -1`, return `dp[i]`.
3. **Store:** before returning, save the answer: `dp[i] = ...`.

```python
# Memoized Fibonacci
def fib_memo(n):

    # Step 1: declare the notebook, -1 means "not solved yet"
    dp = [-1] * (n + 1)

    # The recursive helper
    def f(i):

        # Base cases
        if i <= 1:
            return i

        # Step 2: check the notebook first
        if dp[i] != -1:
            return dp[i]

        # Step 3: solve once and store the answer
        dp[i] = f(i - 1) + f(i - 2)

        # Return the stored answer
        return dp[i]

    # Start from the big question
    return f(n)
```

**How the notebook fills for `n = 5`.** The calls go down the left side first, so `dp[2]` fills first:

Each row is the notebook after one fill. Green = just filled. Orange = notebook hit (read, no new calls). Dashed = still computing.

```mermaid
block-beta
  columns 7
  hx[" "] h0["dp[0]"] h1["dp[1]"] h2["dp[2]"] h3["dp[3]"] h4["dp[4]"] h5["dp[5]"]
  l0["dp[2] = 1"] r0c0["-1"] r0c1["-1"] r0c2["1"] r0c3["-1"] r0c4["-1"] r0c5["-1"]
  l1["dp[3] = 2"] r1c0["-1"] r1c1["-1"] r1c2["1"] r1c3["2"] r1c4["-1"] r1c5["-1"]
  l2["dp[4] = 3"] r2c0["-1"] r2c1["-1"] r2c2["1"] r2c3["2"] r2c4["3"] r2c5["-1"]
  l3["dp[5] = 5"] r3c0["-1"] r3c1["-1"] r3c2["1"] r3c3["2"] r3c4["3"] r3c5["5"]
  classDef head fill:none,stroke:none,color:#64748b
  class hx,h0,h1,h2,h3,h4,h5,l0,l1,l2,l3 head
  classDef empty fill:#f1f5f9,stroke:#94a3b8,color:#64748b
  class r0c0,r0c1,r1c0,r1c1,r2c0,r2c1,r3c0,r3c1 empty
  classDef new fill:#065f46,stroke:#10b981,color:#ecfdf5,stroke-width:3px
  class r0c2,r1c3,r2c4,r3c5 new
  classDef wait fill:#fef3c7,stroke:#f59e0b,color:#78350f,stroke-dasharray:4 3
  class r0c3,r0c4,r0c5,r1c4,r1c5,r2c5 wait
  classDef done fill:#1e3a5f,stroke:#3b82f6,color:#dbeafe
  class r1c2,r2c3,r3c2,r3c4 done
  classDef read fill:#78350f,stroke:#f59e0b,color:#fef3c7
  class r2c2,r3c3 read
```

Each `f(k)` is now solved once, so the work is `O(n)`.

## 7. Step 3: Tabulation (Bottom-Up)

"Bottom-up" means you start from the smallest answers and build up with a loop. No recursion, so no stack.

**How to turn memoization into tabulation, every time:**

| # | Do this | Fibonacci |
|:---:|:---|:---|
| 1 | Make the same dp array | `dp = [0] * (n + 1)` |
| 2 | Write the base cases into it | `dp[0] = 0`, `dp[1] = 1` |
| 3 | Loop the opposite way to the recursion: small to big | `for i in range(2, n + 1)` |
| 4 | Copy the recurrence, `f(...)` becomes `dp[...]` | `dp[i] = dp[i-1] + dp[i-2]` |
| 5 | The answer is in the last cell | `return dp[n]` |

**How the table fills for `n = 5`:**

```mermaid
block-beta
  columns 7
  hx[" "] h0["i = 0"] h1["i = 1"] h2["i = 2"] h3["i = 3"] h4["i = 4"] h5["i = 5"]
  l0["start"] r0c0["0"] r0c1["1"] r0c2[" "] r0c3[" "] r0c4[" "] r0c5[" "]
  l1["i = 2"] r1c0["0"] r1c1["1"] r1c2["1"] r1c3[" "] r1c4[" "] r1c5[" "]
  l2["i = 3"] r2c0["0"] r2c1["1"] r2c2["1"] r2c3["2"] r2c4[" "] r2c5[" "]
  l3["i = 4"] r3c0["0"] r3c1["1"] r3c2["1"] r3c3["2"] r3c4["3"] r3c5[" "]
  l4["i = 5"] r4c0["0"] r4c1["1"] r4c2["1"] r4c3["2"] r4c4["3"] r4c5["5"]
  classDef head fill:none,stroke:none,color:#64748b
  class hx,h0,h1,h2,h3,h4,h5,l0,l1,l2,l3,l4 head
  classDef new fill:#065f46,stroke:#10b981,color:#ecfdf5,stroke-width:3px
  class r0c0,r0c1,r1c2,r2c3,r3c4,r4c5 new
  classDef empty fill:#f1f5f9,stroke:#94a3b8,color:#64748b
  class r0c2,r0c3,r0c4,r0c5,r1c3,r1c4,r1c5,r2c4,r2c5,r3c5 empty
  classDef read fill:#78350f,stroke:#f59e0b,color:#fef3c7
  class r1c0,r1c1,r2c1,r2c2,r3c2,r3c3,r4c3,r4c4 read
  classDef done fill:#1e3a5f,stroke:#3b82f6,color:#dbeafe
  class r2c0,r3c0,r3c1,r4c0,r4c1,r4c2 done
```

Orange = the two cells being read. Green = the cell being filled. `dp[i] = dp[i-1] + dp[i-2]`, so the answer is `dp[5] = 5`.

## 8. Step 4: Space Optimization

Look at the table fill above. To fill `dp[i]`, we only read `dp[i-1]` and `dp[i-2]`. Older cells are never read again. So we keep only two variables.

```mermaid
block-beta
  columns 4
  hx[" "] h0["prev2"] h1["prev"] h2["curr"]
  l0["i = 2"] r0c0["0"] r0c1["1"] r0c2["1"]
  l1["i = 3"] r1c0["1"] r1c1["1"] r1c2["2"]
  l2["i = 4"] r2c0["1"] r2c1["2"] r2c2["3"]
  l3["i = 5"] r3c0["2"] r3c1["3"] r3c2["5"]
  classDef head fill:none,stroke:none,color:#64748b
  class hx,h0,h1,h2,l0,l1,l2,l3 head
  classDef read fill:#78350f,stroke:#f59e0b,color:#fef3c7
  class r0c0,r0c1,r1c0,r1c1,r2c0,r2c1,r3c0,r3c1 read
  classDef new fill:#065f46,stroke:#10b981,color:#ecfdf5,stroke-width:3px
  class r0c2,r1c2,r2c2,r3c2 new
```

After each row, slide: `prev2 = prev`, `prev = curr`. After `i = 5`, `prev = 5` is the answer.

**Rule:** if `dp[i]` only reads the last `k` cells, keep only `k` variables (or a list of size `k`). For Fibonacci, Climbing Stairs, Frog Jump and House Robber, `k = 2`, so space is `O(1)`. For Frog Jump with K distances, it is `O(k)`.

## 9. The Three 1D DP Families

All six 1D problems here belong to one of three families. Learn the family, and the next problem feels familiar.

| Family | Recurrence shape | Combine with | Problems |
|:---|:---|:---:|:---|
| **Counting ways** | `dp[i] = dp[i-1] + dp[i-2]` | `+` | Fibonacci, Climbing Stairs |
| **Minimum cost over choices** | `dp[i] = min(dp[i-j] + cost(j))` for each allowed jump `j` | `min` | Frog Jump, Frog Jump with K Distances |
| **Pick / not pick** | `dp[i] = max(nums[i] + dp[i-2], dp[i-1])` | `max` | House Robber, House Robber II |

```mermaid
---
config:
  layout: dagre
  flowchart:
    curve: basis
---
flowchart TD
    D("1D DP"):::root --> C("Counting ways<br/>add the choices"):::c1
    D --> M("Min cost<br/>min over choices"):::c2
    D --> P("Pick / not pick<br/>max of two options"):::c3
    C --> F1("509 · Fibonacci"):::s
    C --> F2("70 · Climbing Stairs"):::s
    M --> F3("Frog Jump"):::s
    M --> F4("Frog Jump · K distances"):::s
    P --> F5("198 · House Robber"):::s
    P --> F6("213 · House Robber II"):::s

    classDef root fill:#4338ca,stroke:#818cf8,color:#eef2ff
    classDef c1 fill:#1e3a5f,stroke:#3b82f6,color:#dbeafe
    classDef c2 fill:#78350f,stroke:#f59e0b,color:#fef3c7
    classDef c3 fill:#065f46,stroke:#10b981,color:#ecfdf5
    classDef s fill:#1f2937,stroke:#6b7280,color:#e5e7eb
    linkStyle default stroke:#94a3b8,stroke-width:2.5px
```

## 10. Common Traps

| Trap | What goes wrong | Fix |
|:---|:---|:---|
| Writing code before defining `dp[i]` | Recurrence ends up wrong or off by one | Say what `dp[i]` means in one sentence first |
| Missing a base case | Wrong answer for `n = 0` or `n = 1`, or index errors | List every base case and test the tiny inputs |
| Loop stops at `n` instead of `n + 1` | Last answer never computed | `range(2, n + 1)` |
| Memo uses `0` as "not solved" | `0` can be a real answer, so it gets solved again | Use `-1` (or `None`) as "not solved" |
| Forgetting to store in memoization | Still exponential time | `dp[i] = ...` before `return` |
| Greedy instead of DP | Locally best choice gives a worse total | Try every choice and take the min/max |
| Recursion depth in Python | `RecursionError` for big `n` | Use tabulation or the space-optimized loop |
| Space optimizing too early | Hard to debug | Write the table version first, then shrink it |

## 11. Problems

### 01. One Dimensional DP

| # | Problem | Difficulty | Family | Status |
|:---:|:---|:---:|:---|:---:|
| 1 | [509. Fibonacci Number](01.%20One%20Dimensional%20DP/01.%20509.%20Fibonacci%20Number.md) | Easy | Counting ways | Written |
| 2 | [70. Climbing Stairs](01.%20One%20Dimensional%20DP/02.%2070.%20Climbing%20Stairs.md) | Easy | Counting ways | Written |
| 3 | [Frog Jump](01.%20One%20Dimensional%20DP/03.%20Frog%20Jump.md) | Medium | Min cost over choices | Written |
| 4 | [Frog Jump with K Distances](01.%20One%20Dimensional%20DP/04.%20Frog%20Jump%20with%20K%20Distances.md) | Medium | Min cost over choices | Written |
| 5 | [198. House Robber](01.%20One%20Dimensional%20DP/05.%20198.%20House%20Robber.md) | Medium | Pick / not pick | Written |
| 6 | [213. House Robber II](01.%20One%20Dimensional%20DP/06.%20213.%20House%20Robber%20II.md) | Medium | Pick / not pick (circle) | Written |

## 12. What Comes Next

These DP sections follow, in this order:

| # | Section | Status |
|:---:|:---|:---:|
| 01 | One Dimensional DP | Written |
| 02 | Two Dimensional DP (grids, paths) | Planned |
| 03 | Three Dimensional DP | Planned |
| 04 | DP on Subsets and Subsequences (knapsack, coin change, target sum) | Planned |
| 05 | DP on Strings (LCS, edit distance, wildcard) | Planned |
| 06 | DP on Stocks | Planned |
| 07 | DP on LIS | Planned |
| 08 | Matrix Chain / Partition DP | Planned |
| 09 | DP on Rectangles | Planned |
