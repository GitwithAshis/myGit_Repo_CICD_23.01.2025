#  myGit_Repo_CICD_23.01.2025


# Collaborative Git Project: Working Together on the Same File

## This project demonstrates how two developers, Dev A and Dev B, can effectively collaborate on the same file using Git and GitHub for version control. By following the steps outlined below, multiple developers can seamlessly contribute to a shared codebase while avoiding conflicts.

## Project Overview

In this project:

Dev A creates and initializes the repository.

Dev B clones the repository and works collaboratively with Dev A.

Both developers push, pull, and sync their changes using Git commands.

## Steps to Collaborate

# Step 1: Initial Setup (By Dev A)

# 1. Initialize the repository:

git init

# 2. Create the file and add initial content:

File Name: Myjavafile

Dev A writes the first and third lines of Java code.

# 3. Stage and commit the changes:

git add Myjavafile
git commit -m "Initial commit with first and third lines of code"

# 4. Push the changes to GitHub:

git remote add origin <repository-url>
git branch -M main
git push -u origin main

## Step 2: Clone the Repository (By Dev B)

Dev B clones the repository:

git clone <repository-url>

Dev B edits the file by adding the second line of Java code.

Dev B stages and commits the changes:

git add Myjavafile
git commit -m "Added second line of code"

## Step 3: Push and Pull Changes

# Dev A:

 After editing, Dev A pushes the file to the repository:

git push

# Dev B:

Dev B pulls the latest changes from the repository before editing further:

git pull

# After resolving any conflicts (if any), Dev B commits their changes and pushes them back:

git add Myjavafile
git commit -m "Resolved conflicts and updated file"
git push

## Step 4: Syncing Changes

Both Dev A and Dev B continue to:

Pull the latest changes using git pull before editing.

Push their updates using git push after editing.

# Git Commands Reference

Command

Description

git init

# Initializes a new Git repository.

# git clone

Clones an existing repository.

# git add

Stages changes for commit.

git commit

Commits staged changes to the repository.

git push

Pushes local commits to the remote repository.

git pull

Pulls the latest changes from the remote repository.

Key Learnings

# Seamless Collaboration: Git allows multiple developers to work on the same file without overwriting each other’s work.

Conflict Management: Conflicts can be resolved easily by pulling the latest changes and making necessary edits.

Version Control: git push and git pull are essential for keeping local and remote repositories in sync.

## GitHub Repository

https://github.com/GitwithAshis/myGit_Repo_CICD_23.01.2025
