# Essential GIT Commands

Below is a list of fundamental Git commands that are crucial for developers working with version control. Understanding and using these commands effectively will help you manage your codebase efficiently.

1. **`git init`**:
   - Initializes a new Git repository in the current directory. It creates a `.git` subdirectory with necessary files and folders to start tracking changes.

2. **`git clone <repository>`**:
   - Creates a copy of an existing Git repository from a remote location. It clones the repository and its entire history into a new directory on your local machine.

3. **`git branch`**:
   - Lists all branches in your repository. You can also create new branches using `git branch <branch_name>` or delete branches with this command.

4. **`git checkout <branch>`**:
   - Switches to a different branch. It’s commonly used to work on specific features or bug fixes. With Git 2.23 and later, `git switch` is recommended for branch switching.

5. **`git remote`**:
   - Allows you to manage remote repositories. You can add, remove, or view remote repositories with this command.

6. **`git stash`**:
   - Temporarily saves your changes without committing them. This is useful when you need to switch branches but want to keep your unfinished work safe.

7. **`git switch <branch>`**:
   - A simpler command introduced to streamline branch switching compared to `git checkout`. It's designed to improve user experience.

8. **`git merge <branch>`**:
   - Combines changes from one branch into another. This command merges changes from the specified branch into the current branch.

9. **`git push <remote> <branch>`**:
   - Uploads local commits to a remote repository, updating the remote branch with your changes.

10. **`git rm <file>`**:
    - Removes files from the working directory and the staging area. This command stages the removal of files for the next commit.

11. **`git pull`**:
    - Fetches changes from a remote repository and merges them into your local branch. It’s a combination of `git fetch` and `git merge`.

12. **`git status`**:
    - Shows the status of changes in your working directory. It provides information about untracked, modified, and staged files.

13. **`git diff`**:
    - Displays differences between commits, or between the working directory and the index. It helps you review changes before committing.

14. **`git commit -m "message"`**:
    - Saves your staged changes to the local repository by creating a new commit with a descriptive message.

15. **`git log`**:
    - Displays a list of commits on the current branch. It shows commit messages, authors, and dates, providing a history of changes.

16. **`git add <file>`**:
    - Moves changes from your working directory to the staging area, so they are included in the next commit. Use `git add .` to stage all changes.

---

#Git #GitCommands
