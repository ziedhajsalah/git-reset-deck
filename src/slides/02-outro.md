## Git reset command

Git reset command will move the both the `HEAD` and the branch refs to the specified commit.
This command has three options that can be passed as arguments: `--soft`, `--mixed` and `--hard`. The default option is `--mixed`.

---

### `--hard`

It makes the commit history pointes to the specified commit and resets the staging index and working directory to match the staging index and working directory of the specified commit. Any pending changes to the staging index and the working directory gets reset to match the state of the commit tree. This means any work that was hanging out in the staging index and working directory will be lost.
We can't undo any data loss.

---

### `--mixed` (default)

It makes the commit history pointes to the specified commit, resets the staging index to the state of the specified commit and any changes that has been undone from the staging index are moved  to  the working directory.

---

### `--soft`

It only updates the commit history and leaves the staging index and the working directory untouched. The changes contained in the deleted commits are now in the staging index.
