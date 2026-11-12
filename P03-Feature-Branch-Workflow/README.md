# P3 – Feature-Branch Git Workflow

## Aim
To create a feature branch, make a change, and push the branch to GitHub.

## Commands
Run these commands from the project repository:

```bash
git switch -c feature/my-change
git status
git add .
git commit -m "Add a portfolio change"
git push -u origin feature/my-change
```

## Description
- `git switch -c feature/my-change` creates and switches to a new feature branch.
- `git status` displays the current working-tree status.
- `git add .` stages the changes.
- `git commit -m "Add a portfolio change"` records the changes in the feature branch.
- `git push -u origin feature/my-change` pushes the feature branch to GitHub and sets its upstream.

## Result
A feature branch was created, updated with a commit, and pushed to the remote GitHub repository.
