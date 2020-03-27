# GIT

## Branch

- Create branch from another branch

git checkout < Branch-Name-Base >  
git checkout -b < Branch-Name-Sub > < Branch-Name-Base > | < Tag-Name >

- Delete branch
git branch -d < Branch-Name > | -D (force)

- Undo Last Commit 
git reset --soft HEAD^

## Cherry Pick
git cherry-pick < Commit-Id >
git cherry-pick --continue
git cherry-pick --quit
git cherry-pick --abort

Use "-n" flag without commit
git cherry-pick -n  < Commit-Id >

## Patch
git diff > < Patch-Name >
git add.
git diff -p --staged >  < Patch-Name >

## Stash
git stash save "< Stash-Name >"
git stash apply ...
git stash list
git stash save "..." --include-untracked
git stash push -m "name" ...
git stash drop ..

-Delete untracked
- all
git clean -f -d
