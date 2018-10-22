- GitHub is a web-service based on Git, used for sharing code and collaborating with others.

- GitHub is used to store remote copies of local project repositories, which are accessible to others (hence the sharing aspect). Branches are 'pushed' to the remote repo from the local repo (to update the remote copy of the branch) and 'pulled' from the remote repo to the local repo (to update the local copy of the branch)

- 'Fork' and 'Pull Request' are features of GitHub (and NOT Git)

- Used to share Git repositories with people. All the repository files are public (files can be stored privately using a paid subscription). Useful for allowing multiple individuals to collaborate on a single project, while working independently.

- Using GitHub involves syncing between the repository on your local system and the version hosted on the GitHub servers, called the 'local' and 'remote' repository respectively.

- The syncing mainly deals with exchange of commits between the local repository and the remote repository. So we only stage and commite files for the local repository, and do not bother with the same for the remote repository.

- This syncing is done manually by the developer, using commands 'push' and 'pull' on the concerned branches