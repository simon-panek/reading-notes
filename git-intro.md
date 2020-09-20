# Code 102: Class 3 - Git Intro
***
## Read: 03 - Git Intro

Version Control *system that records changes and allows easy access to previous versions*
* Local Version Control *__LVC__ entails one database on the local hard disk that stores changes*
* Centralized Version Control *__CVC__ single server stores all of the files and versions which are accessed by multiple clients allowing for greater collaboration, read and write privileges can be controlled*
* Distributed Version Control *__DVC__ improves on the CVC concept by storing mirrored repositories on multiple servers, removing the single point of failure*

Git *a DVCS that saves system of snapshots of your project*
- primarily relies on locl operations
- all changes to any file is tracked
- makes it difficult to accidently lose data
- File states in git
  - committed *securely stored in a local database*
  - modified *changed, but not committed to the database*
  - staged *flagged a file's changed version ot be committed in the next snapshot*
  
Getting Git help in Terminal
```
git help *command*
git *command* --help
man git-*command*
```

Cloning a repository *Git will automatically give the name "origin" to the server and the name "master" to your local branch*
`$ git clone (url)`

List of terminal commands
`$ git status` *Returns the current branch as well as the status of working files*
`$ git add filename` *Stages the filename*
`$ git add *` *Stages all files in a repository*
`$ git commit -m "message here describing the changes" *Commits the file and includes a describing message*
`$ git push origin master` *Pushes changes from the local "master" branch to the remote repository named "origin".
`$ git stash` *Temporarily removes changes and hides them, giving you a clean working directory*
`$ git stash apply` *Retrieves hidden changes*
`$ git remote` *See the short names of all specified remote handles*
`$ git remote -v` *Shows all the remote URLs next to their short names*

Remote repositories *versions of a project stored online or on network. Teams can push info to and pull info from remote repositories*

***
[Return to reading-notes Deployed Site](https://paneks19.github.io/reading-notes/)

[Return to reading-notes Mark Down](https://github.com/paneks19/reading-notes)
