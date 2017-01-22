## Useful commands for git 

**Makes your current folder a git repository folder**
```
git init
```
**Define the author name and email to be used for all commits in the current repository. Typically, you’ll want to use the --global flag to set configuration options for the current user**
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
#####Add all files in this directory:
```
git add .
```
#####Add specyfic file: 
```
git add filename
```
**Stores the current contents of the index in a new commit along with a log message from the user describing the changes:**
```
git commit -m 'message'
```
**Set adress where files after commiting will be send and from where they will be pulled**
```
git remote add origin 'https://github.com/qbabor4/tryGit.git'
```
**See remote options**
```
git remote -v
```

//zrobic pull do innego repo
// fetch merge 
// branch
