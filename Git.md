# Useful commands:

### cherry-pick
Applying last commit from one branch to another branch
```bash
git checkout A
git commit -m "Fixed bug x"
git checkout B
git cherry-pick A
```

### shortcuts
#### git add
`ga .`
#### git commit
`gc -m "..."`
#### git push
`gp`

### autostash
```bash
git pull --autostash
```
- supremely useful for when you have already done edits on your repo but you forgot to pull
- automatically stashes your changes

### pull submodules with main repo
```
git clone --recurse-submodules (repo)
```
