# GIT ASSIGNMENT #5

**Name:** Natalia  
**Date:** 20/11/2025  
**Course:** Basic Toolkit for Bioinformatics Research, Exercises  
**Group number:** 1  
**Session:** 5  

## **What is git?**  
**"Git is a version-control tool that tracks changes made to the files and directories in a project."**  

## Basic Git commands
- git clone:
    + Clones a remote repository to your local machine.  
      (Downloads the full project history to allow working locally.)
    + example:
        `git clone git@github.com:Tincanot/Assignment-5.git`
- git init:  
    + Initializes repository  .
      (Creates a new, empty, local repository.)
- git status:  
    + Shows modified and staged files.  
        (Checks the current state of the repository. Shows which files have been modified, which are ready for commit, and which aren't tracked by Git.)
- git add:  
    + Select files that will be committed.  
    + example:
      `git add README.md`
- git commit:  
    + Creates a "snapshot" of your files.  
      (It makes Git save the earlier added changes permanently in the project history, with an optional note.)
    + example:  `git commit -m "Commit README with basic information"`  
      ("-m" is used to add the message)
      * The note should be simple, to the point and preferably in Present Simple and imperative form.
- git push:
    + Send committed files to remote server (i.e. GitHub).
- git branch:
    + Create new branch.  
       (Used to manage branches in a repository. Branches allow working on different features or fixes independently of the main version of the project.)
    + example: `git branch new_branch_name`
- git checkout:
    + Changes working branch.
    + example: `git checkout branch_name`
- git merge:
    + Merges content of different branches.  
      (Allows combining changes from different branches into one.)
    + example: `git merge name_of_the_other_branch`
      (name_of_the_other_branch – the branch intended to be merged into the "current branch".)
- git pull:
    + Downloads from remote and merges with local.
- git fetch:
    + Downloads info from remote, but does not merge with local.
- git show:
    + Shows the contents of a single commit.





