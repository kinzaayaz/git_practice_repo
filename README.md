`git init` → Initialize a new Git repository in the current folder.
`git ls` → Lists files and folders in the current directory.
`git ls` -la → Lists files including hidden ones (like .git).
`git add (filename)` → Stage a specific file.
`git add *` → Stage all files.
`git status`: to check for any chnge in repo.
`git commit -m (message)` → Commit staged changes with a message.
`git log` → View the commit history. (author name,date,time,comment, all details)
`git diff` → to see differences in current version and previous version.
`git branch` → Check branches.

Working with git show:
`git show` → Show details of the latest commit.
`git show` (T no) → Show a specific version of a file in terminal (for small codes).

Working with git checkouts:
`git checkout` (T no) – filepath or * → Check a specific file without terminal.
`git checkout branchname – filepath or *` → Go back to the latest version of code/file.

Working with git restore:
`git restore filename or .` → Restore the original version of a file if changes were made by mistake.
`git restore --staged . (then) git restore .` → Revert staged changes after git add.
`git restore –worktree .` → Remove extra changes made after staging, without affecting the staged desired code.

Working with git reset:
`git reset –hard HEAD ^ `: is used to go back one commit and erase changes permanently.

Working with git log:
`git log -p -2`: last 2 commit with diff
`git log –stat` : for summary of chnges
`git log --pretty=oneline`: for commits in one line
`git log -S function name`: for checking detail of specific function
`git log --grep`:for commit msgs
`git log --since`
`git log --until`
`git log --author`

working with git push:
`git remote add origin (link of repo)`
`git branch -M main`
`git push -u origin main`
`git push` :push files from local to remote repo
`git remote` : to check our repo is linked with remote repo
`git remote -v` : not only check for repo is linked or not,but Also provide links of repo as well 
`git pull` : to pull/fetch latest files from remote repo to local repo

working with git clone:
`git clone (repo link)` : to clone others repo on ur sys locally

working with branching and merging:
`git branch branchname` : for creating new branch
`git checkout branchname` : for change branch
`git merge branchname` : 1st u have to checkout to main branch and then merge desired branch to mainn branch

working with git forking and pull request:


working with git ignore:

working with git clean:
`git clean -n` : list untrack files 
`git clean -f` : permanently remove untrack files
