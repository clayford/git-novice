---
layout: page
title: Version Control with Git
subtitle: Reference
---

## Sites of interest

*	[I broke git while trying to...](http://ibrokegit.com/)
*	[Most common git screwups/questions and solutions](http://41j.com/blog/2015/02/common-git-screwupsquestions-solutions/)
*	[nano basics](https://wiki.gentoo.org/wiki/Nano/Basics_Guide)


## [Setting Up Git](01-setup.html)

*   Use `git config` to configure
    a user name, email address, editor, and other preferences once per machine.

## [Creating a Repository](02-create.html)

*   `git init` initializes a repository.

## [Tracking Changes](03-changes.html)

*   `git status` shows the status of a repository.
*   Files can be stored in a project's working directory (which users see),
    the staging area (where the next commit is being built up)
    and the local repository (where revisions are permanently recorded).
*   `git add` puts files in the staging area.
*   `git commit` saves the revisions in the staging area to the local repository.
*   Always write a log message when committing changes.

## [Exploring History](04-history.html)

*   `git diff` displays differences between revisions.
*   `git checkout` recovers old versions of files.

## [Ignoring Things](05-ignore.html)

*   The `.gitignore` file tells Git what files to ignore.

## [Collaborating](06-collab.html)

*   A local Git repository can be connected to one or more remote repositories.
*   Use the HTTPS protocol to connect to remote repositories until you have learned how to set up SSH.
*   `git push` copies changes from a local repository to a remote repository.
*   `git pull` copies changes from a remote repository to a local repository.
*   `git clone` copies a remote repository to create a local repository
    with a remote called `origin` automatically set up.

## [Conflicts](07-conflict.html)

*   Conflicts occur when two or more people change the same file(s) at the same time.
*   The version control system does not allow people to blindly overwrite each other's changes.
    Instead, it highlights conflicts so that they can be resolved.


## Glossary

change set
:   A group of changes to one or more files
    that are [committed](#commit) to a [version control](#version-control) [repository](#repository)
    in a single operation.

commit
:   To record the current state of a set of files (a [change set](#changeset))
    in a [version control](#version-control) [repository](#repository).
    If a commit contains changes to multiple files,
    all of the changes are recorded together.

conflict
:   A change made by one user of a [version control system](#version-control)
    that is incompatible with changes made by other users.
    Helping users [resolve](#resolve) conflicts
    is one of version control's major tasks.

HTTP
:   The Hypertext Transfer [Protocol](#protocol) used for sharing web pages and other data
    on the World Wide Web.

infective license
:   A license such as the [GPL](http://opensource.org/licenses/GPL-3.0)
    that compels people who incorporate material into their own work
    to place similar sharing requirements on it.

merge
:   (a repository):
    To reconcile two sets of changes to a [repository](#repository).

protocol
:   A set of rules that define how one computer communicates with another.
    Common protocols on the Internet include [HTTP](#http) and [SSH](#ssh).

remote
:   A version control [repository](#repository) other than the current one
    that the current one is somehow connected to or mirroring.

repository
:   A storage area where a [version control](#version-control) system
    stores old [revisions](#revision) of files and information about who changed what, when.

resolve
:   To eliminate the [conflicts](#conflict) between two or more incompatible changes to a file or set of files
    being managed by a [version control](#version-control) system.

revision
:   A recorded state of a [version control](#version-control) [repository](#repository).

SSH
:   The Secure Shell [protocol](#protocol) used for secure communication between computers.

timestamp
:   A record of when a particular event occurred.

version control
:   A tool for managing changes to a set of files.
    Each set of changes creates a new [revision](#revision) of the files;
    the version control system allows users to recover old revisions reliably,
    and helps manage conflicting changes made by different users.
