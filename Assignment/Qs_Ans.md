Command to initialize git repository

- `git init`: Initializes a new Git repository in the current directory.

Command to clone remote repository

- `git clone <repo_source>`: Clones a remote repository into a new directory.

Command to stage all changes

- `git add .`: Adds all changes in the current directory to the staging area.

Command to view state of working directory and staging area

- `git status`: Displays the current state of the working directory and staging area.

Command to create new branch

- `git branch <branch_name>`: Creates a new branch with the specified name.

Command to change branch

- `git checkout <branch_name>`: Switches to the specified branch.

Command to clean staging area

- `git reset`: Clears the staging area, unstaging files while keeping changes.

Command to get commits and changes from remote branch (It should not merge changes in current branch).

- `git fetch origin <branch_name>`: Fetches commits and changes from the remote branch without merging.

Command to get commits and changes from remote branch (It should merge changes in current branch).

- `git pull origin <branch_name>`: Fetches and merges commits from the remote branch into the current branch.

Command to cherry pick commit which SHA => 092018283103810930

- `git cherry-pick 092018283103810930`: Picks a specific commit by its SHA and applies it to the current branch.

Command to push branch

- `git push origin <branch_name>`: Pushes the specified branch to the remote repository.

Command to delete remote branch

- `git push origin -d <branch_name>`: Deletes the specified branch from the remote repository.

Command to do iterative rebase

- `git rebase --continue`: Continues the process of an ongoing rebase after resolving conflicts.
