# 1. Git Configuration Commands

## 1.1 git config --global user.name
Syntax:
git config --global user.name

Purpose:
Sets the global username for Git commits.

Example:
git config --global user.name "Harika"

Screenshot:![alt text](image.png)

---

## 1.2 git config --global user.email
Syntax:
git config --global user.email

Purpose:
Sets the global email for Git commits.

Example:
git config --global user.email "harika@gmail.com"

Screenshot:

---

## 1.3 git config --list
Syntax:
git config --list

Purpose:
Displays all git configuration settings.

Example:
git config --list

Screenshot:![alt text](image-1.png)

---

## 1.4 git config --unset
Syntax:
git config --unset

Purpose:
Removes a configuration value.

Example:
git config --unset user.name

Screenshot:

---

# 2. Repository Setup Commands

## 2.1 git init
Syntax:
git init

Purpose:
Initializes a new Git repository.

Example:
git init myproject

Screenshot:![alt text](image-2.png)

---

## 2.2 git clone
Syntax:
git clone

Purpose:
Creates a copy of a remote repository.

Example:
git clone https://github.com/user/repo.git

Screenshot:![alt text](image-3.png)

---

## 2.3 git clone --branch
Syntax:
git clone --branch

Purpose:
Clones a specific branch from repository.

Example:
git clone --branch dev https://github.com/user/repo.git

Screenshot:![alt text](image-4.png)

---

## 2.4 git clone --depth
Syntax:
git clone --depth

Purpose:
Creates a shallow clone with limited commit history.

Example:
git clone --depth 1 https://github.com/user/repo.git

Screenshot:![alt text](image-5.png)

---

# 3. Repository Status & Inspection

## 3.1 git status
Syntax:
git status

Purpose:
Shows the current status of files in repository.

Example:
git status

Screenshot:![alt text](image-6.png)

---

## 3.2 git log
Syntax:
git log

Purpose:
Displays commit history.

Example:
git log

Screenshot:![alt text](image-7.png)

---

## 3.3 git log --oneline
Syntax:
git log --oneline

Purpose:
Shows commit history in short one line format.

Example:
git log --oneline

Screenshot:![alt text](image-8.png)

---

## 3.4 git log --graph
Syntax:
git log --graph

Purpose:
Displays commit history as a visual graph.

Example:
git log --graph

Screenshot:![alt text](image-9.png)

---

## 3.5 git show
Syntax:
git show

Purpose:
Displays details of a specific commit.

Example:
git show a1b2c3

Screenshot:![alt text](image-10.png)

---

## 3.6 git diff
Syntax:
git diff

Purpose:
Shows changes between working directory and last commit.

Example:
git diff

Screenshot:![alt text](image-11.png)

---

## 3.7 git diff --staged
Syntax:
git diff --staged

Purpose:
Shows staged changes waiting to be committed.

Example:
git diff --staged

Screenshot:![alt text](image-12.png)

---

## 3.8 git blame
Syntax:
git blame

Purpose:
Shows who modified each line of a file.

Example:
git blame index.js

Screenshot:![alt text](image-13.png)

---

## 3.9 git reflog
Syntax:
git reflog

Purpose:
Shows history of reference updates.

Example:
git reflog

Screenshot:![alt text](image-14.png)

---

## 3.10 git shortlog
Syntax:
git shortlog

Purpose:
Summarizes commit history by author.

Example:
git shortlog

Screenshot:![alt text](image-15.png)

---

# 4. File Tracking Commands

## 4.1 git add
Syntax:
git add

Purpose:
Adds file changes to staging area.

Example:
git add file.txt

Screenshot:![alt text](image-16.png)

---

## 4.2 git add .
Syntax:
git add .

Purpose:
Adds all modified files to staging area.

Example:
git add .

Screenshot:![alt text](image-16.png)

---

## 4.3 git add -p
Syntax:
git add -p

Purpose:
Adds specific parts of changes interactively.

