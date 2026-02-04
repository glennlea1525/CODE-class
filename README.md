[Github Practice Repository] 🚀

[This repository is for students of the CODE University Technical Documentation course to get up to ensure each student knows how to push files to a common repository.]

---

## Overview
Students must know how to 

- initialize a repository,
- clone remote repositories to a local machine,
- make new branches
- add new files,
- commit changes,
- push changes to the remote repository
- merge changes to main
- delete branches

[🚀 Getting Started]

## Prerequisites

Before you begin, make sure you have the following installed on your local machine:

- VSCode
- 

## 1. Initialize a local directory

Make a directory CODE-class and cd into it.

``` bash
git init
```

The local repo is ready now for cloning a remote Repository into it.

## 2. Clone the CODE-Class repository into the local REPO directory:

```bash
git clone https://github.com/glennlea1525/CODE-class.git
```

## 3. Add a Markdown file to your local Repo

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
