- **Git** is a version control system, created by Linus Torvalds (yeah, the same guy who built Linux. Talk about high performance issues).

- Used to keep versions of an entire project
	- Two consecutive versions differ in the contents of atleast one file
	- A repository refers to a group of one or more files of a directory being monitored by Git. All files of the directory need not be monitored.

- Git workplace consists of 3 separate areas, which allow the user to handle which updates correspond to which version more effectively:
	1. _Working Directory_ - The actual directory where all the changes that you make to your files are stored/saved
	1. _Staging Area_ - An abstract location where files can be selectively 'added', before being bundled together as a single commit (read 'version')
	1. _Repository_ - Refers to the set of all the versions/commits of the project repository. Staged files are bundled into a single commit and recorded here.

- _Branches_ allow users to have multiple independent project end-points to work on, such that changes to one don't break the code of another end-point. Branches are useful for fixing bugs, adding new features, t

- _Merge_ is used to incorporate the commits/changes of two or more branches into the current branch, without affecting those other branches. Merge conflicts arise when the changes being incorporated are in conflict with each other and/or the content of the branch into which the merge is happening.

- _GitHub_ is a web-service based on Git, used for sharing code and collaborating with others.