Example:
git add -p

Screenshot:![alt text](image-17.png)

---

## 4.4 git restore
Syntax:
git restore

Purpose:
Restores file to last committed state.

Example:
git restore file.txt

Screenshot:![alt text](image-18.png)

---

## 4.5 git restore --staged
Syntax:
git restore --staged

Purpose:
Unstages a staged file.

Example:
git restore --staged file.txt

Screenshot:![alt text](image-19.png)

---

## 4.6 git rm
Syntax:
git rm

Purpose:
Removes file from repository and staging area.

Example:
git rm file.txt

Screenshot:![alt text](image-20.png)

---

## 4.7 git mv
Syntax:
git mv

Purpose:
Renames or moves a file.

Example:
git mv old.txt new.txt

Screenshot:![alt text](image-21.png)

---

# 5. Commit Commands

## 5.1 git commit
Syntax:
git commit

Purpose:
Records staged changes to repository.

Example:
git commit

Screenshot:![alt text](image-22.png)

---

## 5.2 git commit -m
Syntax:
git commit -m

Purpose:
Commits with a message.

Example:
git commit -m "Initial commit"

Screenshot:![alt text](image-24.png)

---

## 5.3 git commit --amend
Syntax:
git commit --amend

Purpose:
Modifies the most recent commit.

Example:
git commit --amend

Screenshot:![alt text](image-25.png)

---

## 5.4 git commit --no-edit
Syntax:
git commit --no-edit

Purpose:
Amends commit without changing the commit message.

Example:
git commit --amend --no-edit

Screenshot:![alt text](image-26.png)

---

# 6. Branch Management Commands

## 6.1 git branch
Syntax:
git branch

Purpose:
Lists all branches in repository.

Example:
git branch

Screenshot:![alt text](image-27.png)

---

## 6.2 git branch -a
Syntax:
git branch -a

Purpose:
Lists local and remote branches.

Example:
git branch -a

Screenshot:![alt text](image-28.png)

---

## 6.3 git branch -d
Syntax:
git branch -d

Purpose:
Deletes a branch safely.

Example:
git branch -d feature

Screenshot:![alt text](image-29.png)

---

## 6.4 git branch -D
Syntax:
git branch -D

Purpose:
Force deletes a branch.

Example:
git branch -D feature

Screenshot:![alt text](image-30.png)

---

## 6.5 git checkout
Syntax:
git checkout

Purpose:
Switches to another branch.

Example:
git checkout main

Screenshot:![alt text](image-31.png)

---

## 6.6 git checkout -b
Syntax:
git checkout -b

Purpose:
Creates and switches to new branch.

Example:
git checkout -b feature

Screenshot:![alt text](image-32.png)

---

## 6.7 git switch
Syntax:
git switch

Purpose:
Switches between branches.

Example:
git switch main

Screenshot:![alt text](image-33.png)

---

## 6.8 git switch -c
Syntax:
git switch -c

Purpose:
Creates and switches to a new branch.

Example:
git switch -c dev

Screenshot:![alt text](image-34.png)

---

# 7. Merge & Integration Commands

## 7.1 git merge
Syntax:
git merge

Purpose:
Merges one branch into another.

Example:
git merge feature

Screenshot:![alt text](image-35.png)

---

## 7.2 git merge --no-ff
Syntax:
git merge --no-ff

Purpose:
Creates a merge commit even if fast forward is possible.

Example:
git merge --no-ff feature

Screenshot:![alt text](image-36.png)

---

# 8. Remote Repository Commands

## 8.1 git remote
Syntax:
git remote

Purpose:
Displays remote repositories.

Example:
git remote

Screenshot:![alt text](image-37.png)

---

## 8.2 git remote -v
Syntax:
git remote -v

Purpose:
Shows remote repository URLs.

Example:
git remote -v

Screenshot:![git ](image-38.png)

---

