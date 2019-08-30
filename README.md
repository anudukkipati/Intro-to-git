GIT: Git thinks of its data more like a series of snapshots of a miniature filesystem. With Git, every time you commit, or save the state of your project, Git basically takes a picture of what all your files look like at that moment and stores a reference to that snapshot.
THREE STAGES:
   Git has three main states that your files can reside in: modified, staged, and committed:

•	Modified means that you have changed the file but have not committed it to your database yet.

•	Staged means that you have marked a modified file in its current version to go into your next commit snapshot.

•	Committed means that the data is safely stored in your local database.

This leads us to the three main sections of a Git project: the working tree, the staging area, and the Git directory.
•	The working tree is a single checkout of one version of the project. These files are pulled out of the compressed database in the Git directory and placed on disk for you to use or modify.

•	The staging area is a file, generally contained in your Git directory, that stores information about what will go into your next commit. Its technical name in Git parlance is the “index”, but the phrase “staging area” works just as well.

•	The Git directory is where Git stores the metadata and object database for your project. This is the most important part of Git, and it is what is copied when you clone a repository from another computer.
Source:https://git-scm.com/book/en/v2/Getting-Started-What-is-Git%3F
