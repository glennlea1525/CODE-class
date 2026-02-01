# GitHub Practice Repository

## Initialize a local directory

Make a directory CODE-class and cd into it.

Initialize a local REPO

    git init

The local repo is ready now for cloning a remote Repository into it.

## Clone the CODE-Class repository into the local REPO directory:

    git clone https://github.com/glennlea1525/CODE-class.git

## Add a Markdown file to your local Repo

Make a new branch*: 
	
    git checkout -b <my-branch> (make new branch)

In the new branch make a new markdown (.md) file: 

	your_name.md

Add some Markdown content to file. Sample markdown is in the markdown-cheat-sheet.md file. 

Save the file

*Note: git branch shows the new branch only after first commit.

## Commit your changes

Shows untracked files (the file you just made)

	git status
    modified your_name.md

Track the file you just made.

	git add .

Ensures the job was done.

	git status

Commit your changes and add a short description of this commit.

	git commit –m “your_name.md”

## Push your changes to the remote repository

Push changes to a new branch on the remote repository

	git push origin my-branch

You should now see your own branch listed after running:

	git branch 

Results should be

	main
	*my-branch

*Note: Star next to branch is the currently active branch.