## 8.3 git remote add
Syntax:
git remote add

Purpose:
Adds a remote repository.

Example:
git remote add origin https://github.com/user/repo.git

Screenshot:![alt text](image.png)

---

## 8.4 git remote remove
Syntax:
git remote remove

Purpose:
Removes a remote repository.

Example:
git remote remove origin

Screenshot:![alt text](image.png)

---

## 8.5 git fetch
Syntax:
git fetch

Purpose:
Downloads changes from remote repository.

Example:
git fetch

Screenshot:![alt text](image.png)

---

## 8.6 git fetch --all
Syntax:
git fetch --all

Purpose:
Fetches changes from all remotes.

Example:
git fetch --all

Screenshot:![alt text](image.png)

---

## 8.7 git pull
Syntax:
git pull

Purpose:
Fetches and merges remote changes.

Example:
git pull origin main

Screenshot:![alt text](image.png)

---

## 8.8 git pull --rebase
Syntax:
git pull --rebase

Purpose:
Fetches and rebases local changes.

Example:
git pull --rebase origin main

Screenshot:![alt text](image.png)

---

## 8.9 git push
Syntax:
git push

Purpose:
Uploads local commits to remote repository.

Example:
git push

Screenshot:![alt text](image.png)

---

## 8.10 git push -u origin branch-name
Syntax:
git push -u origin branch-name

Purpose:
Pushes branch and sets upstream tracking.

Example:
git push -u origin main

Screenshot:![alt text](image.png)

---

## 8.11 git push --force
Syntax:
git push --force

Purpose:
Force pushes changes to remote.

Example:
git push --force

Screenshot:![alt text](image.png)

---

# 9. Stash Commands

## 9.1 git stash
Syntax:
git stash

Purpose:
Temporarily saves uncommitted changes.

Example:
git stash

Screenshot:![alt text](image.png)

---

## 9.2 git stash list
Syntax:
git stash list

Purpose:
Displays list of stashed changes.

Example:
git stash list

Screenshot:![alt text](image.png)

---

## 9.3 git stash pop
Syntax:
git stash pop

Purpose:
Applies and removes latest stash.

Example:
git stash pop

Screenshot:![alt text](image.png)

---

## 9.4 git stash apply
Syntax:
git stash apply

Purpose:
Applies stash without removing it.

Example:
git stash apply

Screenshot:![alt text](image.png)

---

## 9.5 git stash drop
Syntax:
git stash drop

Purpose:
Deletes a specific stash.

Example:
git stash drop

Screenshot:![alt text](image.png)

---

## 9.6 git stash clear
Syntax:
git stash clear

Purpose:
Deletes all stash entries.

Example:
git stash clear

Screenshot:![alt text](image.png)

---

# 10. Reset & Undo Commands

## 10.1 git reset
Syntax:
git reset

Purpose:
Resets current HEAD to a previous state.

Example:
git reset HEAD~1

Screenshot:![alt text](image.png)

---

## 10.2 git reset --soft
Syntax:
git reset --soft

Purpose:
Moves HEAD but keeps staged changes.

Example:
git reset --soft HEAD~1

Screenshot:![alt text](image.png)

---

## 10.3 git reset --mixed
Syntax:
git reset --mixed

Purpose:
Moves HEAD and unstages files.

Example:
git reset --mixed HEAD~1

Screenshot:![alt text](image.png)

---

## 10.4 git reset --hard
Syntax:
git reset --hard

Purpose:
Resets repository and deletes changes.

Example:
git reset --hard HEAD~1

Screenshot:![alt text](image.png)

---

## 10.5 git revert
Syntax:
git revert

Purpose:
Creates new commit reversing previous commit.

Example:
git revert a1b2c3

Screenshot:![alt text](image.png)

---

## 10.6 git clean -f
Syntax:
git clean -f

Purpose:
Removes untracked files.

Example:
git clean -f

Screenshot:![alt text](image.png)

---

