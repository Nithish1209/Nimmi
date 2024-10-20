<h1> git commands  </h1>
Basic Git Commands:
Initialize a Git Repository:

bash
Copy code
git init
Initializes a new Git repository in your project directory.

Clone a Repository:

bash
Copy code
git clone <repository_url>
Creates a copy of an existing repository from a remote server (like GitHub) to your local machine.

Check Repository Status:

bash
Copy code
git status
Shows the status of your working directory, including staged, unstaged, and untracked files.

Add Files to Staging Area:

bash
Copy code
git add <file_name>  # Add specific file
git add .            # Add all files
Stages changes you want to include in the next commit.

Commit Changes:

bash
Copy code
git commit -m "Commit message"
Saves changes in the local repository with a descriptive message.

View Commit History:

bash
Copy code
git log
Displays the commit history of the repository.

View Changes Before Committing:

bash
Copy code
git diff
Shows the differences between your working directory and the last commit.

Branching and Merging:
Create a New Branch:

bash
Copy code
git branch <branch_name>
Creates a new branch in the repository.

Switch to a Branch:

bash
Copy code
git checkout <branch_name>
Switches to the specified branch.

Create and Switch to a New Branch:

bash
Copy code
git checkout -b <branch_name>
Creates a new branch and switches to it.

Merge a Branch:

bash
Copy code
git merge <branch_name>
Merges the specified branch into the current branch.

Delete a Branch:

bash
Copy code
git branch -d <branch_name>
Deletes the specified branch locally (only if it is fully merged).

Remote Repositories:
View Remote Repositories:

bash
Copy code
git remote -v
Lists the remote repositories linked to your project.

Push Changes to Remote Repository:

bash
Copy code
git push origin <branch_name>
Uploads your local changes to the specified remote branch.

Pull Changes from Remote Repository:

bash
Copy code
git pull
Fetches changes from the remote repository and merges them into your current branch.

Add a Remote Repository:

bash
Copy code
git remote add <name> <repository_url>
Adds a new remote repository to your local Git configuration.

Undoing Changes:
Undo Changes in a File (Unstaged):

bash
Copy code
git checkout -- <file_name>
Discards changes in a file that haven’t been staged.

Unstage Files:

bash
Copy code
git reset <file_name>
Removes files from the staging area but leaves changes in the working directory.

Reset to a Specific Commit:

bash
Copy code
git reset --hard <commit_hash>
Resets your working directory and staging area to a specific commit, discarding all changes.

Stashing Changes:
Stash Changes:

bash
Copy code
git stash
Temporarily saves changes that are not ready to be committed.

Apply Stashed Changes:

bash
Copy code
git stash apply
Reapplies the latest stashed changes.

View Stash List:

bash
Copy code
git stash list
Shows a list of stashed changes.

Tagging:
Create a Tag:

bash
Copy code
git tag <tag_name>
Tags a specific commit with a version label.

Push Tags to Remote Repository:

bash
Copy code
git push origin --tags
Pushes tags to the remote repository.

Git Configuration:
Set User Name:

bash
Copy code
git config --global user.name "Your Name"
Sets your name for all repositories on your machine.

Set User Email:

bash
Copy code
git config --global user.email "your.email@example.com"
Sets your email for all repositories.
