# CMPG323-Overview-30151007
 The read.me notes for my github project guide.

## Repositories
I will be creating a new repository for each project. from project 2 - project 5.
I will be creating a new repository for each project throught.

* project 1 ( for project 1 which is this one I have already created its repository )
* project 2
* project 3
* project 4
* project 5


All this projects will be having their own repositories, there will be a total of five five repository aligned to each project.

## Diagram




## Branching strategies
In my project I will be using Git flow branching on each project throught,

The good thing I about git flow branching strategy is that:
The various types of branches make it easy and intuitive to organize my work.
The systematic development process allows for efficient testing.
The use of release branches will allow me to easily and continuously support multiple versions of production code.

This branching strategy consists of the following branches:
Master 
Develop
Feature- to develop new features that branches off the develop branch 
Release- help prepare a new production release; usually branched from the develop branch and must be merged back to both develop and master
Hotfix- also helps prepare for a release but unlike release branches, hotfix branches arise from a bug that has been discovered and must be resolved; it enables developers to keep working on their own changes on the develop branch while the bug is being fixed.

## Uses of .gitignore file within each project

gitignore file tells Git which files to ignore when committing your project to the GitHub repository. gitignore is located in the root directory of your repo

Each of my project will  be ignoring the  following files using the  .gitignore file

Log files
Files with API keys/secrets, credentials, or sensitive information
Useless system files like .DS_Store on macOS
Generated files like dist folders
Dependencies which can be downloaded from a package manager

## Storage of Credentials and sensitive information
 I will be storing all my sensitive informations and credentials using encryptions so that no unauthorised users can't access them.
 I will also use the  git-credential-store to store my passwords unencrypted on the disk.
 If I commit sensitive data, such as a password or SSH key into a Git repository, I will  remove it from the history. To entirely remove  that sensitive  or unwanted files from a repository's history I Will use either the git filter-repo tool or the BFG Repo-Cleaner open source tool.
Most credentials will be stored using the Git Credential Manager (GCM) is another way to store your credentials securely and connect to GitHub over HTTPS. 
 
 ## References
 [Branching strategies](https://www.flagship.io/git-branching-strategies/)
 
 [Sensitive info](https://docs.github.com/en/actions/security-guides/encrypted-secrets)
