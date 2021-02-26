# These are my notes class 3

## Version Control

-Local Version Control entails one database on your hard drive for your files.
-Centrilized Version Control is a single server storing all your changes and file versions to be accessed by other clients.
-Distributed Version Control allows clients to create mirrored repositories in the case of file corruption.

## What is Git?

-Git is a DVCS that stores data in a file system made up of stapshots of your project.
-Git relies on local operations because most necessary information can be found in local resources.
-Git always detects file corruption or loss of information in transit.
-Git minimizes the possibility of irreversible damage to files such as accidentally lost data.
-Files in Git can reside in a committed, motified, or staged state. __Committed__ means the data is securely stored in a local database.  __Modified__ means the file has been changed but not committed. __Staged__ means the file's changed version to be committed in the next snapshot is flagged.
-Git includes Graphical User Interface (GUI) tools.

## The Life Cycle of a File Status

-After you edit a file, Git flags it as modified because of changes made after the previous commit. You stage the modified file before committing the staged changes.
-Stashing changes is for when you are not ready to commit but do not want to lose the files.

## Repositories

-A repository on Git is a version of a project residing online or in a network.
[<== back](README.md)