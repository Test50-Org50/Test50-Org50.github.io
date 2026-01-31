---
title: Dynamic Array
---

# A. Dynamic Array

## Problem Setup

- login to [CS50 IDE](https://cs50.dev)
- write `cd` in the *terminal* to go to the home directory
- write `mkdir dynamic-array` to create a folder called `dynamic-array`
- write `cd dynamic-array` to go to the `dynamic-array` folder
- write `code dynamic-array.cpp` to create a file called `dynamic-array.cpp` and open it in the editor

## Problem

You are given a sequence of integers. It is unknown how many integers are in the sequence.

You must keep taking this sequence of integers and store them until you receive \\(-1\\) in the input.

When you receive \\(-1\\) in the input, you must start printing the integers in the sequence in the order they were received.

## Input

Given an unknown number of integers. The integers are in the range of \\(1\\) to \\(10^9\\).

At the end of the input, you will receive \\(-1\\).

## Output

Print the integers in the sequence in the order they were received.

## Example

**Input:**

```text
5
13
2
7
11
20
-1
```

**Output:**

```text
5 13 2 7 11 20
```

## Test Your Code

Make sure you are in the `dynamic-array` directory, then run the following command:

```bash
check50 iti-technical-team/problemset/2026/7/dynamic-array
```

## Submit Your Code

Make sure you are in the `dynamic-array` directory, then run the following command:

```bash
submit50 iti-technical-team/problemset/2026/7/dynamic-array
```
