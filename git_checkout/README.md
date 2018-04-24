# git checkout
Used to switch branches or restore working tree files.

## Usage
```bash
git checkout <branch_name>
```
OR
```bash
git checkout <commit_hex_number>
```

## Example
We've already seen how to switch branches in the git stash folder. We can also use it to switch between commits. 

To view a full list commits, we want to run:
```bash
git log --oneline
```
Once we checkout to our commit directory, we can run our code and read the code, but can't shouldn't make any changes.

To go back to our `HEAD` we run: `git checkout master`.

## If you wanted to undo a commit with git checkout
After we run, the `checkout` command we are in a "detached HEAD" state. If we actually wanted to make changes, we have to create a new branch. To do this we run:
```bash
git checkout -b <branch_name>
```

