# Problem Solving

A collection of competitive-programming solutions written in C++. The repository contains standalone solutions for problems from several online judges, organized by platform and, where useful, by algorithmic topic or training phase.

## Contents

The repository currently contains **347 C++ solutions**:

| Platform | Solutions |
| --- | ---: |
| [Codeforces](<Problem-Solving/Codeforces>) | 232 |
| [CSES](<Problem-Solving/CSES>) | 25 |
| [SPOJ](<Problem-Solving/SPOJ>) | 25 |
| [HackerRank](<Problem-Solving/Hacker%20Rank>) | 21 |
| [UVA](<Problem-Solving/UVA>) | 20 |
| [AtCoder](<Problem-Solving/At%20Coder>) | 8 |
| [LightOJ](<Problem-Solving/Light%20OJ>) | 7 |
| [CodeChef](<Problem-Solving/CodeChef>) | 3 |
| [Yosupo Judge](<Problem-Solving/Yosupo%20Judge>) | 3 |
| [POJ](<Problem-Solving/POJ>) | 2 |
| [DMOJ](<Problem-Solving/DMOJ>) | 1 |

Topics represented include:

- Dynamic programming
- Data structures and range queries
- Graph algorithms and trees
- Divide and conquer
- Greedy algorithms and brute force
- Mathematics and number theory
- String algorithms
- Computational geometry

## Repository layout

```text
Problem-Solving/
├── Codeforces/
│   ├── Edu/
│   ├── Gyms/
│   └── Phase 3-1/, Phase 3-2/, Phase 3-3/, Phase 4-1/
├── CSES/
├── SPOJ/
├── Hacker Rank/
├── UVA/
├── At Coder/
└── ...
```

Most source files use the problem identifier or title as their filename. Each file is intended to be compiled and submitted independently.

## Compiling and running a solution

The solutions do not require a repository-wide build system. A C++17-compatible compiler is recommended:

```bash
g++ -std=c++17 -O2 -Wall -Wextra \
  "Problem-Solving/CSES/Range Queries/Static Range Sum Queries.cpp" \
  -o solution

./solution < input.txt
```

Some solutions include `bits/stdc++.h`, so GCC or another compiler providing that header is recommended. Input and output formats follow the original problem statements.

## Adding a solution

1. Place the source file under the appropriate online judge directory.
2. Keep the solution self-contained with a `main` function.
3. Use a descriptive filename, preferably including the problem ID and title.
4. Compile the file locally with the expected language standard before submitting it.

## Notes

- Solutions are primarily practice and reference implementations; style and level of abstraction may vary.
- Problem statements and test data are not included. Refer to the relevant online judge for the original statement and constraints.
