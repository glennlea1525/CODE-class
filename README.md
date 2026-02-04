# Github Practice Repository 🚀

[This repository is for students of the CODE University Technical Documentation course to get up to ensure each student knows how to push files to a common repository.]


## Contents

- Overview
- Prerequisites
- 
1. Initialize a local directory
1. Clone the remote repository
1. Make a new branch
1. Add a new markdown (.md) file to your local Repo
1. Merge your branch to main
1. Commit your changes
1. Push your changes to the remote repository CODE-class

---

**Overview**
Students must know how to 

- initialize a repository,
- clone remote repositories to a local machine,
- make new branches
- add new files,
- commit changes,
- push changes to the remote repository
- merge changes to main
- delete branches

**Prerequisites**

Before you begin, make sure you have the following installed on your local machine:

- VSCode
- 

**1. Initialize a local directory**

Make a directory and name it CODE-class then cd into it. Afterwards, run the following command:

```bash
git init
```
The local repo is ready now for cloning a remote Repository into it.

**2. Clone the remote repository**

Clone the CODE-Class repository into the local REPO directory you just created:

```bash
git clone https://github.com/glennlea1525/CODE-class.git
```

**4. Make a new branch** 

```bash
git checkout -b <my-branch> (make new branch)
```

**3. Add a new markdown (.md) file to your local Repo**

Make a new file and name it as follows:

```
<your_name.md>
```

In this file, use Markdown to add your name. You can add anything else you want here, as long as it is in Markdown.

```
{
  "firstName": "Glenn",
  "lastName": "Lea",
}
```

Save the file

*Note: git branch shows the new branch only after first commit.*

**4. Track your changes**

Shows untracked files (the file you just made)

```bash
git status
```

It should show the new file you just created.

Track the file you just made.

```bash
git add .
```

Ensures the job was done.

```bash
git status
```

**5. Commit your changes**

Run the commit command and add a short description of this commit.

```bash
git commit –m “your_name.md”
```

**6. Push your changes to the remote repository CODE-class**

Push changes to a new branch on the remote repository:

```bash
git push origin my-branch
```

You should now see your own branch listed after running:

```bash
git branch
```

Results should show the following:

```bash
main
*my-branch
```

*Note: Star next to branch is the currently active branch.*

**7. Merge your branch into main**

**(Should this be moved up?)**

To merge locally, you must be on the main branch

Switch to the target branch*

```bash
git checkout main
```

Pull the latest changes from the remote to ensure you're up to date

```bash
git pull origin main
```

Merge the source branch into 'main'

```
git merge my-branch
```

**Push your changes to main

```
git push origin main
```
