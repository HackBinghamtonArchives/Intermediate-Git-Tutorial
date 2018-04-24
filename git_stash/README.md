# git stash

Temporarily stashes the changes you've made in your working directory, so you can work on something else

## Usage
```bash
git stash
```
## More utilities 

### Bring back your dirty directory
```bash
git stash pop
```
Popping your stash, brings back the dirty working directory.
You can run `git stash list`, to see the stash(es).

To give the stash a meaningful label you can run:
```bash
git stash save <message>
```
So when we call `git stash list`, it'll appear with the "message" label.
### Managing multiple stashes

Let's say that you have multiple stashes and you would only like to pop a specific one. You would run:
```bash
git stash pop stash@{#}
```
The `#` is the number at which stash you would like to pop.

If you wanted to pop a stash to a different branch, you run:
```bash
git stash branch <branch_name> stash@{#}
```

To switch to master branch, run:
```bash
git checkout master
```

To merge your master branch and the new branch you've just created, run:
```bash
git merge <branch_name> 
```

### To get rid of stash(es)
To get rid of a particular stash, run:
```bash
git stash drop stash@{#}
```

To get rid of all stashes, run:
```bash
git stash clear
```
