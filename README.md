# git-restore-branch

git subcommand to restore local branch by using reflog

# Usage

show list of candidates:

```
git restore-branch
```

restore branch:

```
git restore-branch branch-name-in-reflog
```

# Installation

copy git-restore-branch somewhere in your PATH

# Limitations

it will not work properly if the previous reflog of the reflog that left the branch has been deleted

# License

MIT
