# praneeth-demo
This is my first repository
<br>
Author-TulasiPraneeth
Downloading git:
https://git-scm.com/downloads
on desktop
main
override

STEPS:(starting from git clone to pushing to git)
1)create repository
2)clone using git clone "httpslink"
3)add using git add .
4)commit using git commit -m "somemessage"
5)git push origin main

controls:
---------
git --version-->display the version
ls-->displays all folders(list files)
clear-->clears the terminal
pwd-->working directory

Configuring Git:
-->Telling git with which account we are mading changes
git config --global user.name "tulasipraneeth"
git config --global user.email "mukkatulasipraneeth@gmail.com"
git config --list

Open the VSCode and set terminal to gitbash
GIT BASIC COMMANDS:
-------------------
1)clone-->to clone a git repository on our local machine
git clone <--link-->
paste https link from the repository





Change directory to the repository(folder) name in vscode-->cd praneeth-demo(repo name)
ls -->to list files
ls -a--> to list all hidden files

2)status-->displays the status of the code
 git status 

 status-->4 types
  2.1)untracked-->new files that git doesnt yet track
  2.2)modified-->changed
  2.3)staged-->file is ready to be commited
  2.4)unmodified-->unchanged

ADD(engagement) & COMMIT(wedding)
to make untracked files & modified files updated to github
step 1-->add(to make it known to git)
step2-->commit(to remain unchanged)

add--> adds new or chaned files in your working directory to the git staging area
  git add <--filename-->

commit-->it is the record of change
  git commit -m "somemessage"

3)push-->to add local repo content to git(remote) repo content
   git push origin main

REVERSE APPROACH:(starting from local repo to push into git repo)
it can be done with the help of init command


INIT
check ls-a if no git available then do the follow
1)git init
2)git remote add <-origin link->
3)git remote -v (to verify remote)
4)git branch(to check branch)
5)git branch -M main(to rename branch)
6)git push origin main

to just use git push all time
1)git push -u origin main
next time u can use only git push

BRANCH COMMANDS:
----------------
 git branch  (to check branch)
 git branch -M main (to rename branch)
 git checkout <--branch name-> (to navigate)
 git checkout -b <new branch name> (to create branch)
 git branch -d <--branch name--> (to delete branch)

Merging code 

Way1
git diff <-branch name-> (to compare commits,branches,files & more)

git merge <--branchname--> (to merge 2 branches)

Way2
Create a PR(pull requests)

pull request-->It tells you others about changes you've pushed to a bracnch in a repsoitory on Github

pull command:
git pull origin main
used to fetch and download content from a remote repo and immediately update the local repo to match that content

Undoing Changes
Case 1: staged changes
git reset <file name>
git reset

Case 2: committed changes (for one commit)
git reset HEAD~1

Case 3: committed changes (for many commits)
git reset <commit hash>
git reset --hard <commit hash>

git log -->to view commits