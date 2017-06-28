# git-tricks
Share your git tricks here.

## Branches
- `git push --delete  <branch_name>`: Delete remote branch.  see: http://stackoverflow.com/questions/2003505/delete-a-git-branch-both-locally-and-remotely
- `git checkout -b <new_branch_name>`: Create a new branch and check it out in one step
- `git stash save`: Save your local modifications to a stash and roll your working directory back to HEAD
- `git stash pop`: Remove the most recent stash from the list and apply to the working directory
- `git stash list`: Show all stashed changes
- `git stash apply <commit>`: Apply specific stashed change 
