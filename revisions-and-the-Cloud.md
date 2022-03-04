# Git Tutorial

## Version Control

- Allows someone to revisit various version of a file or set of files
- This allows reverting a file or project to a previous version
- Useful for tracking modifications

### Local Version Control

A local database on your hard drive

### Centralized Version Control

A single server storing all changes and file versions  
This allows for programmers to streamline collaboration  
gives access to everyone's files in one spot and gives admins more control

### Distributed Version Control

To prevent having a single point of failure ie. the server  
DVCS allows mirrored repositories that act as backups  
Used to backup lost information 

## Git

- Git is a DVCS that stores data in a file system made of snapshots  
- Commits are saved versions of your project  
- Relies on local operations since that is where most necessary information can be found
- Git will track changes which allows it to detect file corruption or loss of info
- Three main stages of Git files
  - Committed - Data is securely stored in a local database
  - Modified - File has been changed but not committed to the database
  - Staged - Flagged a file's changed version to be committed in the next snapshot
- To clone a repository into your local database use git clone https://<i></i>github.com/test
- In order to push local changes of your files to GitHub follow A-C-P
  - A- is for git add to track and stage the files first
  - C- is for git commit in order to record what you did and follow it with a -m to explain what and why you made changes
  - P- is for git push origin main to push the changes to the remote repository

[Return to Code 102 Table of Contents](https://rogermreyes.github.io/Reading-Notes/Code-102-Reading-Notes)