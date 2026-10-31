# Git Command Cheat Sheet

A quick reference guide to essential Git commands for version control and GitHub repository management.

## 1. Check Git Version

```bash
git --version
```

**Purpose:** Check the installed Git version.

## 2. Configure Username

```bash
git config --global user.name "Your Name"
```

**Purpose:** Set your Git username.

## 3. Configure Email

```bash
git config --global user.email "your@email.com"
```

**Purpose:** Set your Git email address.

## 4. Display Git Configuration

```bash
git config --list
```

**Purpose:** Display current Git configuration information.

## 5. Clone a Repository

```bash
git clone repository-url
```

**Purpose:** Download a remote repository from GitHub to your local computer.

## 6. Check Repository Status

```bash
git status
```

**Purpose:** Display modified, staged, and untracked files.

## 7. Add Files to Staging Area

```bash
git add .
```

**Purpose:** Stage all changes in the current repository.

To stage a specific file:

```bash
git add filename
```

## 8. Commit Changes

```bash
git commit -m "Your commit message"
```

**Purpose:** Save staged changes as a new commit in the local repository.

## 9. Upload Changes to GitHub

```bash
git push
```

**Purpose:** Upload local commits to the remote GitHub repository.

## 10. Download Updates from GitHub

```bash
git pull
```

**Purpose:** Download and integrate changes from the remote repository.

## 11. View Commit History

```bash
git log --oneline
```

**Purpose:** Display a simplified history of commits.

## 12. Create a New Branch

```bash
git branch branch-name
```

**Purpose:** Create a new branch without switching to it.

## 13. Switch Branch

```bash
git checkout branch-name
```

**Purpose:** Switch to another branch.

Modern alternative:

```bash
git switch branch-name
```

## 14. Merge Branches

```bash
git merge branch-name
```

**Purpose:** Merge changes from another branch into the current branch.

## 15. List All Branches

```bash
git branch
```

**Purpose:** Display all local branches.

## 16. View Remote Repositories

```bash
git remote -v
```

**Purpose:** Display connected remote repositories and their URLs.

## 17. Check Current Branch

```bash
git branch --show-current
```

**Purpose:** Display the name of the currently active branch.

---

## Basic Git Workflow

The following commands represent a typical workflow when working on a project:

```bash
# 1. Check repository status
git status

# 2. Stage changes
git add .

# 3. Commit changes
git commit -m "Describe your changes"

# 4. Upload commits to GitHub
git push
```

## Important Notes

- Git tracks changes in files and directories.
- GitHub hosts Git repositories online.
- A commit records changes locally.
- A push uploads local commits to GitHub.
- A pull downloads and integrates remote changes.
- Branches allow developers to work on different features independently.

**Remember:** Always check `git status` before committing changes.