## 10.7 git clean -fd
Syntax:
git clean -fd

Purpose:
Removes untracked files and directories.

Example:
git clean -fd

Screenshot:![alt text](image.png)

---

# 11. Rebasing Commands

## 11.1 git rebase
Syntax:
git rebase

Purpose:
Reapplies commits on top of another branch.

Example:
git rebase main

Screenshot:![alt text](image.png)

---

## 11.2 git rebase -i
Syntax:
git rebase -i

Purpose:
Interactive rebase to edit commits.

Example:
git rebase -i HEAD~3

Screenshot:![alt text](image.png)

---

## 11.3 git rebase --continue
Syntax:
git rebase --continue

Purpose:
Continues rebase after resolving conflicts.

Example:
git rebase --continue

Screenshot:![alt text](image.png)

---

## 11.4 git rebase --abort
Syntax:
git rebase --abort

Purpose:
Cancels rebase process.

Example:
git rebase --abort

Screenshot:![alt text](image.png)

---

# 12. Cherry Pick & Patch Commands

## 12.1 git cherry-pick
Syntax:
git cherry-pick

Purpose:
Applies a commit from another branch.

Example:
git cherry-pick a1b2c3

Screenshot:![alt text](image.png)

---

## 12.2 git format-patch
Syntax:
git format-patch

Purpose:
Creates patch file from commit.

Example:
git format-patch -1 a1b2c3

Screenshot:![alt text](image.png)

---

## 12.3 git apply
Syntax:
git apply

Purpose:
Applies patch file to working directory.

Example:
git apply fix.patch

Screenshot:![alt text](image.png)

---

## 12.4 git am
Syntax:
git am

Purpose:
Applies patch as a commit.

Example:
git am patch.patch

Screenshot:![alt text](image.png)

---

# 13. Tagging Commands

## 13.1 git tag
Syntax:
git tag

Purpose:
Lists all tags.

Example:
git tag

Screenshot:![alt text](image.png)

---

## 13.2 git tag -a
Syntax:
git tag -a

Purpose:
Creates an annotated tag.

Example:
git tag -a v1.0 -m "version 1"

Screenshot:![alt text](image.png)

---

## 13.3 git tag -d
Syntax:
git tag -d

Purpose:
Deletes a tag.

Example:
git tag -d v1.0

Screenshot:![alt text](image.png)

---

## 13.4 git push origin --tags
Syntax:
git push origin --tags

Purpose:
Pushes all tags to remote repository.

Example:
git push origin --tags

Screenshot:![alt text](image.png)

---

# 14. Submodule Commands

## 14.1 git submodule add
Syntax:
git submodule add

Purpose:
Adds another repository as a submodule.

Example:
git submodule add https://github.com/user/lib.git

Screenshot:![alt text](image.png)

---

## 14.2 git submodule init
Syntax:
git submodule init

Purpose:
Initializes submodules.

Example:
git submodule init

Screenshot:![alt text](image.png)

---

## 14.3 git submodule update
Syntax:
git submodule update

Purpose:
Updates submodules.

Example:
git submodule update

Screenshot:![alt text](image.png)

---

# 15. Debugging Commands

## 15.1 git bisect
Syntax:
git bisect

Purpose:
Helps find the commit that introduced a bug.

Example:
git bisect

Screenshot:![alt text](image.png)

---

## 15.2 git bisect start
Syntax:
git bisect start

Purpose:
Starts the bisect debugging process.

Example:
git bisect start

Screenshot:![alt text](image.png)

---

## 15.3 git bisect good
Syntax:
git bisect good

Purpose:
Marks a commit as good during bisect.

Example:
git bisect good a1b2c3

Screenshot:![alt text](image.png)

---

## 15.4 git bisect bad
Syntax:
git bisect bad

Purpose:
Marks a commit as bad during bisect.

Example:
git bisect bad a1b2c3

Screenshot:![alt text](image.png)