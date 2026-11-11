## 1. Introduction to Version Control
Version control is a system that records changes to files over time.

**Key Features:**
- Tracks modifications to files.
- Identifies who made changes and when.
- Restores previous versions when needed.
- Supports multiple contributors.

**Common Problems Without Version Control:**
- Files may get overwritten accidentally.
- Previous working versions may be lost.
- Finding the source of an error becomes difficult.
- Combining work from multiple contributors becomes complicated.
**Key Idea:** Version control keeps changes organized and makes project history easy to track.

## 2. Types of Version Control Systems
There are three main types of version control systems:
1. **Local Version Control:** Stores file versions on a local computer.
2. **Centralized Version Control:** Stores versions on a central server. Example: SVN.
3. **Distributed Version Control:** Every user has a complete copy of the repository. Example: Git.

## 3. Git: Introduction
Git is a distributed version control system used to track changes in files.
- Tracks changes in a project.
- Stores project history using commits.
- Supports branches for separate development.
- Allows offline work.
- Helps combine changes from different contributors.

## 4. How Git Works
Git works through three main steps:
1. **Working Directory:** Where files are created or modified.
2. **Staging Area:** Where changes are selected before committing.
3. **Repository:** Stores committed changes and project history.

## 5. Git Architecture
Git has three main components:
1. **Working Directory:** Contains project files.
2. **Local Repository:** Stores changes and commit history on the computer.
3. **Remote Repository:** Stores the project online and allows collaboration.

## 5. Installing and Verifying Git
Git can be installed on Windows, Linux and macOS.
**Verify Git Installation:**
Use the following command to check whether Git is installed:
```bash
git --version
```
**Git Version:**
<img src="git-version.png" width="600">

## 6. Configuring Git
Before using Git, configure your username and email.
**Set Username, Email and verify configuration:**
```bash
git config --global user.name "Student Name"
git config --global user.email "student@example.com"
git config --global --list
```
**Name and Email:**
<img src="git-name-email.png" width="600">

## 7. Creating a Git Repository
A Git repository stores project files and their version history.
**Steps to Create a Repository:**
```bash
mkdir my-project
cd my-project
git init
```
<img src="git-repo.png" width="600">

## 8. Basic Git Workflow
A basic Git workflow involves the following commands:
| Command | Purpose |
|---|---|
| `git status` | Checks the current repository status. |
| `git add .` | Stages all changes. |
| `git commit -m "message"` | Saves changes in the repository. |
| `git push` | Uploads commits to a remote repository. |

These commands help manage and track project changes.
