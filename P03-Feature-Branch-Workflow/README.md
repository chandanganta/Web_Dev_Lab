# P3 – Feature-Branch Git Workflow

## Aim
To practise creating a feature branch, making a change, and merging it into the main branch.

## Workflow
1. Create a separate branch for the feature.
2. Add the About section to the portfolio page.
3. Commit the changes on the feature branch.
4. Open a pull request and merge it into main.

## Git Commands
```bash
git switch -c p03-feature-branch-workflow
git status
git add .
git commit -m "Add About section"
git switch main
git merge p03-feature-branch-workflow
git log --oneline --graph --all
```

## Result
The feature work is kept separate from main until it is reviewed and merged.
