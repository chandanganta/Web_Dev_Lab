# P3: Feature-branch Git workflow

## Aim
Create a feature branch, commit a change, and merge it into main.

## Commands
```bash
git branch
git switch -c feature
```

Make a small change to a project file, then run:
```bash
git status
git add .
git commit -m "Add portfolio feature"
git switch main
git merge feature
git branch
```

- `git branch` lists branches.
- `git switch -c feature` creates and opens a new branch.
- `git add .` stages the changes.
- `git commit` saves the changes on that branch.
- `git switch main` returns to main.
- `git merge feature` merges the feature branch into the current branch.

## Result
A change is developed separately and merged into main.
