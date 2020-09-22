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

![image](https://user-images.githubusercontent.com/13598741/93943986-48931b00-fd51-11ea-8c6c-ae923f73ed25.png)

<h2  align="center"><img src="https://user-images.githubusercontent.com/5679180/79618120-0daffb80-80be-11ea-819e-d2b0fa904d07.gif" width="27px"> Reach Us On</h2>
<p align="center">
    <a target="_blank"href="https://www.linkedin.com/in/sheethal-mathew-4579a0a5/"><img src="https://img.shields.io/badge/Sheethal linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" /></a>&nbsp;&nbsp;&nbsp;&nbsp;
  <a target="_blank"href="https://www.linkedin.com/in/jedidiahjohn/"><img src="https://img.shields.io/badge/Jedidiah linkedin-%231DA1F2.svg?&style=for-the-badge&logo=linkedin&logoColor=white" /></a>&nbsp;&nbsp;&nbsp;&nbsp;
</p>
