# Random git notes

## Rename local and remote branches

[1] - Rename local branch
```
git branch -m <new_name>
```

[2] - Push new local branch to new remote branch
```
git push origin -u <new_name>
```

[3] - Delete old remote branch
```
git push origin --delete <old_name>
```
