1. To reset a branch and delete changes done to tracked files: `git reset --hard`. Be careful with `--hard`.
2. To reset a branch and delete all changes (including tracked and untracked files)
	```
	git reset --hard
	git clean -f -d # -f: --force, -d: also delete untracked directories, -n: for dry run
```