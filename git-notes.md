<

<!-- Write your notes here -->

### 1. What is a VCS and why is it needed?

Version Control software (VCS) helps in tracking and managing the changes that occurs while developing the software.

Needs:
Easy to keep track of version.
Compare earlier versions of the code to help fix the mistake.
Developers can collaborate.

### 2.Whats is the difference between a forked repo and a cloned repo?

Forking a repo makes a copy of entire project/folder available on the remote repo i.e on github.
Cloning a repo makes a copy enture project/older available on our local system.

### 3.Why do we create branches?

Allows the developers to isloate their work from others and later merge it .
Keeps the code in the main branch clean and up-to-date.

### 4.What is the use of fork if we can create branches?

Forking creates a copy of an existing process which is independent of original repo even if the repo is deleted in future we will have a copy of it .All these are not possible in branch

### 5. What is the difference between staged and unstaged files?
Ans Staged files are those which are present in the staging area. These are the files which will be commited to the repository.
Unstaged files are those files which are not present in staging area that is git hasn't recorded it.

### 6. Difference between tracked and untracked files?
Ans Tracked files are those files which git has concern with.
Untracked files are those files which git doesnt know about.

### 7. How is git pull different from git fetch?
Ans Git pull is used when we wan to pull in any changes that have been made in the remote repo. Git fetch only brings the files to your system but doesnt merge it.

### 8. Why do we raise PRs?
Ans PRs are pull request.When we ahve made our changes and pushed it back into our repo. Click on Compare and pull request button or if it is not present then we can click on create new pull request and fill the required information that which is the base repo and what branch we want to pull.
### 9. What are the best practices for naming branches and writing commits?
Ans We should always write commits in key-value pair where key will tell what feature or change we have done  and while name branches we can use the word fix and then give name to branches i.e fix/ branch name

### 10. Write git commands to create a new branch and switch to a different branch.
  Ans git branch <branch name> and git checkout<new branch name>


### 11. Can we add a new remote to our repo, if yes, what is the command?
Ans   Yes,we can and the command is :-
    git add remote add origin <URLfromgithub>


### 12.Write git commands to view status of changes and the commit history.
Ans  git status and git log


### 13. List the basic linux commands that you learnt and write their uses.
Ans cd:-to change directory
    ls:-list files
    mkdir:-to make a directory
    touch :-to make file
    :wq - to save and exit from vim 
  
### 14. How to sync your changes in local repository to remote one?
Ans We can use pull command.
  


