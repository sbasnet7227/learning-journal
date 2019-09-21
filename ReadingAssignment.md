# Git Tutorials
## INTRODUCTION:
-  Git is a distributed version control that stores data in a file system made up of snapshots.

### **Version Control:**
- Version Control is a system that allows you to revisit various versions of a file or set of files by recording changes. Through version control, one can revert a file or project to a previous version, track modifications and modifying individuals, and compare changes. By utilizing a Version Control System (VCS), mistakes with files can easily be rectified.
- Types of Version COntrol
    - Local Version Control
    - Centralized Version Control
    - Distributed Version Control

**States:** Files in Git can reside in three main states: committed, modified and staged.

- Committed: Data is securely stored in a local database

- Modified: File has been changed but not committed to the database

- Staged: Flagged a file’s changed version to be committed in the next snapshot

- **Some of the Git commands are:**
    - git clone URL(GitHub repository url)
    - git status: check file status
    - git add . : Track all files in a repository by using this command
    - git commit -m 'updated resources' :  committing files with committing message
    - git push origin master : pushing changes
    - git log : shows all the updates; after this command press q to exit
    - git remote -v : display GitHub url

- Local Repository Structure: The local Git repository has three components:

    - Working Directory: The actual files reside here.
    - Index: The area used for staging
    - Head: Points to the most recent commit

