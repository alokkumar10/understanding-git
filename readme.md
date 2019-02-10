## what is git and its uses
* its a distributed version control
* use to coordinate between multiple developer
* it is an example of Verion Management System (VMS)
* you can revert back to and time to previous change
* you can work without internet excess (not everytime ;)
* keep track of your code history

## Basic Commands 
* git inti // intialize local repo
* git add // add files to the index
* git status // check the working tree
* git commit // commit changes in index
* git push // push your changes to remote repo
* git clone // copy repo into your local machine
* git config --global user.email "singhp154154@gmail.com" // add your detail to the project
* git config --global user.name "yamraj21"  // add your detail to the project
* git add // add a file to the project
* git status // status of your staging area
* git rm --cached <file>  // to remove file from staging area
* git add * // add all the file to the staging area
* git add *.html // add all the html file to staging area
* git commit // to push your file in git server :)
* git commit -m this is my helpful message // this will save us from vim editor :( but it saves time :)
* touch .gitignore // git ignore will contain the file which you dont want to add just add the file<file_name> or folder name </dir_name>
* git branch branch_name // create a new branch now master is safe :P
* git checkout branch_name // to switch between branch main branch name is master
* git merge branch -m this is your precuous message //wohoo you have made your task now it is ready to merge with your current -tech- merge your branch_name to current branch
### workign with remote location
* git remote // show the remote repo location
* git remote add origin https://github.com/yamraj21/understanding-git.git // to add a remote repo
* git remote // will list out the origin you are workign
* git clone <repo_url> // take an online git repo to your local machine
* git pull // will make a change on your local machine made by other developer on your rempo
