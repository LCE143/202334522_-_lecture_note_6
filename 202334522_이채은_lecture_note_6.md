# 202334522_-_lecture_note_6

## Version Control and Collaboration
- It's essential to use a version control system for software development and other documentation works.
- We need a systematic management system for version control and collaboration.

### Changes vs Snapshots
- Changes: Storing data as changes to the base version.
- Snapshots: Storing data as snapshot(using in Git)

### Version Control System in Collaboration.
- Local
- Centralized
- Distributed

### Three States in Git
- Modified: Working Directory
- Staged: Staging Area
- Comitted: git directory

#### Git config: First-time setup
Git configurations are stored in three levels:
 - System Level: --system option. Affects all uses and repositories on the system (administrative)
 - Global (user) level: --global option. Affects all repositories of a current user
 - Local level: --local option. Specific to the current repository
 - * Each level overrides values in the previous level: system -> global -> local

#### Initializing a Repository in an Existing Directory
 - $ git init
 - $ git ststus
 - $ git add [file_name]
 - $ git rm-cashed [file_name]
 - $ git commit-m "commit message"
 -  
