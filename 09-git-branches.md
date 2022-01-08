# Branches
>Branches are 'parallel project', with the purpose of working on some features or changes without directly affect the main project/branch

# Checking available Branches
    git branch

# Checking available remotes Branches (on github)
    git branch -r

# Checking all available Branches
    git branch -a

# Creating a new branch
    git branch newBranchName

# Changing active branch
    git checkout branchName

# Creating and changing active branch
    git checkout -b branchName

# Creating a local branch, changing to it and then, copying from a remote branch to it
    git checkout -b localBranchName remoteBranchName

# Delete a local branch
    git branch -D branchName

# Delete a remote branch
    git push origin -d my-branch-name


# Pushing a local branch to a remote repository
> After commit and push your local branch to the repository
>   Change to the master branch, then:
        git merge origin/branchName 

>Then, git push again, and delete the branch (local and remote)
