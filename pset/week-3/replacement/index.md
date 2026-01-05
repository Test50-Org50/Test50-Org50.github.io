---
title: Replacement
---

# D. Do a Replacement

## Problem Setup
- login to [CS50 IDE](https://cs50.dev)
- write `cd` in the *terminal* to go to the home directory
- write `mkdir replacement` to create a folder called `replacement`
- write `cd replacement` to go to the `replacement` folder
- write `code replacement.cpp` to create a file called `replacement.cpp` and open it in the editor

## Problem

You are given an array of \\(n\\) numbers and two indexes \\(a\\) and \\(b\\).

You have to replace the number of index \\(a\\) with the number of index \\(b\\), and vice versa.

## Input

First line contains three numbers \\(n\\), \\(a\\), \\(b\\) where \\(1 \\leq n \\leq 10^4\\) and \\(1 \\leq a, b \\leq n\\) — the size of the array and the indexes you have to do a replacement to it.

Second line contains \\(n\\) numbers \\(a_i\\) where \\(1 \\leq a_i \\leq 10^4\\), the numbers of the array.

## Output

Print the array after the replacement.

## Examples

**Example 1:**

**Input:**
```
5 2 4
1 2 3 4 5
```

**Output:**
```
1 4 3 2 5
```

---

**Example 2:**

**Input:**
```
4 1 4
5 3 2 6
```

**Output:**
```
6 3 2 5
```

## Test Your Code

Make sure you are in the `replacement` directory, then run the following command:

```bash
check50 iti-technical-team/week3/2026/3/replacement
```

## Submit Your Code

Make sure you are in the `replacement` directory, then run the following command:

```bash
submit50 iti-technical-team/week3/2026/3/replacement
```
