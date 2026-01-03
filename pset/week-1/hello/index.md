---
title: Hello, World!
---

# A. Hello, World!

## Problem Setup
- login to [CS50 IDE](https://cs50.dev)
- write `cd` in the *terminal* to go to the home directory
- write `mkdir hello` to create a folder called `hello`
- write `cd hello` to go to the `hello` folder
- write `code hello.cpp` to create a file called `hello.cpp` and open it in the editor

## Problem

Write a program that reads a person's name and age, and outputs a greeting message in the format `"Hello s, you are n years old."`.

where \\(s\\) is the name of the person and \\(n\\) is the age of the person.

## Input

A single line containing:

- A string \\(s\\) where \\(1 \\leq \|s\| \\leq 100\\) — the name of the person, where \\(\|s\|\\) is the length of the string \\(s\\).
- An integer \\(n\\) where \\(1 \\leq n \\leq 100\\) — the age of the person.

## Output

Print a single line with the greeting message in the format:

```markdown
Hello s, you are n years old.
```

## Example

**Input:**
```
Mohammed 24
```

**Output:**
```
Hello Mohammed, you are 24 years old.
```


## Test Your Code

Make sure you are in the `hello` directory, then run the following command:

```bash
check50 iti-technical-team/week1/2026/1/hello
```

## Submit Your Code

Make sure you are in the `hello` directory, then run the following command:

```bash
submit50 iti-technical-team/week1/2026/1/hello
```