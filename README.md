# git-basics

For cloning the repo
```
git clone https://github.com/abhic137/hello-world-jenkins.git
```
Get into the cloned folder
```
cd hello-world-jenkins
git status  #gives the status of the edited files
git branch -a #gives the list of branches including the remote repo
```
For configuring GIT in a PC
```
git config --global user.name "abhic137"
git config --global user.email "abhirajbobby@gmail.com"
git config --list
```
For creating a new GIT Branch
```
git branch develop   #creates a branch named develop
git branch            # you can check the branches available
git checkout develop  # to get into the develop branch
git branch  
```
OR
```
git checkout -b ＜new-branch＞   #creates a branch and switched into it
```
For Making changes and pushing
```
sudo nano README.md   #changes are made
git status            # to see the changes made (the changes are unstaged)
git add .              # to stage the changes made
git status              # you can see the changes are staged
git commit -m "testing"  # commiting the changes with the message
git push -u origin develop  # pushing the changes into the develop repo
git branch                 
 
```
after adding the changes in develop do these steps to merge develop into master branch:
first you have to get into the master branch to merge develop into master
``` 
  git branch
  git checkout master  # get into master branch
  git branch    
  git merge develop    # for merging the develop into the master branch 
  git status
  git push --set-upstream origin master  #to push the changes in the remote repo ie github
 ```


