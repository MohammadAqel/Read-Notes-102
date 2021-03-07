*We're talking about Git*

*In order to explain Git, we have to first explain various aspects of Version Control*

### Version Control
Version Control is a system that allows you to revisit various versions of a file or set of files by recording changes. Through version control, one can revert a file or project to a previous version, track modifications and modifying individuals, and compare changes. By utilizing a Version Control System (VCS), mistakes with files can easily be rectified.

### So, what is Git?
Git is a DVCS that stores data in a file system made up of snapshots. Each time you save a changed version of your project — called commit — Git creates a snapshot of the file and stores a reference to it. If the file has not changed, Git only stores a reference to the already-stored identical version of it.

## Features of Git :
1. Local Operation:

Git mostly relies on local operations because most necessary information can be found in local resources. This allows for process expediency because a project’s history resides on the local disk, eliminating the need to fetch history information from the server, and allowing one to continue work on a project even when not online or on a VPN.


2. Tracking Changes

Every single change applied to any file or directory is tracked by Git. And, as the gatekeeper, Git will always detect file corruption or loss of information in transit.


3. Loss of Data

Git is set up to greatly minimize the possibility of irreversible damage to files, such as accidentally lost data. Git makes it extremely difficult for a snapshot of your file that is committed to be lost.

## -Files in Git can reside in three main states: committed, modified and staged:


1. Committed

Data is securely stored in a local database.

2. Modified

File has been changed but not committed to the database.

3. Staged

Flagged a file’s changed version to be committed in the next snapshot.

## - Graphical Clients

Git includes inherent Graphical User Interface (GUI) tools. However, users can also utilize third-party tools created for particular platforms.

## - Initial Customization

After making sure Git has been installed, you should perform some customization steps, which should only need to be completed once on any machine. To change settings, you can repeat these steps.

## - Configuration of Variables

An inherent Git tool called git config allows the setting of configuration variables that control aspects of Git’s operation and look.


## - Post-download steps of Git :

1. Identity Setting

After installing Git, users should immediately set the user name and email address, which will be used for every Git commit.

- By using the –global option, these Git settings apply to anything on the system. To use different identity settings for a specific project, change the working directory to the desired local Git repository and repeat the steps above without using –global.

2. Default Text Editor

Without configuration of a default text editor, Git will use the system’s default editor–most likely Vim. To configure a different text editor, such as Emacs.

3. Check Settings

To check settings, use the git config --list command.

4. Getting Help

## - There are three ways to get more information on a particular command, by accessing the manual:

1. git help command

2. git command --help

3. man git-command

////////////////////