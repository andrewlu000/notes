# Useful commands:

### cherry-pick
Applying last commit from one branch to another branch
```bash
git checkout A
git commit -m "Fixed bug x"
git checkout B
git cherry-pick A
```

### reversing the previous commit and erasing
```bash
git reset --hard HEAD~1
```

### reversing the previous commit but keeping changes
```bash
git reset --soft HEAD~1
```

### dealing with stashing
#### clear the top stash on the stack
```bash
git stash drop
```
#### clear specific stash on stack
```bash
git stash drop stash@{n}
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
