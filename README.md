# Daehee Git

This is an example repository to play with git.

## Git cheat sheet

**create new git repo**
`git init`

**check status, e.g. which branch we're on**
`git status`

**add untracked file README.md to what will be committed**
`git add README.md`

**add all untracked files to be committed**
`git add -A`

**commit a change**
`git commit -m "message describing the change"`

**see your temotes**
`git remote -v`

**push changes to remote (push master branch to origin remote)**
`git push origin master`

**create branch readme and checkout**
`git checkout -b readme`

**add all and commit immediately**
`git commit -a -m "improved readme"`

**reset to remote branch (be careful)**
```
git checkout master # make sure that we are on master branch
git fetch origin master 
git reset --hard origin/master
```