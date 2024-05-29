# Git Commands Cheat Sheet

| Command                   | Description                                                       |
|---------------------------|-------------------------------------------------------------------|
| `git log --oneline`       | Displays the commit history in a compact, one-line format.        |
| `cat .gitconfig`          | Shows the contents of the `.gitconfig` file, which contains Git configuration settings. |
| `git diff --staged`       | Shows the differences between the staging area and the last commit. |
| `git stash`               | Stashes changes in the working directory, allowing you to switch branches without committing changes. |
| `git stash pop`           | Applies the stashed changes back to the working directory and removes them from the stash list. |


## Notes
1. **.gitignore**: A `.gitignore` file can be created using a generator to specify files and directories that Git should ignore.
2. **Stash**: Stashes are not limited to the current branch; they can be applied to any branch.

## Examples and Usage

### Viewing Commit History

```bash
# Display commit history in one-line format
git log --oneline
