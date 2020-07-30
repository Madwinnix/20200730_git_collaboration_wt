# 20200730_git_collaboration_wt
Git collaboration notes -> NEW CHANGE

- git clone <url> [target]   : downloads a repository from specified url to local computer.
                               - don't nest repositories inside each other
                               - just like git init => only to be done once per repo

- git branch <branch name>   : create a new branch based on current HEAD
- git branch -a              : list all brnaches in local repository
 
- git switch <branch name>   : switch to specified branch
  git switch -c <branch name>: create an new branch and switch to it
  git checkout <branch name> : same as git switch

- git log --oneline --all --graph : shows decorated log information

- git fetch --prune          : clean local history and remove references from remote which are still in local repository

- git branch -d <branch name>: removes branch from local repository

- pull request               : 

