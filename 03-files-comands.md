# Local repo changes

## Sending a local change to the staging area
>Adding a specific file
	git add fileName.ext 

>Adding all files of a specific extension 
	git add *.ext

>Adding all files (except in .gitignore)
	git add .

## Ignoring files and folders

>Ignore files or folders using .gitignore 
	fileName.ext
	folderName/
>Ps: .gitignore it's a hidden file. If you have problem to create it, you can do it using cli (touch .gitignore)


## Removing files from staging area
>Remove a file from staging area
    git rm --c fileName.ext

>Remove and DELETE a file from staging area (force removal)
    git rm -f fileName.ext

>Remove all files in staged area, from a specific folder
	git rm -r --cached 'folderName'


## Commits

>Confirm changes from staging area (after that, you'll be requested to enter a commit message)
	git commit 

>Commit with the message on the same line of command
	git commit -m "My commit message here"

>Adding all files to staging area and commit on the same line of command
	git commit -a -m "Mensagem do commit"


## Commits Messages

>Change a commit message
	git commit --amend
>OR
	git commit --amend -m "...new message here..."


>Change a commit message on the last pushed commit
	git commit --amend -m "...msg..."

>Forcing a Push to alter the commit message
	git push --force

