---
title: MacGitver
layout: default
group: "main-projects"
project: "MacGitver"
---

# Why MacGitver is what you always searched for
Do you know Git? The awesomely fast, secure and flexible versioning system? No doubt, it really is a powerful system and probably you use it to maintain versions of your homepage or an open source application. And yes ... this very website you are just looking at is stored in a Git repository.

So, why would you need another tool to handle such a well thought system? Well - assume you only want to view the history. You'll probably end up in typing something like this:

```bash
git log --oneline --graph --decorated --color
```

After you learned how to do that, you create an alias (maybe something like `git history`). Does this sound familiar? Now let's say you work with a team of 5 developers. Every single developer in your team has to learn and perform the above task. Quite time consuming isn't it?

Note, that this example is kept very simple, just to show where a GUI can be useful.

There's tens of existing applications supporting that already, right? So **what makes MacGitver unique?**

Well ... in short, our goal is to make you feel like relaxing on the couch while performing complex versioning tasks on your project(s).

Ok, let me tell you some of our leading motivations  ...

**... for users:**

1. Clean user interface with lean menus and well thought keyboard shortcuts.
2. Customizable (e.g. theming, fonts, branch colours, etc.)
3. Complete overview about your (local) repository (including submodules and worktree) in one screen.
4. Quick as the terminal (in both usability and performance).
5. Natively support the major platforms (currently UNIX only!).

**... for project members**

1. Open Source'd with a highly maintainable code base.
2. Build on a stable API instead of wrapping the console (aka libgit2).
2. Keep modularity.
3. Keep high stability and overall quality.

We highly appreciate, if you like to try it and provide feedback. **Want to join the team?** Feel welcome! Start by browsing our public [issues](https://github.com/macgitver/MacGitver/issues) or register to our [mailing list](mailto:dev-subscribe@macgitver.org).

# Some technical stuff
MacGitver is powered by the C-library [libgit2](https://libgit2.github.com). The higher level abstractions and the GUI part is completely powered by [Qt](http://qt.io) and advanced C++ techniques. This makes the system perform fast, while being able to provide multiplatform support.

# Want to know how the project began?
Development of MacGitver started in 2011 and is the result of two separate projects, driven by the same motivation.

The developers of both projects decided to merge their begun work into one project. Thus, the other project - *MsPiggit* - is no longer maintained and source code resides for reference. Source is still available on [GitHub](https://github.com/antis81/MsPiggit).
