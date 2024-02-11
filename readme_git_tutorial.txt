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
 to create a branch use git branch < new branch name> < source branch name >
then change the branch to go to the new branch using  git checkout <branchname>  command
later make changes in this branch.
to merge to any other branch go to the branch where you want to merge and use
git merge <main branch>  <branch to be merged>

