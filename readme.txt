#intial user
git config --global user.name <name>
git config --global user.email <email>

#Create empty Git repo in specified directory
git init

#Stages all the changes for the next commit
git add .

#Commit the staged snapshot
git commit -m "message"

#Create a new connection to a remote repo.
git remote add origin <URL>

#Create and check out a new branch named <branch>.
#Drop the -b flag to checkout an existing branch
git checkout -b <branch>

#Push the branch to <remote>, along with necessary commits and objects
git push origin <branch>

#
git remote -v