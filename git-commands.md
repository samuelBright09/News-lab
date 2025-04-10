# Git   Commands Documentation
This section documents common Git commands I use during this project. This is basically for reference and learning purposes.

### Start A New Repo
git init- initialized git in local repo

### Adding all Changes
git add . - added all files

### Commiting 
git commit -m "starter code": saving changes history in local 

### Renaming Branch
git branch -M main: making sure to change branch name form master to main

### Adding a remote repo
git remote add origin https://github.com/samuelBright09/News-lab.git  : Telling git there's a remote repo I want to pull from and push to. 

### Pushing to remote repo
git push -u origin main: Pushing to the main branch on github

### Creating a New Branch
git checkout -b navigation-feature: Create a branch out of main.

### Fetching remote updates after creating a remote branch(staging)
git fetch: fetches upto date of remote repo into the local.

### Creating a new local branch and syncing it to track remote(staging)
git checkout -b staging origin/staging

### Creating new branch out of staging
checkout -b headline-section 

### Checking out branches available
git branch


