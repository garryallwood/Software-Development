## Software Development Tips
[edit on GitHub](https://github.com/garryallwood/Software-Development/edit/master/index.md)

### Git Commands
[Setup SSH Keys](https://www.freecodecamp.org/news/manage-multiple-github-accounts-the-ssh-way-2dadc30ccaca/)

```bash
git status #get diff between current working tree and the local head commit
git pull #Incorporates changes from a remote repository into the current local branch.
git checkout -- <paths> #undo the local uncommitted changes in the paths
git add . #Adds all changes in working tree to the index so it is ready for commit
git commit -m "message here" #commit local changes with the message
git push origin master #Push to the master branch (the branch on Bitbucket) on origin (the Bitbucket server)
git branch -a #View all branches - local and remote"
git branch <new branch name> #Create a new branch.  Just a pointer at this stage point to the same commit as master.
git checkout <branch name> #Now you can work on the branch.  No longer working on master.
git checkout master #switch back to master
git merge <branch name> #merge branch name to master
git branch -d <branchname> #delete branch.
```
```vi
:wq #write merge message and quit - Needed after a merge
```
