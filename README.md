# learninGit

Configurando git
// this is the config for the whole machine
git --version
git config --config list
git config --global user.name ""
git config --global user.email ""

// configuration for a specific folder
git config --list
git config user.name ""
git config user.email ""


// check what user name is using
git config user.name

//starts a repository
git init
git status
git commit -m ""
git diff

git remote add origin <http url>

// checkout if theres a remote configured
git remote -v

//idk
git branch --set-upstream-to=origin/main

//pulls the online repo
git pull –allow-unreleated histories

// push local repo to online
git push

// list all the branches of a repo
git branch --list

//change working branch
git checkout <branch name>

//create branch
git checkout -b <branch name>

//delete branch on local repo
git branch -d <branch name>
//delete branch on online repo
git push origin :<branch name>

//push a locally created branch into origin (online repo)
gir push --set-upstream origin <branch name>

//marge a branch into main
git checkout main
git merge <branch name>

//gets branches created in origin
git fetch origin

//shows history of commits
git log

//reverts to old commit
git revert <id commit>

//not recommended
git revert HEAD~3

git revert HEAD~3..HEAD~1

GitHub
gh auth
gh repo 
Workflow
cd c:/dev
mkdir <proyect name>
cd <proyect name>
git init
git add .
git commit -m ""
git remote add origin <http url>
git branch –set-ups tream-to=origin/main
git pull –allow-unreleated histories
git push



