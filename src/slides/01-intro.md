# Git Reset

---

## The working directory

- The working directory is in sync with the local file system
and it is representative of the immediate changes made to
content in files and directories.

- When we make changes to a file those changes are now part
of the working directory. If we run `git status` the modified
file will be displayed in red.

---

## The staging index

The staging index tracks the changes that has been staged by
running `git add` and will be stored in the next commit.
The staging index changes can be seen in green when running
`git status`. We also understand it as a preview of the next
commit.

---

## The commit history

The commit history is a list of snapshots that can be appended
with the `git commit` command. We can see the state of the
commit history by running `git Log`.
