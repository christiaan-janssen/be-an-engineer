---
title: 2 - Basic Tools
type: docs
prev: docs/01-operating-systems
next: docs/basics/webservers
sidebar:
  open: true
---
There are some tools that need to be in your tool box. Here is a non exhaustive list I think you should learn.

## GIT

Git is currently the defacto standard tool for version control. It is used in both development and ops tasks.

### What is version control?

Version control is a system that records changes to a file or set of files over time so that you can recall specific versions later. It is commonly used in software development to manage the source code of a project. The main purposes of version control are:

1. **Tracking Changes**: It keeps a history of modifications to files, which helps in understanding the evolution of the project and identifying when specific changes were made.

2. **Collaboration**: Multiple developers can work on the same project simultaneously without overwriting each other’s work. Changes can be merged, conflicts can be resolved, and contributions from different team members can be integrated smoothly.

3. **Backup and Restore**: It provides a backup mechanism where any previous version of the files can be restored if necessary, protecting against data loss or mistakes.

4. **Branching and Merging**: Developers can create branches to work on new features or bug fixes independently of the main codebase. These branches can later be merged back into the main project.

5. **Audit Trail**: Version control systems maintain a detailed log of who made what changes and when, which can be useful for auditing and accountability.

6. **Code Integration**: Automated tools and continuous integration systems can use version control to automatically build and test the project as new changes are committed.

### Types of Version Control Systems

1. **Local Version Control Systems**: These keep all the versioned files on a local machine. An example is RCS (Revision Control System).

2. **Centralized Version Control Systems (CVCS)**: These have a single central server that contains all the versioned files, and clients check out files from this central place. Examples include CVS (Concurrent Versions System) and Subversion (SVN).

3. **Distributed Version Control Systems (DVCS)**: These allow every user to have a complete copy of the entire repository. This setup improves collaboration and redundancy. Examples include Git, Mercurial, and Bazaar.

### Popular Version Control Systems

- **Git**: The most widely used modern version control system today. It is a distributed system that allows for branching, merging, and full repository history on every user’s local machine.
- **Subversion (SVN)**: A centralized version control system that has been widely used, particularly in enterprise environments.
- **Mercurial**: Another distributed version control system that is known for being easy to use and handle large projects efficiently.

### Basic Concepts and Terminology

- **Repository**: The database where the version control data is stored.
- **Commit**: The act of saving changes to the version control system.
- **Branch**: A separate line of development that diverges from the main codebase.
- **Merge**: Combining changes from different branches.
- **Conflict**: A situation where changes from different branches cannot be automatically merged.
- **Clone**: Creating a copy of a repository.
- **Push/Pull**: Commands to send and receive changes from a remote repository.

In essence, version control is a crucial tool in software development that enhances productivity, collaboration, and the quality of the codebase.

Every thing you need to know about git can be found in the [Git book](https://git-scm.com/book/en/v2). To be effective as an *engineer you need to be able to do basic task with git, at a minimum you need to be able to:

- [clone, commit, merge](https://git-scm.com/book/en/v2/Git-Basics-Getting-a-Git-Repository)
- [Fix your sh*t](https://ohshitgit.com)

## (NEO)Vim

## Docker
