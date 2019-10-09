# Git Commands
* GitFlow is a collaborative, easily scaled branching model for Git. The general flow is as follows: 
	* New development is created in feature branches.
	* Feature branches are created from the develop branch.
	* A release branch is created from the development branch when new features are ready.
	* After release, the release branch is merged into the master and development branches.
	* The master branch only contains released code. 
	* If there are any issues, a hotfix branch is created and merged into the master and development branches.

### Repository
* A repository holds all the files and revision history for a project on GitHub. Repositories can be individual or shared for collaboration, as well as public or private depending on the project.

![Repository Image](/images/repository.PNG)
### Clone
* The clone command is used to duplicate a repository. Cloning creates a local copy of a repository that can be synced with the remote repository on Github. This can be done through HTTPS, which is the web address of the repository, or using an SSH key, which is an encryption method that allows for authentication of a remote computer and user. 

![Clone Image](/images/clone.PNG)
### Fork
* The fork command creates a copy of a repository. Forking is used to allow the user to manipulate the code without affecting the original project. This is most commonly used to test potential changes to another user’s project, or to use existing code as a base for a new idea. 

![Fork Image](/images/fork.PNG)
### Branch
* Branches are used to create a separate environment for development work within the repository that will not affect other branches. All repositories have one master branch, and can have many different branches.

![Branch Image](/images/branch.PNG)
### Commit
* Commits are all the tracked saved changes made within a branch. Commits show the specific changes, who made them, and when. Comments can be made on commits for organizational purposes. 

![Commit Image](/images/commit.PNG)
### Merge
* Merges allow a user to apply changes from one branch to another. This can happen through a pull request or the command line.

![Merge Image](/images/merge.png)
### Checkout
* The checkout command allows users to navigate between different branches. Checking out a branch updates all files in the working directory to match the version within that branch, as well as record all new commits. 

![Checkout Image](/images/checkout.PNG)
### Push
* Push is used to push commits on a local branch to a remote repository. The push command requires two arguments, a remote name and a branch name.

![Push Image](/images/push.PNG)
### Pull
* Pull is used to get all changes from the remote repository onto the local repository. The pull command combines fetch, which retrieves changes, and merge, which combines the local and remote changes.  

![Pull Image](/images/pull.PNG)
### Remote Add
* The remote add command adds a new remote to the directory of the repository. 

![Remote Add Image](/images/remoteadd.PNG)
### Remote Remove

### Remote Show

### Status
* Status checks the state of the working directory and staging area. It also displays all untracked files, whether they are staged or unstaged. Ideally, it will show the message in the image.

![Status Image](/images/status.PNG)
### Master Branch
* The master branch is the main branch where all changes are ultimately merged into, and is the working version of a project.

![Master Image](/images/master.PNG)
