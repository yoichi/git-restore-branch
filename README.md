# git-restore-branch

A git subcommand to restore deleted local branch by using reflog.
It can restore branches that were checked out locally in the past.

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

* Branches that have never been checked out locally cannot be restored. [git-fsck](https://git-scm.com/docs/git-fsck) or [git-resurrect](https://github.com/git/git/blob/master/contrib/git-resurrect.sh) may help.
* It will not work properly if the previous reflog of the reflog that left the branch has been deleted.

# License

MIT
