


Use \git cherry-pick\ to apply a specific range of commits from a source branch into the current branch.

\`bash
git checkout main
git cherry-pick 3950485^..536c660
\`

This experiment demonstrates how to selectively bring in changes from \feature-branch\ without merging the entire branch.

Commits cherry-picked:
- 3950485: Modified file.txt in feature branch
- 536c660: Added Experiment 4 files


