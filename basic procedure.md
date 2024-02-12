# basic command lines of git i have tried

## initialize and config

git init //create a new respository
git config --global user.email "---"
git config --global user.name "name"

## something about the commit

git add .
git add readme
git commit
git commit -m "i want to make a change"
git pull main // get the latest version of the remote "main"
git push main // make the real change of the remote "main"
git log       // display all the commit records
git reflog    // reference log ,only display commits with reference

## branch

git branch          // display all the branches
git branch branch1  // create a new branch branch1
git checkout branch1// switch to branch1
git branch -M main  // create a branch,main,and set it as the main branch
git branch -d branch1// delete branch1
git merge branch1    // merge branch1 with the current branch
