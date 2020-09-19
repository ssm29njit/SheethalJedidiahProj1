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
 
 ## Git Fork
 A fork is a personal copy of another user's repository that lives on your 
 account. Forks allow you to freely make changes to a project without 
 affecting the original upstream repository. You can also open a pull request
  in the upstream repository and keep your fork synced with the latest 
  changes since both repositories are still connected.
  <img width="582" alt="Fork" src="https://user-images.githubusercontent.com/13598741/93671169-52512000-fabe-11ea-884c-4cbaa88dfed3.PNG">

## Git Branch
A branch is a parallel version of a repository. It is contained within the repository,
 but does not affect the primary or master branch allowing you to work freely without 
 disrupting the "live" version. When you've made the changes you want to make, you can merge
  your branch back into the master branch to publish your changes.
  ![branch](https://user-images.githubusercontent.com/71558799/93671285-a97bd400-fa6f-11ea-9551-d72191af203c.png)


## Git Commit
A commit, or "revision", is an individual change to a file (or set of files). When you 
make a commit to save your work, Git creates a unique ID (a.k.a. the "SHA" or "hash") that 
allows you to keep record of the specific changes commited along with who made them and when. 
Commits usually contain a commit message which is a brief description of what changes were made.

![commit1](https://user-images.githubusercontent.com/71558799/93671440-03c96480-fa71-11ea-9f42-c8b82bf3895d.png)
![commit2](https://user-images.githubusercontent.com/71558799/93671444-088e1880-fa71-11ea-8435-0935b7886666.png)
![commit3](https://user-images.githubusercontent.com/71558799/93671449-0e83f980-fa71-11ea-8651-4d93a2374ea1.png)

## Git Merge
Merging takes the changes from one branch (in the same repository or from a fork), and applies 
them into another. This often happens as a "pull request" (which can be thought of as a request to merge),
 or via the command line. A merge can be done through a pull request via the GitHub.com web interface 
 if there are no conflicting changes, or can always be done via the command line.
![merge](https://user-images.githubusercontent.com/71558799/93671485-6c184600-fa71-11ea-9175-e668d37d9415.png)


## Git Checkout
A "checkout" is the act of switching between different versions of a target entity. 
The git checkout command operates upon three distinct entities: files, commits, and branches. 
In addition to the definition of "checkout" the phrase "checking out" 
is commonly used to imply the act of executing the git checkout command.
The git checkout command lets you navigate between the branches created by git branch. 
Checking out a branch updates the files in the working directory to match the version stored 
in that branch, and it tells Git to record all new commits on that branch. 
Think of it as a way to select which line of development you’re working on.
![git-checkout](https://user-images.githubusercontent.com/13598741/93671696-d60d0b80-fac2-11ea-967b-c8dbe510f3e9.png)


## Git Push
Use git push to push commits made on your local branch to a remote repository.
The git push command takes two arguments:

A remote name, for example, origin
A branch name, for example, master
For example:

git push  <REMOTENAME> <BRANCHNAME> 
As an example, you usually run git push origin master to push your 
local changes to your online repository.

## Git Pull
git pull updates your current local working branch, and all of the remote tracking branches. 
It's a good idea to run git pull regularly on the branches you are working on locally.

Without git pull, (or the effect of it,) your local branch wouldn't have any of the updates that are present 
on the remote.
A git pull is one of the 4 remote operations within Git. Without running git pull, 
your local repository will never be updated with changes from the remote. git pull should 
be used every day you interact with a repository with a remote, at the minimum. 
That's why git pull is one of the most used Git commands.

![git push and pull](https://user-images.githubusercontent.com/13598741/93671810-c641f700-fac3-11ea-953d-5e7e5351089f.jpg)




 
