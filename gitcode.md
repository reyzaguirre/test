# create a new brach and switches to the new branch
$ git checkout -b <branch_name>


# to check the branches you have
$ git branch

# to switch between branches
$ git switch <branch_name>

# pull the most recent version of the repo (where main is the main branch)
$ git pull origin main

# add your changes (staged)
$ git add --all

# commit the changes
$ git commit -m "your text"

# check the status
$ git status

# push the changes if you are in a branch
$ git push --set-upstream origin <branch_name>

# push changes if you are the main branch
$ git push -u origin main

# delete branch
$ git branch -d <branch_name>

