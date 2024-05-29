# Git Commands Cheat Sheet

| Command                   | Description                                                       |
|---------------------------|-------------------------------------------------------------------|
| `git log --oneline`       | Displays the commit history in a compact, one-line format.        |
| `cat .gitconfig`          | Shows the contents of the `.gitconfig` file, which contains Git configuration settings. |
| `git diff --staged`       | Shows the differences between the staging area and the last commit. |
| `git stash`               | Stashes changes in the working directory, allowing you to switch branches without committing changes. |
| `git stash pop`           | Applies the stashed changes back to the working directory and removes them from the stash list. |
| `git stash list`          | Lists all stashed changes.                                        |
| `git reflog`              | Displays a log of all Git references, including commits and other actions, such as checking out branches or reverting changes. |
| `git rebase`              | Reapplies commits on top of another base, commonly used to integrate changes from one branch into another or to maintain a clean commit history. |
| `git remote -v`           | Displays the URLs of the remote repositories associated with the local repository, along with their corresponding names. |


## Notes
1. **.gitignore**: A `.gitignore` file can be created using a generator to specify files and directories that Git should ignore.
2. **Stash**: Stashes are not limited to the current branch; they can be applied to any branch.
3. **rebase**: Never ever run this command on the main/master branch.
4. 

## Examples and Usage


### Viewing Commit History

```bash
# Display commit history in one-line format
git log --oneline
