# gittutorial
git and local repository

working directory

dir where we initialize our git repo using "git init" command
git gonna keep track of changes of files in the working directory

Staging Area

"git add ." used to add the files to the staging area

local repository .git file

through "git commit -m "msg" " the file is now in the local repository
so even if we messed up with the code we can revert to the
last committed version in our local repository
under version control through the "git checkout" command

timeline of savepoints/commits called master branch

git diff filename to find out the difference bw the saved version
and the last committed version of the file

git checkout filename revert to last committed version of the file 
in the local repository

github and remote repository-github

git push pushes all those commits to github
create a repository(remote) in github
copy the url of the repository
git remote add origin url
git push -u origin master

note:- here origin is the name of the remote and master is the name of the main branch
you can call it any name say  "muthus"

git remote

git ignore

Refer github/gitignore to find the common stuffs u need to add to specific projects say swift code

git init
git add .
git status
removing all of the files so staged from the staging area and add them once the gitignore is set up
making the files untracked
git rm --cached -r .
r=>recursive
. =>all of the files inside the repository

create .gitignore file
 
#used to comment

asterisk.txt 
to ignore all with txt extension
git add .
git status
git commit -m "bhdb"

# cloning a remote repository to pull it into the local repository
git clone urlOfRepository
once you cloned a project git log
to find their commits
# forking pull requests and merging
# BRANCHING
 1 2    3----4---
     3    4 /
# creating branch
git branch branchname
# to list out branches
git branch
# to switch branch 
git checkout branchname
# to merge changes to master branch
switch to master
git checkout master
git merge branchname
