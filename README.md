# 3.1 Introduction to GIT I

## Basic Git commands and its uses

`git version`

To verify Git is installed on local terminal

`git init`

Initialise a Git repository in current directory

`git clone <repository-url>`

Clones the repostory from remote to current directory

`git add <file>` or `git add .`

Add specific file to staging area or adds all files to staging area

`git status`

Show current state of the repository, showing if there are any changes to the files or if new files or branch is added

`git commit -m “<message>”`

Prepares a new commit for file(s) in the staging area

`git push`

Pushes the update to the files to the repository

`git pull`

Retrieves any updates to the files in the repository to local directory

`git branch`

Checks the available branch in the repository

`git checkout -b <new-branch-name>`

Switched to the specific branch

`git push --set-upstream origin <branch-name>`

Set the local terminal to prepare any future `git push` to new branch

`echo "# Simple README" > README.md`

Updates the file `README.md` to include the line `# Simple README`