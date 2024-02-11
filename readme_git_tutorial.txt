git init
to initiate git repo, inside the directory run above
create your program/package/software in this directory
git status    : use this to check current status of the repo
 git add test.py readme_git_tutorial.txt 
>> readme_git_tutorial.txt
git config --global --edit : to edit the global config for git
git commit --amend --reset-author : to update the author for git 
 if you dont want to track a type of file eg a particular extension it is to be added in a .gitignore file 
 GIT Branching
=================================================
git branch  ## list the branches and current branche, marked with *
git branch test-branch main  ## 
git push -u origin test-branch   ## in case aother branch needs to be pushed to github
