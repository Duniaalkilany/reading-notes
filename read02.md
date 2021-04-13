 # Git Tutorial: A Comprehensive Guide
 #### In order to explain Git, we have to first explain various aspects of Version Control :
 ## What is Version Control ?
 ### Version Control is a system that allows you to revisit various versions of a file or set of files by recording changes. Through version control, one can revert a file or project to a previous version, track modifications and modifying individuals, and compare changes. By utilizing a Version Control System (VCS), mistakes with files can easily be rectified.
 ## types of Version Control :
 1. Local Version Control
 2. Centralized Version Control
 3. Distributed Version Control

 # So, what is Git?
 - Snapshots : it is a DVCS that stores data in a file system made up of snapshots. Each time you save a changed version of your project — called commit — Git creates a snapshot of the file and stores a reference to it. If the file has not changed, Git only stores a reference to the already-stored identical version of it.
 - Local Operations : Git mostly relies on local operations because most necessary information can be found in local resources. This allows for process expediency because a project’s history resides on the local disk, eliminating the need to fetch history information from the server, and allowing one to continue work on a project even when not online or on a VPN.    
 - Tracking Changes : Every single change applied to any file or directory is tracked by Git. And, as the gatekeeper, Git will always detect file corruption or loss of information in transit.
 - Loss of Data : Git is set up to greatly minimize the possibility of irreversible damage to files, such as accidentally lost data. Git makes it extremely difficult for a snapshot of your file that is committed to be lost.
 - States : Files in Git can reside in three main states:
 
       1. Committed 
       2. Modified
       3. staged.
![gitstatus](https://coderz.ca/progit/images/areas.png) 

# History of Git : Since its inception in 2005, Git has become one of the most utilized Version Control Systems in the world.
- Git traces its roots to the open source software project Linux kernel. Developers of this project began using a DVCS called BitKeeper in 2002.
-  In 2005, many of these developers stopped using this DVCS due to tension between the Linux kernel community and the company behind BitKeeper’s and the eventual revocation of the DVCS’ gratis status.
-  Subsequently, Linus Torvalds, the chief architect of the Linux kernel, began creating Git. With the intention of creating a DVCS with a workflow design similar to that of BitKeeper, which was also fast
-  Git allowed for non-linear development via multiple branches, could support large projects, possessed strong mechanisms preventing corruption, and had a simple design.

# Getting Started

### Download Git
##### Git can be installed in three ways:
1. Install as a package
2. Install via another installer
3. Download and compile the source code.

##### you can use these links in order to download Git :

1. Mac OS X :
[mac](http://git-scm.com/download/mac)
2. Windows :
[windows](http://git-scm.com/download/win)
3. Linux :
[Linux](http://git-scm.com/download/linux)

### Graphical Clients 
### you can access a variety of GUI clients for Mac, Windows, and Linux via the following link: [git-scm](https://git-scm.com/downloads/guis)


### Initial Customization
### After making sure Git has been installed, you should perform some customization steps, which should only need to be completed once on any machine. To change settings, you can repeat these steps.
1. Configuration of Variables
2. Identity Setting


### Default Text Editor
### To configure a different text editor, such as Emacs, type the following into your Terminal or Command Line:
##### $ git config --global core.editor emacs


### Check Settings
### To check settings, use the Command :
##### git config --list 

### Getting Help

## Workflow
### The local Git repository has three components:
1. Working Directory: The actual files reside here.
2. Index: The area used for staging
3. Head: Points to the most recent commit

![status](https://image.slidesharecdn.com/anintroductiontogit-140124042938-phpapp02/95/an-introduction-to-git-9-638.jpg?cb=1391574227)



