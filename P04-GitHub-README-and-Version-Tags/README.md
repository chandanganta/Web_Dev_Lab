# P4: GitHub README and version tags

## Aim
Document a project, connect its local repository to GitHub, and create a version tag.

## Suggested README sections
- Project title and description
- Features and technologies
- Steps to run the project
- Author or contact details

## Commands
Replace `URL` with the HTTPS URL of your own GitHub repository.
```bash
git remote add origin URL
git remote -v
git branch -M main
git push -u origin main
git tag -a v1.0 -m "First version"
git tag
git push origin v1.0
```

- `git remote add origin` connects the local repository to GitHub.
- `git remote -v` checks the remote URL.
- `git branch -M main` renames the current branch to main.
- `git push` uploads commits.
- `git tag -a` creates an annotated version tag.
- `git push origin v1.0` uploads the tag.

## Result
The repository has project documentation and a tag marking its first version.
