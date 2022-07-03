# git-commands

## 1. git checkout -- {fileName}
discard uncommitted changes to the specified {fileName}

## 2. git stash 
saves your changes and reverts the working directory to what it looked like for the latest commit

## 3. git stash list 
list all stashes

## 4. git stash apply {Index}
applies the changes and leaves a copy in the stash

## 5. git stash push -m "{message}"
same as git stash, but has a more descriptive message

## 6. git stash drop {Index}
delete a stash by its Index

## 7. git stash pop {Index}
same as git stash apply, but deletes the stash from the list

## 8. git stash clear
remove all stashes

