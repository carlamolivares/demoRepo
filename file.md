# changed the name of the branch
git branch -M main

# add file to git 
git add file.md or git add . 

# commits the changes to local git repo
git commit -m "added file.md"

# make sure to add your username and email if asked
git config --global user.email "you@example.com"
git config --global user.name "Your Name"
~/.gitconfig

# make sure that the default branch for any repo is main instead of master
git config --global unit.defaultbranch main

# create and switch to new branch
git checkout -b branch1

# one more change to show new branch path

# to change branches
git checkout branchname

# cache credentials
git config --global credential.helper store (stores them permanently)