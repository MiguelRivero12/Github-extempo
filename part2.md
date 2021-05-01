# Git commands
| Command | Useness|
| ------ | ------ |
 ```git config --global user.name ``` | "MiguelRivero12" 
 ```git config --global user.email ``` | "MiguelRivero12@github.com" 
```git config --global core.editors``` | name of the editor defines which editor to use 
```git config--list``` | lets you check your configurations

`git init` is used to start a repository in your computer

`git nano filename.extension` creates a file lets you type it, you would use ctrl+x to leave, y to save ctrl+o and then enter

`git add filename.extension` adds it to start tracking it

`git commit -m " message "` lets you commit it and save with a message

`git push` is used to upload

`git pull` used to upload the recent sea file of the repository

`git clone` https://github.com/MiguelRivero12 is used if you want to clone a directory

`git rm filename.extension` removes the file

`git log` allows to see the history

`git remote -v` lets you see the remotes that are associated

`git mergetool` is used as a graphic tool so see merging problems and resolve them

`git commit` would let you finally commit the merge

### Git flow
`git flow init` initiates gitflow

`git flow feature start` feature/example creates a new feature

`git flow feature pull origin` feature/example is used to obtain a feature branch from the remote repository

### Branches
| Command | Useness |
| ------ | ------ |
```git branch *name*``` | With this command you create a branch where you can work in parallel.
```git checkout *name*```| Change branch
```git checkout -b``` | Create and change to another branch
```git merge *name*``` | Fusion branches and make a commit
```git branch -d *name*``` | Delete the branch
```git branch --contains *commit*``` | This command is for seeing in which commit that branch stayed.

