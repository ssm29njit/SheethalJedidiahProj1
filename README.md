# SheethalJedidiahProj1
Git Collaboration Homework

## GitFlow 
Gitflow is a branching model for Git. 
It is very well suited to collaboration and scaling the development team.

New development (new features, non-emergency bug fixes) are built in feature branches:

Feature branches are branched off of the develop branch, and finished features and fixes are merged back into the develop branch when they’re ready for release
a release branch is created off of develop:


The code in the release branch is deployed onto a suitable test environment, tested,
 and any problems are fixed directly in the release branch. 
This deploy -> test -> fix -> redeploy -> retest cycle continues until you’re happy that 
the release is good enough to release to customers.

When the release is finished, the release branch is merged into master and into develop too, 
to make sure that any changes made in the release branch aren’t accidentally lost by new development.
The master branch tracks released code only. The only commits to master are merges from release 
branches and hotfix branches.

Hotfix branches are used to create emergency fixes
They are branched directly from a tagged release in the master branch, and when finished are 
merged back into both master and develop to make sure that the hotfix isn’t accidentally 
lost when the next regular release occurs.


## Git Repository

 Repository is like a folder for your project. Your project's repository contains all 
 of your project's files and stores each file's revision history.
 You can also discuss and manage your project's work within the repository.
 ![repo](https://user-images.githubusercontent.com/71558799/93670753-b0084c80-fa6b-11ea-9a9b-3163ec5e7457.png)
 
 ## Git Clone
 To clone a repository means to duplicate and download 
 everything in the repository.
 <img width="437" alt="clone" src="https://user-images.githubusercontent.com/13598741/93671087-c2ab7180-fabd-11ea-886f-1b08154c1d77.PNG">
 

 
