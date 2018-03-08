# Hello-World
Introductory repository created to learn git-hub

This line is added to make this branch different from the master.

Tutorial Video Link https://www.youtube.com/watch?v=HVsySz-h9r4 

**Steps to use git remotely**
Clone a repo
  * git clone repoURL whereToClone(default=current directory)
  
 Add files to staging area
  * git add filename      (single file)
  * git add -A            (all files)
  
 Remove files from staging area
  *  git reset filename   (single file)
  *  git reset
 
 Commit
  *  git commit -m "Commit Message"
 
 To list all branches
  *  git branch -a
 
 Pull any changes made to the repository (i.e. get the latest version of the repo)
  *  git pull origin master
  
 Push changes from staging area to master branch (or currently active branch)
  *  git push origin master
  
**Git commands for quick reference**
To see changes made that are not yet commited
  * git diff
  
To see status of uncommited parts
  * git status

To see log of commits
  * git log

View information about remote repository
  * git remote -v
  
To set username email
 * git config --global user.name "MyGitName"
 * git config --global user.email "MyGitemail"
 
To check name and email settings
 * git config --list
 
To store credentials 
 * git config --global credential.helper store
