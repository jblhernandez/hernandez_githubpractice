Summary

Version Control records and manages changes over time of projects being worked on by either one person or a collaboration of people who are most likely going to access and edit the same version of a program or project. Version control is important to use since it can revert back to any state that it has undergone, if in case the developers face problems and would want to go back to an older version that is running and has still no major errors or have little debugging to do. 

Types of Version Control Systems include Local VCSs, which had a simple database wherein all file changes are kept under revision control. Another type, Centralized Version Control Systems, which have a single server containing all the versions of the file and a number of clients that check out the these files from that server. It can be said though that Distributed Version Control Systems beat all the other two. This type of Version Control System fully mirror or clone the repository; a backup of all the data contained.

Git Basics
Even with its evolved state and efficiency, Git has managed to retain its initial qualities of speed, simple design, strong support for non-linear development, full distribution, and a great handler of large projects.

"Git thinks about its data more like a stream of snapshots." This is what Git is basically about. When one commits a project state, Git doesn't just save the file but basically "takes a picture of what all the files look like at that moment and stores a reference to that snapshot."

Local file and resources are the only things needed in most Git operations. Git doesn't need to go out of the server and no information is needed from another computer in your network. It simply needs or use from your local database itself. 

There are three main states of Git: committed, modified, and staged. "Committed means that the data is safely stored in your local database. Modified means that you have changed the file but have not committed it to your database yet. Staged means that you have marked a modified file in its current version to go into your next commit snapshot."

There are also three main sections of a Git project:
1. the Git directory
2. the working directory
3. the staging area
