# P2 – Portfolio Repo with an Initial Commit

## Aim
To create a Git repository for a portfolio project and make its initial commit.

## Commands
Run these commands inside a new portfolio project folder. Do not run `git init` inside an existing Git repository.

```bash
git init
git status
git add .
git commit -m "Initial commit"

git branch -M main
git remote add origin YOUR_GITHUB_REPOSITORY_URL
git push -u origin main
```

Replace `YOUR_GITHUB_REPOSITORY_URL` with the URL of the separate GitHub repository created for this practical.

## Description
- `git init` initializes a new local Git repository.
- `git status` displays the current repository status.
- `git add .` stages the project files.
- `git commit -m "Initial commit"` records the first commit.
- `git branch -M main` renames the current branch to main.
- `git remote add origin` connects the local repository to its GitHub repository.
- `git push -u origin main` pushes the main branch to GitHub and sets its upstream.

## Result
A portfolio project repository was initialized, committed, connected to GitHub, and pushed to the main branch.
