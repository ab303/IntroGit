## Version Control

Versions are nothing but different saves on a file. Let’s say I have a grocery list. I add milk to it and I save it. Then I add cookies to it ad save it again. Each time I save the file I’m creating a new version. Now what Version control does is it lets you keep the versions of your grocery list organized. Version control lets you keep track of **when** the change was made, **why** it was made and **who** made those changes.

## Tracking changes

* **Working directory**: The directory that your are currently in is your working directory.
* **Staging area**: This is where you want to put your files so that git tracks the changes you make to your files.
* **Repository**: Once your are satisfied with the changes that you’ve made you can commit those changes. The changes that you commit are safely stored in your repository.

## set up your credentials
* this is done to let git know who you are.
`git config --global user.name "John Doe" `
`git config --global user.email johndoe@example.com`


## git commands

### git init
* `git init` is used to initialise a repository.
* It creates a .git directory in your project folder
* The .git directory contains everything related to git.

### git add
* To add your file to staging area use
* `git add <filename>`
* This will make git track the changes made to this file

### git status
* Running git status helps you check if the files are staged or not
* It also lets you know on which branch you’re currently working
* `git status`

### git commit
* To save the changes you made, you can use the git commit command.
* When you commit changes, you must include a commit message along with your commit which describes your commit.
* This can be done by `git commit –m “message”`

### git diff
* Git diff can also be used to find changes made since the last commit**
* Git diff can be used to find out the changes made to the staged files. This can be done using
* `git diff --staged.`

### Git Branch
* To create a new branch type in
`git branch <branch name>`
* Branches can be deleted using the –d option
`git branch –d <name of branch to be deleted>`

### Git checkout
* To switch to your newly created branch use git checkout
`git checkout <branch name>`

### Git merge
* Once you’ve finished your work on the branch you’ll want to merge your branch with the original master branch.
* To do this you’ll use git merge
* Navigate to your main branch using checkout and type in
`git merge <branch to be merged>`

### Git log
* git keeps a log of all the commits made.
* To view the log type in
`git log`

### Remotes in git
* Remote repositories in git are repositories hosted on the internet(Github.com)
* To create a remote to a repository on the web use
`git remote add <shortname> <url>`
* You can name your remote anything you want but the general convention is to name your main remote as origin

### git push
* Git push is used to push your local commits to a remote repository.
* To push your commits to a remote named origin use
`git push origin master`

### Git pull
* If your online repository becomes out of sync you can use git pull to pull all the different commits made on the online repository.
`git pull origin master`
