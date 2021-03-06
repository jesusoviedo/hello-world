--------------
Commands used
=============

**View version**

git --version

**Turn Git on for a folder**

git init

**Check status of changes to a repository**

git status

**Add a file's changes to be committed**

git add FILENAME

**To add all files changes**

git add .

**To commit the changes you've added with a short message describing the changes**

git commit -m "your commit message"

**View changes to files**

git diff

**Add config global**

git config --global user.name "Your Name"

git config --global user.name

git config --global user.email "youremail@example.com"

git config --global user.email

git config --global user.username <USerNamE>

git config --global user.username

**Add remote connections**

git remote add REMOTENAME URL

REMOTENAME:
- *origin*
- *upstream*

**Set a URL to a remote**

git remote set-url REMOTENAME URL

**View remote addresses**

git remote -v

**Push changes**

git push REMOTENAME BRANCH

**Pull in changes**

git pull REMOTENAME BRANCHNAME

**See changes to the remote before you pull in**

git fetch --dry-run

**Clone repository**

git clone URLFROMGITHUB

**Verify what branch you're working on**

git status

**Create a new branch**

git branch BRANCHNAME

**You can create and switch to a branch in one line**

git checkout -b BRANCHNAME

**Move onto a branch**

git checkout BRANCHNAME

**List the branches**

git branch

**Rename a branch you're currently on**

git branch -m NEWBRANCHNAME

**Merge a branch into current branch**

git merge BRANCHNAME

**Delete a local branch**

git branch -d BRANCHNAME

**Delete a remote branch**

git push REMOTENAME --delete BRANCHNAME