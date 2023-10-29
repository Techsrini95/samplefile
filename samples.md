this is to check the git branches 

git init:

Initializes a new Git repository in the current directory.
git clone <repository_url>:

Creates a copy of a remote Git repository on your local machine.
git add <file>:

Stages changes in a file for the next commit.
git add . or git add --all:

Stages all changes in the working directory for the next commit.
git commit -m "message":

Records the staged changes into the Git history with a descriptive message.
git status:

Shows the current status of your working directory, including untracked files and changes to be committed.
git diff:

Displays the differences between the working directory and the last commit.
git log:

Shows a log of all commits in the current branch.
git branch:

Lists all local branches in the repository and indicates the currently active branch.
git branch <branch_name>:

Creates a new branch with the specified name.
git checkout <branch_name>:

Switches to an existing branch.
git checkout -b <new_branch_name>:

Creates a new branch and switches to it in one step.
git merge <branch_name>:

Merges changes from the specified branch into the current branch.
git pull:

Fetches changes from a remote repository and merges them into the current branch.
git push:

Pushes local changes to a remote repository.
git remote -v:

Lists all remote repositories associated with the current repository.
git fetch:

Downloads objects and references from a remote repository without merging them.
git reset <commit>:

Moves the HEAD and current branch pointer to a specific commit.
git stash:

Temporarily saves changes that are not ready to be committed.
git tag <tag_name>:

Creates a new tag to mark a specific commit for future reference.
git blame <file>:

Shows who last modified each line in a file and in which commit.
git rebase <branch_name>:

Reapplies commits from one branch onto another, often used to maintain a linear commit history.
git cherry-pick <commit>:

Applies a specific commit from one branch to another.
git remote add <name> <url>:

Adds a new remote repository with a given name and URL.
git remote remove <name>:

Removes a remote repository from the list of remotes.