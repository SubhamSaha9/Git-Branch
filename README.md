# About git and Branch

# Basic commands

1: `git branch` (to check branch) </br>
2: `git branch -M <new name>` (to rename branch)</br>
3: `git checkout <branch name>` (to navigate)</br>
4: `git checkout -b <branch name>` (to create new branch)</br>
5: `git branch -d <branch name>` (to delete branch)</br>

# Merging branches

1: `git diff <branch name>` (to compare commits, branches, files & more)</br>
2: `git merge <branch name>` (to merge two branches)</br> &ensp;or </br> &ensp; create pull request</br>

# pull requests

`git pull origin main` (to download remote repo to local and update as in local as remote)</br>

# fixing issue

case 1: staged(add) changes</br>
&ensp; 1: `git reset <file name>` (to unstage that particular file)</br>
&ensp; 2: `git reset` (to unstage all the last added file)</br>
case 2: commited changes(for one change)</br>
&ensp; 1: `git reset HEAD~1` (uncommit and unstage the last commit)</br>
case 3: commited changes(for many changes)</br>
&ensp; 1: `git reset <commit hash>` (run `git log` to get all the commits and there we will get `commit hash`)</br>
&ensp; 2: `git reset --hard <commit hash>` (remove the changes in files after that commit)
