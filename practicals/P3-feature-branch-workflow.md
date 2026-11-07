# P3 – Feature-Branch Git Workflow

## Aim
Make a change on a separate branch, commit it, and merge it into the main branch.

## Commands used
```bash
git switch -c feature/about-section
git status
git add about.html
git commit -m "P3: Add about section"
git push -u origin feature/about-section

git switch main
git merge feature/about-section
git push origin main
```

## Explanation
A feature branch keeps work separate from the main branch. The file `about.html` was created on `feature/about-section`, staged and committed. The branch was pushed to GitHub, then merged into `main`.

## Result
The About page was committed on the feature branch and merged into the main branch.

## Conclusion
The feature-branch workflow was used to isolate, publish and integrate a change.
