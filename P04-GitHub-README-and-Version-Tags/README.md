# P4 – GitHub README and Version Tags

## Aim
To document the project using a GitHub README file and understand how to create version tags.

## Repository README
The root `README.md` describes this laboratory repository, lists the practical folders, and identifies the technologies used.

## Git Commands

Check the repository:
```bash
git status
git log --oneline
```

Create an annotated version tag after the P1–P4 work is available locally:
```bash
git tag -a v1.0.0 -m "First version of Web Development Lab"
git tag
git push origin v1.0.0
```

To inspect the tag:
```bash
git show v1.0.0
```

## Description
A README gives visitors an overview of the repository. A Git tag marks a particular commit so that a version can be identified later.

## Result
The repository documentation has been added. The commands above create and publish the version tag `v1.0.0` from the local Git repository.
