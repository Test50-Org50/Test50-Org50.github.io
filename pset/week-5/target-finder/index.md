---
title: Target Finder
---

# D. Target Find

## Problem Setup

- login to [CS50 IDE](https://cs50.dev)
- write `cd` in the *terminal* to go to the home directory
- write `mkdir target-finder` to create a folder called `target-finder`
- write `cd target-finder` to go to the `target-finder` folder
- write `code target-finder.cpp` to create a file called `target-finder.cpp` and open it in the editor

## Problem

Given \\(2\\) numbers \\(N\\) and \\(Q\\), array \\(A\\) of \\(N\\) numbers and \\(Q\\) queries each one contains two numbers \\(x\\) and \\(z\\).

For each query print a single line that contains **YES** if there is a number \\(y\\) exist in the array \\(A\\) satisfy \\(x + y = z\\). otherwise, print **NO**.

## Input

First line contains two numbers \\(N\\) , \\(Q\\) (\\(1 \\leq N, Q \\leq 10^5\\)).

Second line contains \\(N\\) numbers (\\(1 \\leq A_i \\leq 10^9\\)).

Next \\(Q\\) lines contains \\(x\\), \\(z\\) (\\(1 \\leq x, z \\leq 10^9\\)). Note: the array is sorted.

## Output

Print the answer for each query in a single line.

## Example

**Input:**

```text
5 3
1 2 3 4 5
4 5
3 3
1 6
```

**Output:**

```text
YES
NO
YES
```

## Test Your Code

Make sure you are in the `target-finder` directory, then run the following command:

```bash
check50 iti-technical-team/problemset/2026/5/target-finder
```

## Submit Your Code

Make sure you are in the `target-finder` directory, then run the following command:

```bash
submit50 iti-technical-team/problemset/2026/5/target-finder
```
