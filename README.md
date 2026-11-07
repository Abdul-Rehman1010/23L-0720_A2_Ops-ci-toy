# 23L-0720_A2_Ops-ci-toy

Throwaway repository for the GitHub Actions warm-up of MLOps Assignment 2 (Task 6.6, toy part).

The workflow in `.github/workflows/tests.yml` runs `pytest` on every push, on Python 3.11 and 3.12 (a build matrix).
The first commit contains a deliberate bug in `is_even` (red run); the second commit fixes it (green run).
