## sync running a program in paralell. Plus you have to wait for one thing to finish another thing. 
# async running a program not in pararell. So a programm is not waiting for something else to finish. 

## PRE-INITIALIZED
## create repo, open terminal > git bash, navigate to where i want my project to be, git clone repo. Then git status, git add, git commit, git push (if need right at first)

## STEPS FOR OUT BASIC APPLICATION SETUP -- Web Todo List
## when setting up repo make sure to hit ignore in the options
## set up as npm project with git ini -- this creates the package.json
## install npm install browser-sync
## better to run a module than write code ourselves. so is std to see bunch of dependencies

## npm test to run my test script. i can co in the package.json to rename it after the fact. Use a comma to do multiple scripts and single quotes to wrap them in. 
## the test script here is echo 

## npm run to show all the list of scripts i may have set up. 
## this is an async calls application
## Best Practice to use single quotes for values!! In JSON files too.
## add to scripts on package.json "start": "npm browser-sync start --server" and it will open the web page
## use cntrl c to get out of the browser-sync screen