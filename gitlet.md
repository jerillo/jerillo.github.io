---
layout: inner
title: Gitlet
permalink: /gitlet/
---
# Gitlet    
##### Written in Java 
--- 
A version-control system that mimics some of the basic features of the popular system Git.
This project was created for UC Berkeley's CS 61B: Data Structures in Spring 2020. 

*Source code for this project can be provided upon request.*

---

## Features
Some functionality of Gitlet include:    
- Save contents of files in commits
- Restore a version of one or more files or entire commits
- View history of backups
- Maintain related sequences of commits in branches
- Merge changes made in one branch into another
- Simplified implementation of Git's remote features

--- 

## Preview
Note that all of the commands are prefaced with `java gitlet.Main`.
- **Initialize** a Gitlet repository using the `init` command. This will create a .gitlet folder, which contains files such as serialized commits and objects.
- Check the **status** of files and branches in your repository using the `status` command.
- Create a new **branch** with a specified name using `branch [branch name]`.

![Init, Status, Branch](../img/preview/gitlet/init-status-branch.gif)   

- Stage files for **addition** using `add [file name]`.
- Create a new **commit** of files so that they can be restored at a later time using `commit [message]`.
- View a **log** of the commit history in the current branch using `log`.

![Add, Commit, Log](../img/preview/gitlet/add-commit-log.gif)   

- **Remove** a file from the commit using `rm [file name]`.
- **Checkout** a different branch using `checkout [branch name]` to make `[branch name]` the active branch.
- **Merge** two branches using `merge [branch name]`.

![Remove, Checkout, Merge](../img/preview/gitlet/remove-checkout-merge.gif)   

- **Reset** to a different commit using `reset [commit id]` 
- **Remove branch** with a given name using `rm-branch [branch name]`   

![Reset, Rm-branch](../img/preview/gitlet/reset-rmbranch.gif)  
