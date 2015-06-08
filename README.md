# git-ls

List contents of the current directory, marked according to git status.

![git-ls example](https://github.com/stedolan/git-ls/raw/master/screenshot.png)

Staged files are green and marked with `^`.

Changed but unstaged files are red, marked with `*`.

Untracked files are yellow, marked with `?`.

Directories are blue, but if they contain staged, changed or untracked files they're marked accordingly.

## Installing

Run this:

    git config --global alias.ls '!/path/to/git-ls'

Then, you can run `git ls` from inside any git repo.

## About

It's written in Python (runs as either Python2 or Python3). Should
work on anything vaguely Unixy. MIT licensed.
