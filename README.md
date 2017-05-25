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
#### **Updates the index using the current content found in the working tree, to prepare the content staged for the next commit**
#####Add all files in this directory:
```
git add .
```
##### Add specyfic file: 
```
git add <filename>
```
**Stores the current contents of the index in a new commit along with a log message from the user describing the changes:**
```
git commit -m 'message'
```
**Set adress where files after commiting will be send and from where they will be pulled**
```
git remote add origin 'https://github.com/qbabor4/tryGit.git'
```
**Change remote directory**
```
git remote set-url origin git://new.url.here
```
**See remote options**
```
git remote -v
```
**Send comited files to the adress given in remote**
```
git push origin master
```
**Get files from github in adress given in remote**
```
git pull
```

**With Allowing unrelated histories**
```
git pull --allow-unrelated-histories
```

**See changes on pulled files**
```
git diff HEAD
```
**Remove file from added files**
```
git reset <filename>
```
**Go back to the last commit for specyfic file**
```
git checkout -- <filename>
```
**Create branch**
```
git branch <branchname>
```
**Switch between branches**
```
git checkout <branchname>
```
**See all branches**
```
git branch
```
**Merge changes from current branch with specified branch**
```
git merge <branchname>
```
**Delete branch**
```
git branch -d <branchname>
```
// fetch merge 
// branch
