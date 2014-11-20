---
title: The MacGitver Project
layout: default
---

# About the MacGitver project
More experienced users of the Git version control system know, that it is a very powerful and useful system. But -- the learning curve is still high for newcomers. And even experienced users always have to lookup command options to accomplish more complex versioning tasks.

The lack of a good user interface (at least) for all major plattforms makes the user experience even worse.

## Let's fix that!
MacGitver makes Git easier for newcomers and takes some of the burden, having to learn hundreds of Git options, hacking them into a terminal to simply setup a working repository.
At the same time, professional users are able to accomplish more sophisticated tasks like when a team member accidently messed up a repository.

## Some internal details and project history
Development of MacGitver began in 2011 and actually resulted out of two separate projects, driven by the same motivation:
*Create a freely available user interface to control Git in a comfortable way.*

The developers of both projects decided to merge their begun work into one of the two projects. Thus, the other project, called *MsPiggit*, is no longer maintained and only lies there for reference.

To make the system perform fast and support at least the major desktop plattforms as good as possible, Qt and C/C++ were the first choice as a solid base.

## So, what is it?
Well, in short, the goal is to make you feel like being at home, relaxing on the couch, while managing complex versioning tasks of a your project(s) at work.

# What to expect from MacGitver? - (The Features)
MacGitver is still under heavy development and lots of features are not completed. If you are a developer and like to contribute to the project, feel free to contact one of the developers.

## Basic Git tasks

### Git Configuration
* Graphical editor for system, user and repository Git configuratio

### Repositories
* Create a new repository
* Clone an existing repository (Not completely supported yet!)
    * The working directory appears empty and has to be checked out manually. (i.e. `git checkout master`).
    * Not all protocols are supported yet (especially SSL).
* Open an existing local repository (and its submodules!) and display the full history.
* Display submodules and switch between the repositories
* Display the status of the working directory and the stage area.

### Branches (locally)
* Create a branch
* Checkout a branch (branch will not be activated yet!)
* Rename a branch

### Difference Viewer
Compare current commit with ...

* ... working directory
* ... parent
* ... all parents (important for merge commits)
* ... a branch

### Working Directory and Stage Area
* Display working directory and Stage Area (aka the Index)
* Highlight changed files in working directory
* Display file differences
* Create a commit (with a message)
