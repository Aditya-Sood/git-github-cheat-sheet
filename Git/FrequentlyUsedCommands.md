`git init` : Initialise a Git repository within the current working directory (of the terminal). Repository is given the same name as the directory.

`git clone` : Used to copy a remote Git repository (so all files of the current version, AND the set of all previous commits)

`git status` : Specifies files which are : i) Not being tracked, ii) Tracked and have undergone change since last commit, ii) Tracked, undergone changes since last commit and staged (ready to be committed)

`git branch` : Displays list of branches in the repository

`git branch <branchname>` : Creates a new branch at the same point as the last commit

`git add <filename>` : Used to add files which have undergone changes since the last commit, onto the staging area

`git diff --staged` : Compares state of the files in the staging area with their state in the last commit

`git reset --hard` : Empties the staging area and also reverts any changes to the WORKING DIRECTORY since the last commit

`git commit` : Bundles the staged changes into a single commit and updates the current branch head to this new commit

`git checkout <commitID>` : Checks out/Shifts to the specified commit

`git checkout <branchname>` : Checks out/Shifts to the specified branch

`git merge <branch1> <branch2> ...` :  Merges the specified branches into the currently checked out branch

`git gc` : Runs Git Garbage Collection, to remove unreachable commits

`git remote -v` : Displays list of all the remote repositories for the current repository, with URL

`git remote add <repo_label> <repo_HTTP_URL>` : Adds a new remote with specified label, pointing to the specified URL

`git push <remote_repo> <branchname>` : Pushes the local branch to update the corresponding branch in the specified remote repo

`git pull <remote_repo> <branchname>` : Pulls the branch from the specified remote repo to update the corresponding local branch