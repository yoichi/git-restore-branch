# git-restore-branch

git subcommand to restore local branch by using reflog

# Usage

To show list of candidates:

```
git restore-branch
```

The format of each line is "branch-name = commit-hash".


To restore branch:

```
git restore-branch branch-name-in-reflog
```

# Installation

Copy git-restore-branch somewhere in your PATH.

# Limitations

It will not work properly if the previous reflog of the reflog that left the branch has been deleted.

# License

MIT
