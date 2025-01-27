## What is Git?

Git is a free and open source distributed version control system designed to handle everything from small to very large projects with speed and efficiency.<br>

Git is easy to learn and has a tiny footprint with lightning fast performance. It outclasses SCM tools like Subversion, CVS, Perforce, and ClearCase with features like cheap local branching, convenient staging areas, and multiple workflows.<br>

### Types of Version Control Sysems

Version control systems are tools that help a software team manage changes to source code over time.<br>

For almost all software projects, the source code is like the crown jewels - a precious asset whose value must be protected.<br> 

VCS are sometimes known as SCM (Source Code Management) tool.<br>

Most widely used modern version control system in the world today is Git. Git is a mature, actively maintained open source tool originally developed in 2005 by Linus Torvalds, the famous creator of the Linux operating system kernel.<br> 

<b>Two types Version Control systems</b><br>
1) Centrailized Version controlling<br>
2) Distributed Version controlling<br>

Git is Distributed Version controlling.<br>

### Centralized Version Control System

Centralized Version Control is a version control system using server/client model and server contains all the history of source code.

### Distributed Version Control System

One of the nicest features of any Distributed SCM, Git included, is that it's distributed. This means that instead of doing a "checkout" of the current tip of the source code, you do a "clone" of the entire repository.

### What is gitbash ?

Git Bash is an application for Microsoft Windows environments which provides an emulation layer for a Git command line experience. ... A shell is a terminal application used to interface with an operating system through written commands. Bash is a popular default shell on Linux and macOS.<br>

<b>How to configure username and email for git?</b><br>

$ git init<br>
$ git config - -global   user.name "user name"<br>
$ git config - -global   user.email  "user_mail@gmail.com"<br>

### Branching and Merging

This feature is provided in git, so that developers can create code related to different functionalities  on seprate branches.<br>
This helps the development team in creating the code in an uncluttered way.<br>
Later this code can be merged with master branch.<br>
Default branch of git is "Master"<br>

The Git feature that really makes it stand apart from nearly every other SCM out there is its branching model.<br>

Git allows and encourages you to have multiple local branches that can be entirely independent of each other. The creation, merging, and deletion of those lines of development takes seconds.<br>

<b>This means that you can do things like:</b><br>

<b>Frictionless Context Switching.</b> Create a branch to try out an idea, commit a few times, switch back to where you branched from, apply a patch, switch back to where you are experimenting, and merge it in.<br>

<b>Role-Based Codelines.</b> Have a branch that always contains only what goes to production, another that you merge work into for testing, and several smaller ones for day to day work.<br>

<b>Feature Based Workflow.</b> Create new branches for each new feature you're working on so you can seamlessly switch back and forth between them, then delete each branch when that feature gets merged into your main line.<br>

<b>Disposable Experimentation.</b> Create a branch to experiment in, realize it's not going to work, and just delete it - abandoning the work—with nobody else ever seeing it (even if you've pushed other branches in the meantime).<br>

### Some useful Git commands

<b>git init</b>           ----> to make working directory as git repository<br>
<b>git add filename</b>   ----> to move file to staging area<br>
<b>git add . </b>         ----> to move all files to staging area<br>
<b>git rm  --cached filename or git reset  filename </b> ----> bring file back to untracked section<br>
<b>git commit -m "first commit"</b> ----> to move the files from staging are to local repositary<br>
<b>git log</b>            ----> to see the list of commit<br>
<b>git rebase</b>         ----> the commits from the sub branch are added to the top of the master branch<br>
<b>git stash</b>          ----> this feature is used for leaving unfinished work, in such a way that Git cannot access it and continue  work on some other files<br>
<b>git stash -u</b>       ----> to stash  staged and untracked files<br>
<b>git stash list</b>     ----> to see the list of stashes<br>
<b>git stash pop</b>      ----> to get back the stashed files<br>
<b>git  stash  pop  stash@{stash_number}</b>    ----> to bring the older stash  out<br>
