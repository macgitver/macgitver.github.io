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
* Create repositories
* Clone existing repositories
    * Some major protocols are not yet supported (especially SSL).
* Open local repository (including submodules!) and display the complete history.
* Navigate between repositories

## Submodules
* Seamlessly navigate between repositories and submodules.
* Tooltips provide information about a submodule´s state.

## Branches
* Overview of all existing local and remote branches, tags and other references.
* Create local branches on any commit in a repository´s history.
* Checkout a branch (branch will not be activated yet!)
* Rename a branch (currently only supported for local branches)

## Difference Viewer
Compare any commit in a repository´s history to ...

* ... all parents (especially useful for merged commits)
* ... a single parent commit
* ... another branch
* ... the current working directory

## Working Directory and Stage-Area
* Display files in the working directory and stage them.
* Highlight changed files in the working directory.
* Commit all staged files to the repository.
