# git-restore-branch

git subcommand to restore local branch by using reflog

# Usage

## Show list of candidates

```
git restore-branch
```

The format of each line is "branch-name = commit-hash".


## Restore branch

```
git restore-branch branch-name
```

# Installation

Copy git-restore-branch somewhere in your PATH.

# Limitations

It will not work properly if the previous reflog of the reflog that left the branch has been deleted.

# License

MIT
