Task5 - both branches advanced after split, fast-forward was impossible

Submission answers to 3 questions:
1. First:
   1. Fast forward is performed when `main` has no new commits after the feature branch was created, `main` pointer just moves forward.
   2. Merge commit is created when both branches contain new commits, Git needs to combine 2 histories.
2. Second:
   1. `merge` saves the real branch structure and adds a merge commit, history is fully explicit.
   2. `rebase` rewrites feature branch commits on top of the `main` + changes the commit hashes.
3. Third:
   4. Conflict was triggered by editing the same code fragment in `CalculateMin(int[] values)` body(`main` and `feature-conflict` branches). The conflict was resolved by picking a single final version, staging the resolved file and pushing the final result.