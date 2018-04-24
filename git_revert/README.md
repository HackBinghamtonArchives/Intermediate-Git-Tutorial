# git revert

We can revert to some existing commit.

## Usage
```bash
git revert <commit_hex>
```

## Example
Instead of creating a new branch like we did with the `checkout` command, we can just use `revert`.

If we want to go back to the latest commit we can run:
```bash
git revert HEAD
```
This will go back to the latest commit (This doesn't work if the latest commit is a merge ¯\_(ツ)_/¯).

You can also specify which commit you want to revert back to as shown above.
