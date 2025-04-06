# Git commands

## Commit
```bash
git commit -m "message"
```

## Push
```bash
git push origin
```
if we rewrite old commits
```bash
git push --force
```

## Reset 
### (reset 4 last commits)
--soft (returns commits changes in vs code staged area)
```bash
git reset --soft HEAD~4
```

## Pull
```bash
git pull
```

## Checkout
```bash
git checkout branch-name
```

## Rebase
takes changes from branch named branch-name 
```bash
git rebase branch-name
```