# Git and GitHub Commands - Complete Notes
=============================
## 1. GIT BASICS
=============================
- git --version -> Check Git version
- git config --global user.name "Your Name" -> Set username
- git config --global user.email "youremail@example.com" -> Set email
- git config --list -> Show all config details 
 

=============================
## 2. INITIALIZING REPOSITORY
=============================

- git init -> Initialize a local repository
- git clone <url> -> Clone a remote repository
  
=============================
## 3. STAGING & COMMITTING
=============================

- git status -> Check status of files
- git add <filename> -> Add specific file to staging
- git add . -> Add all files to staging
- git commit -m "message" -> Commit staged files with a message
- git commit -am "message"-> Add and commit tracked files in one step
- 
=============================
## 4. BRANCHING
=============================

- git branch -> List all branches
- git branch <name> -> Create a new branch
- git checkout <name> -> Switch to a branch
- git checkout -b <name> -> Create and switch to a new branch
- git merge <branch> -> Merge branch into current
- git branch -d <name> -> Delete a branch
- 
=============================
## 5. REMOTE REPOSITORIES
=============================

- git remote -> List remotes
- git remote -v -> Show remote URLs
- git remote add origin <url> -> Add remote repository
- git push -u origin main -> Push to remote main branch
- git pull origin main -> Pull updates from remote
- git fetch -> Fetch updates without merging
- 
=============================
## 6. UNDO & RESET COMMANDS
=============================

- git restore <file> -> Discard changes in working directory
- git reset <file> -> Unstage a file
- git reset --hard HEAD -> Reset all changes to last commit
- git revert <commit> -> Revert a specific commit
- 
=============================
## 7. VIEWING HISTORY
=============================

- git log -> View commit history
- git log --oneline -> Compact view of commits
- git diff -> Show file differences
- git show <commit> -> Show details of a specific commit
- 
=============================
## 8. GITHUB COMMANDS
=============================

- Create a repository on GitHub via browser
- git remote add origin <url> -> Connect local repo to GitHub
- git push -u origin main - git push - git pull - git clone <url> -> Push first commit
-> Push changes
-> Pull updates from GitHub
-> Clone GitHub repo
  
=============================
## 9. TAGS
=============================

- git tag -> List tags
- git tag -a v1.0 -m "Version 1" -> Create annotated tag
- git push origin v1.0 -> Push tag to GitHub
- 
=============================
## 10. IGNORING FILES
=============================

- Create .gitignore file and list files/folders to ignore
- 
=============================
## 11. STASHING
=============================

- git stash -> Temporarily save uncommitted changes
- git stash list -> List stashed changes
- git stash pop -> Apply last stash and remove it
- git stash apply -> Apply last stash without removing it
- 
=============================
## 12. ALIASES
=============================

- git config --global alias.st status
- git config --global alias.cm "commit -m"
- 
=============================
## 13. COMMON SHORTCUTS
=============================

- git diff HEAD~1 HEAD -> Compare last two commits
- git log --graph --oneline --all-> Visual branch history
- git fetch --all --prune -> Sync with remote branches
- 
=============================
## 14. GITHUB EXTRA
=============================

- Fork -> Copy another repo to your GitHub
- Pull Request -> Propose changes to original repo
- Issues -> Track bugs or requests
- Actions -> Automate workflows
- 
=============================
## 15. DELETE COMMANDS
=============================

- git rm <file> -> Remove file from repo and stage
- git rm --cached <file> -> Remove file from repo but keep local
- git clean -f -> Remove untracked files

