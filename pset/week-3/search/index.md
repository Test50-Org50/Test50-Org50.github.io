---
title: Search
---

# C. Search

## Problem Setup
- login to [CS50 IDE](https://cs50.dev)
- write `cd` in the *terminal* to go to the home directory
- write `mkdir search` to create a folder called `search`
- write `cd search` to go to the `search` folder
- write `code search.cpp` to create a file called `search.cpp` and open it in the editor

## Problem

Given an array of \\(n\\) elements and a value \\(x\\), your task is to find the first index in the array whose value equals \\(x\\).

## Input

The first line contains two numbers \\(n\\) and \\(x\\) where \\(1 \\leq n \\leq 10^4\\) and \\(1 \\leq x \\leq 10^5\\) — the size of the array and the value you have to find.

The second line contains \\(n\\) elements, \\(a_i\\) where \\(1 \\leq a_i \\leq 10^5\\) — the elements of the array \\(n\\).

## Output

Print the first index which equals \\(x\\) or determine it doesn't exist: "notfound".

## Examples

**Example 1:**

**Input:**
```
6 2
1 2 3 4 5 6
```

**Output:**
```
1
```

---

**Example 2:**

**Input:**
```
3 3
5 22 1
```

**Output:**
```
notfound
```

## Test Your Code

Make sure you are in the `search` directory, then run the following command:

```bash
check50 iti-technical-team/week3/2026/3/search
```

## Submit Your Code

Make sure you are in the `search` directory, then run the following command:

```bash
submit50 iti-technical-team/week3/2026/3/search
```
