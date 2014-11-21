---
title: Features
layout: default
group: navigation
---

# What to expect from MacGitver? (The Features)
MacGitver is still under heavy development and lots of features are not completed. If you are a developer and like to contribute to the project, feel free to contact one of the developers.

In the current development state MacGitver provides mostly basic Git tasks.

## Git Configuration
* Editor for Git's system, user and repository configuration

## Repositories
* Create a new repository
* Clone an existing repository (Not completely supported yet!)
    * The working directory appears empty and has to be checked out manually. (i.e. `git checkout master`).
    * Not all protocols are supported yet (especially SSL).
* Open an existing local repository (and its submodules!) and display the full history.
* Switch between multiple repositories

## Submodules
* Seamlessly navigate between submodules and their parent repository.
* Tooltips provide information about each submodule and its state.

## Branches
* Overview of all existing branch references (local and remote) plus tags.
* Create a local branch on any commit in a repository's history.
* Checkout a branch (branch will not be activated yet!)
* Rename a branch (currently only supported for local branches)

## Difference Viewer
Compare current HEAD commit with ...

* ... working directory
* ... parent
* ... all parents (important for merge commits)
* ... a branch

## Working Directory and Stage Area
* Display working directory and Stage Area (aka the Index)
* Highlight changed files in working directory
* Display file differences
* Create a commit (with a message)
