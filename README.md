# 2020-08-17-git-allenl

## Local

- `git init`: create git repository in current folder

- `git config --global user.name "Allen Linkenhoker"
- `git config --global user.email "llinkenhoker@gmail.com"

- `git status`: tells if there are files with uncommited changes
- `git add <filename>`: adds filename to staging area
- `git commit`:commits files in staging area, opens file ready to commit changes
	-`git commit -m "MESSAGE"`: allows oneline commitmessage in one step, without opening first in editor and saving

- `git config --global core.editor "nano -w"

- `git log`: shows your history
	- `git log --oneline`: shows one line version of log

- `HEAD`: tells where you are looking in history

- `git diff`: shows current state with last known state differences, prints summary of changes to screen output
	- `git diff --oneline': oneline summary of diff
	- `git diff --staged`: includes diffs from staging area

## Remotes

- `git remote add origin <URL>`: adds <URL> with the name origin
- `git push origin master`: pushes the master branch to the origin remote
- `git pull origin master': pulls the master branch from origin to local computer

- You can make changes to differat parts of a file and it will be combined automatically

