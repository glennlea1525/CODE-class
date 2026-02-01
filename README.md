# GitHub Practice Repository

## Initialize a local directory

1. Make a directory CODE-class and cd into it.
1. Initialize a local REPO using git init.

The local repo is ready now for cloning a remote Repository into it.

## Add a Markdown file to your local Repo
1. Make a new branch*: 
	
    git checkout -b <my-branch> (make new branch)

2. In the new branch make a new markdown (.md) file: 

	<your_name.md>
3. Add some Markdown content to file. Sample markdown is in the README file. 

4. Save the file

*Note: git branch shows new branch only after first commit.

## Get a local copy of CODE-Class repository:

git clone https://github.com/glennlea1525/CODE-class.git

## Commit your changes using the following commands

Shows untracked files (the file you just made)

	git status

Track the file you just made.

	git add .

Ensures the job was done.

	git status

Commit your changes and add a short description of this commit.

	git commit –m “Initial commit”

## Push your changes to the remote repository

Push changes to a new branch on the remote repository

	git push origin my-branch

You should now see your own branch listed after running:

	git branch 

Results should be

	main
	*my-branch

*Note: Star next to branch is the currently active branch.
