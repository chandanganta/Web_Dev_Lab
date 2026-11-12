# P3 – Feature-Branch Git Workflow

## Aim
To understand how Git branches are created, used, and merged.

## Practical
This practical demonstrates the branch workflow through Git commands and README documentation only. No HTML or CSS files are required.

## Commands
```bash
git switch -c p03-feature-branch-workflow
git status
git add README.md
git commit -m "Document P3 branch workflow"
git switch main
git merge p03-feature-branch-workflow
git branch
git log --oneline --graph --all
```

## Description
- `git switch -c` creates and switches to a new branch.
- `git status` checks the working-tree status.
- `git add README.md` stages the practical documentation.
- `git commit` records the change on the current branch.
- `git switch main` returns to the main branch.
- `git merge` combines the feature branch into main.
- `git branch` lists local branches.
- `git log --oneline --graph --all` displays the branch and commit history.

## Result
A feature branch was created, used for a documentation change, and merged into the main branch.
