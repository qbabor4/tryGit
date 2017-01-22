## Useful commands for git 

**Make your current folder a git repository folder:**
```
git init
```
**Define the author name and email to be used for all commits in the current repository. Typically, you’ll want to use the --global flag to set configuration options for the current user:**
```
git config --global user.name jakub
git config --global user.email qbabor4444@gmail.com
```
**See username and email of current user**
```
git config --list
```
**Displays paths that have differences between the index file and the current HEAD commit, paths that have differences between the working tree and the index file, and paths in the working tree that are not tracked by Git**
```
git status
```	
####**Updates the index using the current content found in the working tree, to prepare the content staged for the next commit**
#####Add all files in this directory
```
git add .
```
#####Add specyfic file 
```
git add filename
```

git commit -m 'message'

git remote add origin 'https://github.com/qbabor4/tryGit.git'

git config --global user.name jakub
git config --global user.email qbabor4444@gmail.com

git remote -v
//zrobic pull do innego repo
// fetch merge 
// branch
