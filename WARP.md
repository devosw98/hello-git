# WARP.md

This file provides guidance to WARP (warp.dev) when working with code in this repository.

## Repository Overview

This is a Git learning/tutorial repository containing simple Python scripts used to practice Git workflows, branching, merging, and conflict resolution. The repository is connected to GitHub at `github.com:devosw98/hello-git`.

## Common Commands

### Running Python Scripts
```pwsh
python hellogit.py
python hellogit2.py
python hellogit3.py
python login.py
```

### Git Operations
```pwsh
# View commit history
git log --oneline

# Check branches
git branch -a

# View file status
git status

# Create and switch branches (common pattern in this repo)
git checkout -b <branch-name>

# Merge branches
git merge <branch-name>
```

## Repository Structure

- `hellogit.py`, `hellogit2.py`, `hellogit3.py` - Simple Python scripts used for Git practice
- `login.py` - Feature branch script (was merged from separate branch)
- `data.txt` - Ignored data file (not tracked)
- `markdown_exercise.md` - Markdown syntax practice/reference
- `node_modules/` - Empty directory (ignored, no package.json exists)

## Development Patterns

- This repository uses a simple branching workflow where feature branches are created, modified, and merged back to `main`
- Conflict resolution practice is part of the learning process (visible in commit history)
- The `.gitignore` excludes `**/data.txt` and `**/node_modules`

## Notes

- No build system, linting, or test framework is configured
- Scripts are standalone and require only Python runtime
- Repository history shows commits in Spanish, indicating Spanish-speaking learning context
