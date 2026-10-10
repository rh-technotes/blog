# Useful Git Commands

## Undo the last commit but keep changes

```bash
git reset --soft HEAD~1
```

## See the history of a single file

```bash
git log -p -- path/to/file
```

!!! tip
    Use `git reflog` to recover from almost any mistake.
