# Git and GitHub

Git and GitHub are essential tools for version control and collaborative software development. They enable developers to track changes to their codebase, collaborate with others seamlessly, and manage projects effectively.

## Table of Contents

- [Introduction](#introduction)
- [Git and GitHub](#git-and-github)
  - [Git](#git)
  - [GitHub](#github)
  - [Difference Between Git and GitHub](#difference-between-git-and-github)
- [Common Git Terms](#common-git-terms)
  - [Repository](#repository)
  - [Commit](#commit)
  - [Tree](#tree)
  - [Remote](#remote)
  - [Branches](#branches)
  - [Clone](#clone)
  - [Checkout](#checkout)
  - [Pull](#pull)
  - [Push](#push)
  - [Fetch](#fetch)
  - [Reset](#reset)
  - [Merge](#merge)
  - [Staging Files (Add)](#staging-files-add)
  - [Committing Changes](#committing-changes)
- [Installation of Git and GitHub Desktop](#installation-of-git-and-github-desktop)
  - [Windows Installation](#windows-installation)
  - [Linux Installation](#linux-installation)
  - [GitHub Desktop Installation](#github-desktop-installation)
- [Configure User Name](#configure-user-name)
- [Install Git in Local Repository](#install-git-in-local-repository)
  - [Intitialize git](#intitialize-git)
  - [Cloning the repository](#cloning-the-repository)
- [.gitignore file](#gitignore-file)
- [Git Basic Commands](#git-basic-commands)
  - [Managing Changes](#managing-changes)
    - [Check the status of files](#check-the-status-of-files)
    - [Add file(s) to the staging area](#add-files-to-the-staging-area)
    - [Commit changes to the repository](#commit-changes-to-the-repository)
  - [Viewing and Updating](#viewing-and-updating)
    - [View commit history](#view-commit-history)
    - [Push and Pull from Remote](#push-and-pull-from-remote)
  - [Branching and Merging](#branching-and-merging)
    - [Create a new branch](#create-a-new-branch)
    - [Switch to a different branch](#switch-to-a-different-branch)
    - [Merge changes from one branch into another](#merge-changes-from-one-branch-into-another)
  - [Miscellaneous](#miscellaneous)
    - [View remote repositories](#view-remote-repositories)

---

## Introduction

Git and GitHub are pivotal in modern software development, offering robust version control and collaboration capabilities that enhance productivity and project management.

## Git and GitHub

### Git

Git is a distributed version control system that tracks changes to files, allowing developers to manage and collaborate on projects efficiently.

### GitHub

GitHub is a web-based platform built around Git, providing hosting for repositories, collaboration tools, and workflows such as pull requests and issue tracking.

### Difference Between Git and GitHub

| Aspect         | Git                                      | GitHub                                                  |
|----------------|------------------------------------------|----------------------------------------------------------|
| **Nature**     | Version control system                    | Hosting platform for Git repositories                     |
| **Functionality** | Tracks changes locally                  | Hosts Git repositories in the cloud, adds collaboration features |
| **Access**     | Command-line interface (CLI)              | Web-based interface                                      |
| **Scope**      | Local                                     | Cloud-based, accessible globally                          |
| **Collaboration** | Limited (local collaboration)           | Extensive (remote collaboration, pull requests, issues)  |
| **Usage**      | Individual development                   | Team collaboration, open source projects                  |

## Common Git Terms

### Repository

A repository (repo) is a storage space where your Git project resides. It contains all files, folders, and version history related to your project.

### Commit

A commit is a snapshot of changes made to files in the repository at a specific time. It represents a saved state of your project and includes a commit message that describes the changes made.

### Tree

A tree represents the hierarchy of files and directories in a Git repository, organized by commits.

### Remote

A remote is a version of your repository that is hosted on a server, typically on platforms like GitHub or GitLab. It allows collaboration with others and synchronization of changes.

### Branches

Branches are separate lines of development within a repository. They allow you to work on different features or versions of your project without affecting the main codebase.

### Clone

To clone a repository means to create a local copy of it on your machine. This allows you to work on the project locally, make changes, and synchronize those changes with the remote repository.

### Checkout

Checkout is the process of switching between different branches or versions of a repository.

### Pull

Pull is used to fetch and download content from a remote repository and update your local repository at the same time.

### Push

Push is used to upload local repository content to a remote repository.

### Fetch

Fetch is used to download content from a remote repository but does not automatically merge it into your current branch.

### Reset

Reset is used to undo changes in your working directory, staging area, or commit history.

### Merge

Merge is used to integrate changes from one branch into another branch.

### Staging Files (Add)

Staging files means preparing files to be included in the next commit. This is done using the `git add` command.

### Committing Changes

Committing changes means saving staged changes to the local repository with a descriptive commit message using the `git commit` command.

## Installation of Git and GitHub Desktop

### Windows Installation

To install Git on Windows, visit [git-scm.com](https://git-scm.com).

### Linux Installation

Install Git on Linux through your distribution's package manager or download it directly from [git-scm.com](https://git-scm.com/download/linux).

### GitHub Desktop Installation

To install GitHub Desktop, visit [GitHub Desktop](https://github.com/apps/desktop).

## Configure User Name

After installing Git, configure your global username and email using the following commands in the terminal:

```bash
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"

## Install git in local repository
### Intitialize git 
This will initialize git on a local repository
```
git init
```

### Cloning the repository
This will clone all the files , branches , commits that already exists on github.
```
git clone [url]
```

## .gitignore file

The `.gitignore` file specifies files and directories that Git should ignore. It prevents unnecessary files (e.g., build artifacts, temporary files) from being tracked by Git, keeping the repository clean and focused on important code.

## Managing Changes

### Check the status of files

```
git status
```
### Add file(s) to the staging area

```
git add <file1> <file2> ...
```

### Commit changes to the repository

```
git commit -m "Your commit message here"
```

## Viewing and Updating

### View commit history

```
git log
```

### Push and Pull from Remote

```
git push origin <branch-name>
git pull origin <branch-name>
```

## Branching and Merging

### Create a new branch

```
git checkout -b <branch-name>
```

### Switch to a different branch

```
git checkout <branch-name>
```
### Merge changes from one branch into another

```
git merge <source-branch>
```

## Miscellaneous

### View remote repositories

```
git remote -v
```

