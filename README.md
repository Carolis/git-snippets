# Reverting Commits

Better for using on the master branch, maintains commit history
```
git revert {commit hash}
```
---

Better for using on other branches, doesnt maintain commit history

The `Soft` param returns the files to the staging area 

The `Hard` param returns to the commit and ignores all the changed files
```
git reset --soft {commit hash}
git reset --hard {commit hash}
```

PS: It may be necessary to use the `--force` param for pushing to master with different commit history
 
--- 

