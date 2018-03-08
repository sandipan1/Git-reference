# Hello-World
Introductory repository created to learn git-hub

This line is added to make this branch different from the master.

Tutorial Video Link https://www.youtube.com/watch?v=HVsySz-h9r4 

## Steps to use git remotely
1. Clone a repo
   * git clone repoURL whereToClone(default=current directory)
  
2. Add files to staging area
   * git add filename      (single file)
   * git add -A            (all files)
  
3. Commit
   *  git commit -m "Commit Message"
 
4. Pull any changes made to the repository (i.e. get the latest version of the repo)
   *  git pull origin master
  
5. Push changes from staging area to master branch (or currently active branch)
   *  git push origin master 

**Before using gitignore remove cache using git rm -r --cached .**
  
## Using branches 
1.  Creating a branch
    *  git branch BranchName
   
2.  Use a particular branch
    *  git checkout BranchName
  
3.  Push branch to remote repository
    *  git push -u origin BranchName

4. Then checkout to master. Remember to pull current version of master before pushing your code
After checkout master and pull master.

5.  Merge branch to master
    * git merge BranchName

6. Finally push changes to master.

7. Delete the unnesseary branch
    * git branch -d BranchName  (removes it locally not from remote repo)
    * git push origin --delete BranchName (removes branch from remote repo)
   
## Git commands for quick reference
Remove files from staging area
  * git reset filename   (single file)
  * git reset
 
To list all branches
  * git branch -a

To list branches that have been merged
  * git branch --merged
  
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
