---
title: Binary Search
---

# B. Binary Search

## Problem Setup

- login to [CS50 IDE](https://cs50.dev)
- write `cd` in the *terminal* to go to the home directory
- write `mkdir binary-search` to create a folder called `binary-search`
- write `cd binary-search` to go to the `binary-search` folder
- write `code binary-search.cpp` to create a file called `binary-search.cpp` and open it in the editor

## Problem

Given \\(2\\) numbers \\(N\\) and \\(Q\\), array \\(A\\) of \\(N\\) numbers and \\(Q\\) queries each one contains a number \\(X\\).

For each query print a single line that contains **YES** if the number \\(X\\) exists in array \\(A\\) otherwise, print **NO**.

## Input

First line contains two numbers \\(N\\) , \\(Q\\) (\\(1 \\leq N, Q \\leq 10^5\\)).

Second line contains \\(N\\) numbers (\\(1 \\leq A_i \\leq 10^9\\)).

Next \\(Q\\) lines contains \\(X\\) (\\(1 \\leq X \\leq 10^9\\)). Note: the array is sorted.

## Output

Print the answer for each query in a single line.

## Example

**Input:**

```text
5 3
1 2 3 4 5
5
3
6
```

**Output:**

```text
YES
YES
NO
```

## Test Your Code

Make sure you are in the `binary-search` directory, then run the following command:

```bash
check50 iti-technical-team/problemset/2026/5/binary-search
```

## Submit Your Code

Make sure you are in the `binary-search` directory, then run the following command:

```bash
submit50 iti-technical-team/problemset/2026/5/binary-search
```
