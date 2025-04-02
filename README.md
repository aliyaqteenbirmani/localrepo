# This is my Local repo

# Branches Commands 
    git branch  --------> to check branch<br>
    git branch -M main --------> to rename branch<br>
    git checkout <other branch name> --------> to navigate to other branch<br>
    git checkout -b <new branch name> --------> to create new branch<br>
    git branch -d <branch name> ---------> to delete branch<br>
    <br>git diff <branch name to merge with> --------> to compare commits, branches, files & more<br>
    git merge <branch name to merge with> -------> to merge 2 branches<br>
    <br> 
# Undoing Changes

case 1: staged changes
    git reset <file name> -------> reset that file
    git reset ------> reset all files

case 2: commited changes (for one commit)
    git reset HEAD~1 --------> reset latest commit 

case 3: commited changes (for many commits)
    git reset <commit hash> --------> uncommit the many commit using hash code
    git reset --hard <commit hash> --------> make changes in vs code too unlike in git


