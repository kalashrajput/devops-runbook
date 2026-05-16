# Git Workflow Reference

## Branch Strategy
- main — stable, production-ready
- feature/* — new additions
- fix/* — bug fixes

## Daily Workflow
1. git checkout -b feature/name
2. make changes + commit
3. push to GitHub
4. raise Pull Request
5. merge to main

## Key Commands
- `git stash` — save incomplete work
- `git rebase` — linear history
- `git cherry-pick` — pick specific commits
- `git tag` — mark releases
