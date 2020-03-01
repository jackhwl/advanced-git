git clone
git init
git checkout branch
git add .
git reset HEAD file
git reset HEAD .
git commit -m

1. setup env
git config --global

2. commit
md test
cd test
git status
git init
git status
22

git add .
git commit 

git branch new_branch

3. working area, staging area (cache index), repo
working area: untracked files, not handled by git
staging area: files are going to be part fo the next commit
                how git knows what will change between the current commit and the next commit.
                git add -p


repository: contains all of your commits

A branch is just a pointer to a particular commit
the pointer of the current branch changes as new commits are made

HEAD is how git knows what branch you're currently on, and what the next parent will be

git checkout -b new_branch
git checkout branch

git tag my-first-commit
