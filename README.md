# Exercise 3: Resolving Conflicts

- Account A: Seven17777
- Account B: y963782207-arch
- Mode: individual practice using two accounts controlled by one student.

## Shared project plan

Pipeline priority: data quality checks (Account A), then incremental loading (Account B).

## Conflict and resolution

Both feature branches started from commit 324648dbc29187a23431b6764fac69c91317518d.

1. A changed the priority line to data quality checks in PR #1.
2. B changed the same line to incremental loading in PR #2.
3. A merged PR #1 first, creating a conflict in B's PR.
4. B merged main into the feature branch and replaced the conflict markers with the combined priority above.
5. The resolution preserves both contributions: validate data first, then load incrementally.

A reviews the resolved PR before merging it into main. See PR #1, PR #2, and the merge commit history for evidence.
