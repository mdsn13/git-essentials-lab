# Library Demo Run Guide

## Prerequisites

Install the tools required by the project:

- Python 3.
- JDK (Java Development Kit), providing both `java` and `javac`.

Ensure these commands are available in your terminal:

```bash
python3 --version
java -version
javac -version
```

On Windows, you can check Python with `py -3 --version`.

## Run the demo

Open a terminal in the repository root directory, where `run.py` is located.

Run:

```bash
python3 run.py demo
```

On Windows, you can alternatively use:

```bash
py -3 run.py demo
```

## What the demo does

The demo uses the fixed date `2026-09-01` and demonstrates the library's borrowing workflow:

- Displays borrowing limits: two books per student and two per faculty member.
- Searches the catalog for `git`.
- Loans the book `Git Essentials` to Alex.
- Displays the due date: `2026-09-15`.
- Returns the book and displays a fee of `0`.
- Shows that no active loans remain after the return.

In this exercise's starting version, title search is case-sensitive.
The query `git` returns an empty list (`[]`), even though the catalog contains `Git Essentials`.