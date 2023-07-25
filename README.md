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
sudo nano README.md 
git status
git add .
git status
git commit -m "testing"
git push -u origin develop
git branch
 
```
after adding the changes in develop do these steps to merge develop into master branch:
``` 
  git branch
  git checkout master
  git branch
  git merge develop
  git status
  git push
  git checkout develop
  git status
  git push --set-upstream origin master
 ```


