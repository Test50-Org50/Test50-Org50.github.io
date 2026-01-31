---
title: Stack
---

# D. Stack

## Problem Setup

- login to [CS50 IDE](https://cs50.dev)
- write `cd` in the *terminal* to go to the home directory
- write `mkdir stack` to create a folder called `stack`
- write `cd stack` to go to the `stack` folder
- write `code stack.cpp` to create a file called `stack.cpp` and open it in the editor

## Problem

You have an empty stack. You need to perform the following queries:

Type 1: Push an integer \\(x\\) to the top of the stack.

Type 2: Print the top element of the stack and pop it. If the stack is empty, print "Empty!" (without quotes) instead.

## Input

The first line contains a single integer \\(q (1 \\leq q \\leq 10^5)\\) — the number of queries.

Each of the next \\(q\\) lines contains a query. The \\(i\\)-th query is described by two integers \\(t_i\\) and \\(x_i (1 \\leq t_i \\leq 2, 1 \\leq x_i \\leq 10^9)\\) — the type of the query and the integer \\(x_i\\).

## Output

For each query of the second type, print the answer on a separate line.

## Example

**Input:**

```text
5
1 1
1 2
2
2
2
```

**Output:**

```text
2
1
Empty!
```

## Test Your Code

Make sure you are in the `stack` directory, then run the following command:

```bash
check50 iti-technical-team/problemset/2026/7/stack
```

## Submit Your Code

Make sure you are in the `stack` directory, then run the following command:

```bash
submit50 iti-technical-team/problemset/2026/7/stack
```
