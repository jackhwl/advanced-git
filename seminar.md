git clone
git init
git checkout branch
git add .
git reset HEAD file
git reset HEAD .
git commit -m

git commit -a --allow-empty-message -m ""

1. setup env
git config --global user.name
git config --global user.email
git config --global core.editor
git config --global core.editor "'C:\Program Files (x86)\Notepad++\notepad++.exe' -multiInst -notabbar -nosession -noPlugin"

2. commit
md test
cd test
git status
git init
git status

git add .
git commit 

git branch new_branch

3. working area, staging area (cache index), repo
working area: untracked files, not handled by git
staging area: files are going to be part for the next commit
                how git knows what will change between the current commit and the next commit.
                git add -p


repository: contains all of your commits

A branch is just a pointer to a particular commit
the pointer of the current branch changes as new commits are made

HEAD is how git knows what branch you're currently on, and what the next parent will be

git checkout -b new_branch
git checkout branch

git tag my-first-commit

git checkout -- file



# Branch
Branching in Git is very powerful but can be overwhelming at the same time. 
Git branches are effectively a pointer to a snapshot of your changes.

Branching is a core concept in Git. There's only one rule: anything in the master branch is always deployable.
git branch -l

create branch:
git branch newBranchName
git checkout -b newBranchName
