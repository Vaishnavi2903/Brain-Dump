# GitHub
## Gists
- Similar to repositories.
- Simplified way of sharing code repositories with other developers
- Every gist is Git repository which can be forked or cloned. These gists can either be secret or public.
### Public gists
- created for the public and displayed publicly.
- searchable
### Secret gists
- not searchable
- not entirely private
- can be shared with the help of a link to friends and fellow developers
## Wikis
- Every repositiory on Github has a dedicated section for hosting documentation known as wiki
## Branches
- a new development string extracted from the main branch
- comes handy when building or working on a new release
- changes done here can be reverted if it does not
- safe place to experiment
## Commits
- A commit is a change to one or more files on a branch.
- Every time a commit is created, it's assigned a unique ID and tracked, along with the time and contributor.
### Stages of Version Control
- Untracked - Initial state of a file when git is not aware of the file or the file is not part of any repository yet.
- Tracked - File that git is consistently monitoring.
  - Unmodified: The file is tracked, but it hasn't been modified since the last commit.
  - Modified: The file has been changed since the last commit, but these changes aren't yet staged for the next commit.
  - Staged: The file has been modified, and the changes have been added to the staging area (also known as the index). These changes are ready to be committed.
  - Committed: The file is in the repository's database. It represents the latest committed version of the file.
## Pull request
A pull request is the mechanism used to signal that the commits from one branch are ready to be merged into another branch.
