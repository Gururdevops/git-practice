# Practice repository to start learning Git

## Commands used

-git init:Create a new git repository
-git status:Compare working directory,staging area, and current branch
-git add:Add changes from staging area to current branch
-git commit:Commit changes from staging area to branch

-git config:Set configuration (aka get config)
-git checkout: Check out branch(update HEAD and apply changes to working directory)
-git branch -c:Create a branch
-git merge: Merge changes from different branches
-A fat-forward merge happens when the target branch was branched from the current one,and there are no new changes to the current branch since then.
- An automatic merge happens when the two histories have diverged,but git is able to reconcile them into one set of changes.This creates a new commit on the current branch.
