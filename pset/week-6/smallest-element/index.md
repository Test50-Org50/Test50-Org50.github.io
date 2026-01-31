---
title: Smallest Element
---

# A. K-th Smallest Element in Sorted Array

## Problem Setup

- login to [CS50 IDE](https://cs50.dev)
- write `cd` in the *terminal* to go to the home directory
- write `mkdir smallest-element` to create a folder called `smallest-element`
- write `cd smallest-element` to go to the `smallest-element` folder
- write `code smallest-element.cpp` to create a file called `smallest-element.cpp` and open it in the editor

## Problem

You are given an unsorted array of \\(n\\) integers and an integer \\(k\\). Your task is to find the \\(k\\)-th smallest element in the array after sorting it.

You can use Selection Sort, Bubble Sort or Insertion Sort.

## Input

The first line contains two integers \\(n\\) and \\(k\\) (\\(1 \\leq k \\leq n \\leq 10^3\\)) — the number of elements in the array and the position of the element to find.

The second line contains \\(n\\) integers \\(a_1, a_2, \dots, a_n\\) (\\(1 \\leq a_i \\leq 10^6\\)) — the elements of the array.

## Output

Print a single integer — the \\(k\\)-th smallest element in the array after applying any sorting algorithm.

## Examples

**Example 1:**

**Input:**

```text
5 3
64 25 12 22 11
```

**Output:**

```text
22
```

**Example 2:**

**Input:**

```text
6 4
30 10 20 50 40 60
```

**Output:**

```text
40
```

## Note

In the first example:

- The sorted array after Sorting: [11, 12, 22, 25, 64].

- The 3-rd smallest element is 22.

In the second example:

- The sorted array after Selection Sort: [10, 20, 30, 40, 50, 60].

- The 4-th smallest element is 40.

## Test Your Code

Make sure you are in the `smallest-element` directory, then run the following command:

```bash
check50 iti-technical-team/problemset/2026/6/smallest-element
```

## Submit Your Code

Make sure you are in the `smallest-element` directory, then run the following command:

```bash
submit50 iti-technical-team/problemset/2026/6/smallest-element
```
