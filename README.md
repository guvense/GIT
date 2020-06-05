
# GIT :rainbow: 

## Branch  :evergreen_tree:

Create branch from another branch

- *git checkout < Branch-Name-Base >*  
- *git checkout -b < Branch-Name-Sub > < Branch-Name-Base > | < Tag-Name >*  

Delete branch  
- *git branch -d < Branch-Name > | -D (force)*

Undo Last Commit 
- *git reset --soft HEAD^* 

## Cherry Pick  :cherries:
- *git cherry-pick < Commit-Id >*  
- *git cherry-pick --continue*  
- *git cherry-pick --quit*  
- *git cherry-pick --abort* 

Use "-n" flag without commit
- *git cherry-pick -n  < Commit-Id >*

## Patch  :jeans:
- *git diff > < Patch-Name >*
- *git add.*
- *git diff -p --staged >  < Patch-Name >*

## Stash  :briefcase:
- *git stash save "< Stash-Name >"*
- *git stash apply ...*
- *git stash list*
- *git stash save "..." --include-untracked*
- *git stash push -m "name" ...*
- *git stash drop ..*


## Merge Commit  :punch:
Merge master branch  
- *git checkout master*
- *git pull*
- *git checkout < Your-Branch >*
- *git merge master*

## Revert  :bike:
Revert commit   
- *git revert <commit-hash> *
  
  if conflict -> solve -> then
- *git revert --continue*
- *git push*

