# Git Tutorial

## Version Control 
 - Version control is a system that allows you to revist various versions of the file by recording the changes. You could also track any changes and compare them.
 - A Local Version Control is a system that was created a very long time ago that entails one database on your hard disk. 
 - Centralized Version Control **CVCS** entails a single server storing all changes that have happened between all clients. 
 - Distrubuted version control **DVCS** is a system where any major vunleberability happens to the CVS or distrubtion of the file will be backed up. DVCS allows the client to create mirrored repos

 ## Git in a nutshell

 ### Snapshots
 - Git is a DVCS which stores our data in filing system made of diffrent snapshots of. Which allows us to work on an online server even if we lost our data on local computer 
 
 ### Tracking changes 
 - Any changes that have been apploed to any file can be tracked by Git, and it will always track any corrupted file or loss of information. 

 ### Loss Of Data
 - Git is set up to help you minimize the chance of having irreversable damage on the file. 

 ### States
 Files on Git can reside in three maines states committed, modified and staged.

 Check out the graph as it explains the [states](https://blog.udemy.com/wp-content/uploads/2015/08/image066.png)

 # History Of Git
. Git traces to its roots to open the source software project linux kernal. THis project began by BitKeeper in 2002. Git is a revamped for people to start using this DVCS in order to save their work and using minimal effort. 

## Downloading Git on Mac
- Terminal is the simplest method of install Git on your mac
- Git Website you can follow this link to download [GitHub](http://git-scm.com/download/mac)

## Options for Git
- Git included Graphical user interface tools, which can also utlize third parth tools created for these platforms.[GitHubtools](https://git-scm.com/downloads/guis)
- Inital Customization after downloading Git you should customize it by usning the follow setup

    - git config --global user.name "Jane Smith"

    - git config --global user.email "example@email.co 

- Default Text Editor where Git will use the systems default editor. And to configure a diffrent text you can use :

$ git config --global core.editor emacs

- Checking your settings using the git config -- list command 
- For more git commands you can type git command --help

## Setting Up a Git Repo
There are some steps that are needed 
    1. Importing an existing project into git following these steps 
        - $ cd test (cd = change directory)
        - $ git init
        - $ git add *.c
        - $ git add LICENSE
        - $ git commit -m “any message here”
    2. Cloning is also a way to create a copy of an existing git repo from a server as follows :$ git clone https://github.com/test
        By cloning a file you have copied all of its versions, this commands leads to the creating of a directory called a "test". To clone a repo int o a directory with another name use the following command: $ git clone https://github.com/test mydirectory

## Work Flow 
    - [Local Repository structure](https://blog.udemy.com/wp-content/uploads/2015/08/image036.png)

## Saving Changes
    - There are two tupes of files track and untracked if you want to track the files use this command git add . to track untracked files. 

## The Life Cycle of file Status 
    - Here is a link to show you the [lifecycle](https://blog.udemy.com/wp-content/uploads/2015/08/image006.png) of files

## Check file status
    - To check file status use the $ git Status 

## Tracking and Staging a new file
    - Single File tracking is git add filename
    - All Files tracking is $ git add *
Once these codes have been used use the commit

## Committing a File 
1.After creating a file and you wanna *save* you wanna commit and use the follow command $ git commit -m “made change x,y,z”
1.After that command is put you use $ git commit -a
Once finished you want to push your items toe Git using the following $ git push origin master

