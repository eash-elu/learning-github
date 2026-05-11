# learning-github

A small sandbox repository for practicing **Git** and **GitHub** workflows: commits, branches, pull requests, and collaboration basics.

## Getting started

Clone this repository:

```bash
git clone https://github.com/eash-elu/learning-github.git
cd learning-github
```

## Working on a branch

Create a branch, commit locally, and publish it (example branch name: `learningOne`):

```bash
git switch -c learningOne          # create and switch (omit -c if it already exists)
git add .
git commit -m "Describe your change"
git push -u origin learningOne     # first push; later you can use git push
```

Switch back to the default branch when you are done:

```bash
git switch main
git pull origin main
```

## Useful commands

| Task | Command |
|------|---------|
| See what changed | `git status` |
| Stage changes | `git add .` or `git add <file>` |
| Commit | `git commit -m "Describe your change"` |
| Push a branch | `git push origin <branch>` |
| Pull latest for current branch | `git pull` |

## License

This project is for learning; add a license file if you plan to share code more broadly.
