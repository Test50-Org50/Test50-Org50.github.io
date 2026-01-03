---
title: Compare
---

# C. Compare

## Problem Setup
- login to [CS50 IDE](https://cs50.dev)
- write `cd` in the *terminal* to go to the home directory
- write `mkdir compare` to create a folder called `compare`
- write `cd compare` to go to the `compare` folder
- write `code compare.cpp` to create a file called `compare.cpp` and open it in the editor

## Problem

Given 2 numbers \\(a\\) and \\(b\\). Compare them and determine if \\(a\\) is greater than \\(b\\), less than \\(b\\), or equal to \\(b\\).

## Input

One line containing two integers \\(a\\) and \\(b\\) where \\(-10^3 \\leq a, b \\leq 10^3\\).

## Output

Print the result of the comparison:
- `Greater` if \\(a > b\\)
- `Less` if \\(a < b\\)
- `Equal` if \\(a = b\\)

## Examples

**Example 1:**

Input:
```
5 1
```

Output:
```
Greater
```

---

**Example 2:**

Input:
```
5 5
```

Output:
```
Equal
```

---

**Example 3:**

Input:
```
4 9
```

Output:
```
Less
```


## Test Your Code

Make sure you are in the `compare` directory, then run the following command:

```bash
check50 iti-technical-team/week1/2026/1/compare
```

## Submit Your Code

Make sure you are in the `compare` directory, then run the following command:

```bash
submit50 iti-technical-team/week1/2026/1/compare
```