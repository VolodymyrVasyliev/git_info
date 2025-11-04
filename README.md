//Terminal commands

exit - ends the terminal session
pwd - shows the current location in the file structure
ls - displays a list of files and folders in the current working directory
cd .. - moves back one level (nesting, folder), i.e., to the previous directory
cd [directory name] - moves forward, i.e., to a subdirectory
cd ~ - returns to the root directory
clear - clears the contents of the terminal

//Git commands
git inint -Initializes a local repository
git clone - https://github.com/userName/repoName.git

git branch - a list of branches that exist locally on the computer
git branch -r — shows only remote branches
git branch -a — shows all branches, both local and remote

git branch [branch name] - creates a new branch
git checkout [branch name] - to go to the selected branch
git checkout -b [branch name] - combines 2 action commands

git status - What stage is the project at now?

git add . - save all changes
git commit -m "[name save commit]" - sign saves
git commit -am "[name save commit]" - sing and save changes
git push - push changes to git

git pull - fetches all the latest changes from the remote repository(to pull changes from a branch that interests me, I need to be in it)

git merge [name branch] - merging branches(you need to be in the branch where the merge will be done)

git branch -d [name branch] - deletes a branch (delete without being in it)
git push origin --delete [name branch] - deletes a branch from a remote repository

git stash - instantly saves unfixed changes
git stash save [my-comment] - add a comment when a new post is created
git stash apply stash@{56f4531} -apply a specific Stash without deleting it
git stash list - revisiting the Stash list
git stash pop - to save the remaining changes and remove them from the stack
git stash clear - deleting all saved stacks
