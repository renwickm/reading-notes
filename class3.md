# Class 3 Reading Notes!

## Git Tutorial: A Comprehensive Guide

### **Version Control**

Have you ever been a member of a team, working on a project, collaborating on specific tasks that fit the overall scope of the project, altogether? A Version Control allows teams to do this, virtually. Through this, members can *revert files or projects* to a previous version, *track modifications* and *modifying individuals*, and *compare* changes.

1. Local Verion Control
>One database on your hard disk that stores changes to files
2. Centralized Version Control
>Single server, storing all changes and file versions.  
>Accessed by various clients
3.Distributed Version Control
>Allows clients to create a mirrored repository.  
>Are easily placed on the server to replace any lost information.  
>Encourages collaboration among team members, which enables the use of various simultaneous workflows.

### **Git**

1.Snapshots
>Git creates a snapshot each time you save a file and stores a reference to it.
2.Local Operations
>Allows operations to be processed expediently because it resides on local disks. This eliminates the need to fetch history information from the server.  
>Enforces project work continuity without the use of VPN or being online.
3.Tracking Changes
>All changes applied to a file or directory are tracked by *git*.  
>Detects corrupt of lossed information in transit
4.Loss of Data
>With the way *git* is setup, the possibility of damage to files is minimized.  
>Makes it extremely difficult for a snapshot of your file that is committed to be lost.
5.States
>Three main states the *git* resides in:
>>**Committed**
>>>Securely stored in a local database
>>**Modified**
>>>Changed, but not committed to the database.
>>**Staged**
>>>Flagged a file's changed version to be committed in the next snapshot.

