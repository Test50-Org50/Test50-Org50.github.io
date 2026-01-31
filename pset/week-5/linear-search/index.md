---
title: Linear Search
---

# A. Linear Search

## Problem Setup

- login to [CS50 IDE](https://cs50.dev)
- write `cd` in the *terminal* to go to the home directory
- write `mkdir linear-search` to create a folder called `linear-search`
- write `cd linear-search` to go to the `linear-search` folder
- write `code linear-search.cpp` to create a file called `linear-search.cpp` and open it in the editor

## Problem

Given a number \\(N\\) and an array \\(A\\) of \\(N\\) numbers. Determine if the number \\(X\\) exists in array \\(A\\) or **not** and print its position (**0-index**).

**Note:** \\(X\\) may be found **once** or **more than once** and **may not be found**.

## Input

First line contains a number \\(N\\) (\\(1 \\leq N \\leq 10^5\\)) number of elements.

Second line contains \\(N\\) numbers (\\(0 \\leq A_i \\leq 10^9\\)).

Third line contains a number \\(X\\) (\\(0 \\leq X \\leq 10^9\\)).

## Output

Print the **position** of \\(X\\) in the first time you find it. If it doesn't **exist** print -1.

## Examples

**Example 1:**

**Input:**

```text
3
3 0 1
0
```

**Output:**

```text
1
```

**Example 2:**

**Input:**

```text
5
1 3 0 4 5
10
```

**Output:**

```text
-1
```

**Example 3:**

**Input:**

```text
4
2 3 2 1
2
```

**Output:**

```text
0
```

## Test Your Code

Make sure you are in the `linear-search` directory, then run the following command:

```bash
check50 iti-technical-team/problemset/2026/5/linear-search
```

## Submit Your Code

Make sure you are in the `linear-search` directory, then run the following command:

```bash
submit50 iti-technical-team/problemset/2026/5/linear-search
```
