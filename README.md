# Git-Learning
Some notes I've taken as I learn about Git


## Turn the current folder into a git repo
git init

## Get the status of the current folder/repo
git status

## Clone a github repo into the current folder without creating a new folder
git clone https://github.com/johnsie/SQL-Learning.git ./

## If a file has been changed it should show up in 'git status'. Add it to 'staging'
git add filename.exe

#Add all the changed files to 'staging'
git add .

#Commit the current contents of staging to the repo
git commit -m "message about what you're committing"


#Push the committed files to the origin (remote repo eg. Github)
git push origin main
(Where main is the name of the branch)

#Pull updated filed from the remote repo (eg. Github)
get pull








