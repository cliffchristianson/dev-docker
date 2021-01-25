# dev-docker
This is an attempt to automate as much stuff as possible so I can just type a command 
and have a dev environment ready to go

docker setup plus scripts to:
1. Prompt user for project name, db credentials
2. Create a LEMP stack
3. Setup Laravel and Vue

Ideally you just clone the repo, set perms on the script, and run it

$git clone repo
$chmod +x dev
$dev init

To Do:
1.  Not sure how to get this to production yet, would be cool to go 
$production init 
and it could build all of the images minus all the un-needed dependencies.

2.  need to run

$sudo chown -R $USER:$USER . 

to add your user to the group or root will own the files and vscode will cry about it

3.  It would be cool if it could setup the repos for the frontend and backend

4.  Would be cool if we could integrate that static site exporter 
