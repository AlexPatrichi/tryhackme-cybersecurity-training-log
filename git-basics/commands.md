# Git & Bash Learning Log & Cheat Sheet

This file documents the key Git and Bash commands I’ve personally used while building my cybersecurity training portfolio.
It serves as both a reference and a learning log for workflows, file management, and version control. 

---

## Git Basics Table

| Command | Description |
|---------|-------------|
| `git clone <repo-url>` | Copying my GitHub repository to my local machine |
| `git status` | Checking file status (modified, staged, untracked) |
| `git add <file>` | Selecting specific files to commit |
| `git add .` | Staging all changes in the repo |
| `git commit -m "message"` | Saving changes with a clear commit message |
| `git push` | Uploading my work to GitHub. Pushes local commits to the remote repository |
| `git pull` | Syncing local repository with GitHub |
| `git branch` | Viewing existing branches in the repo |
| `git branch <branch-name>` | Creating a new branch |
| `git checkout <branch-name>` | Switching to another branch |
| `git merge <branch>` | Merging another branch into the current one |
| `git log` | Viewing commit history |
| `git diff` | Viewing file differences before committing |

---

## How Git Tracks File Changes (States)  

Understanding how Git tracks file states helped me control what gets saved in version history instead of committing blindly.  

Main states:  

**Untracked** – New files Git hasn’t seen before  
(Created, but not added to version control yet)  

**Modified** – Existing files that have been changed  
(Edited locally, but not prepared for commit)  

**Staged** – Files selected for the next commit  
(Prepared to be saved in Git history)  

**Committed** – Files permanently saved in the repository history  
(Stored in Git history)  

Commands involved:  
git add <file>       - prepares changes for commit  
git commit -m "msg"  - records changes in version history  
git push             - uploads committed changes to GitHub  

---

## Merge Conflicts

I experienced merge conflicts while editing README.md and learned how Git handles conflicting changes between local and remote versions.

| Command / Concept | Description |
|------------------|-------------|
| `<<<<<<< HEAD` | My local version of the file |
| `=======` | Separator between local and remote changes |
| `>>>>>>> origin/main` | Remote (GitHub) version of the file |

Conflicts are solved by:  
1. Open the conflicted file
2. Compare both versions
3. Keep the correct content
4. Remove conflict markers
5. Stage the file
6. Commit the fix
7. Push the update

---

## Bash Commands

| Command | Description |
|---------|-------------|
| `pwd` | Knowing exactly where I am in the system |
| `ls` | Lists files and folders in the directory |
| `mkdir <folder>` | Creates a new folder |
| `touch <file>` | Creates a new empty file |
| `cd <folder>` | Navigating between folders |
| `rm <file>` | Deletes a file |
| `rm -r <folder>` | Deletes a folder and its contents |

---

## Best Practices

- Commit small and frequently with clear messages  
- Pull before editing to avoid conflicts (git pull) 
- Stage only the files you intend to commit  
- Keep folder and file structure clean and consistent  
- Use descriptive file names and Markdown headers for readability
