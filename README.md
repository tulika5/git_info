# hello-world
Created this repository just for learning git.

GITHUB: code hosting platform for version control and collaboration
Repository: organize whole project
created new repository: hello-world
initialized with README file i.e. file with description of the project
.gitignore file=file with list of files to ignore while storing in repo

by default master branch created
create feature or bugfix branches out of it-commit and push your changes.
create pull request and merge to master


GIT COMMANDS:
1. cloning and pulling a repo=
git config --global user.name "tulika5"
git config --global user.email "tulikabhushan3@gmail.com"
git clone https://github.com/tulika5/scalaPractice.git
git init
git pull

2. create a new repository on the command line=
echo "# scalaPractice" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M master
git remote add origin https://github.com/tulika5/scalaPractice.git
git push -u origin master

3.  push an existing repository from the command line=
git remote add origin https://github.com/tulika5/scalaPractice.git
git branch -M master
git push -u origin master

ques. what is a git repository?
ans: Git repository refers to a place where all the Git files are stored. These files can either be stored on the local repository or on the remote repository.
*server: remote repository
* every user: local repository ; so, u pull changes from remote, make ur changes and push ur code
so, this is distributed version-control system

ques. what is version control system?
: 1. record all changes to code so that any previous version can be restored and
2. all coders get the latest version to work with.

ques. what is diff. between git and github?
: git is version control system. 
github is the git repository hosting service.
other similar tech is bitbucket

ques. . How can you initialize a repository in Git?
If you want to initialize an empty repository to a directory in Git, you need to enter the git init command. 
After this command, a hidden .git folder will appear in the folder. 

ques. Explain the git push command.
The Git push command is used to push the content in a local repository to a remote repository. After a local repository has been modified, a push is executed to share the modifications with remote team members.

ques. Explain the git pull command.
Git pull is used to fetch and merge changes from the remote repository to the local repository. Git pull is a combination of two commands: git fetch; followed by git merge.

ques.What is a merge conflict in Git?
A merge conflict is an event that takes place when Git is unable to resolve differences in code between the two commits automatically. 
Git is able to automatically merge the changes only if the commits are on different lines or branches.

ques. What is the process to revert a commit that has already been pushed and made public?
There are two processes through which you can revert a commit:
1. Remove or fix the bad file in a new commit and push it to the remote repository. Then commit it to the remote repository using:
git commit –m “commit message”
2. Create a new commit to undo all the changes that were made in the bad commit. Use the following command:
git revert <commit id>
  
ques.  What is Git stash?
Let’s say you're a developer and you want to switch branches to work on something else. The issue is you don’t want to make commits in uncompleted work, so you just want to get back to this point later. The solution here is the Git stash. 
Git stash takes your modified tracked files and saves it on a stack of unfinished changes that you can reapply at any time. To go back to the work you can use the stash pop.

ques.What is the difference between git merge and git rebase?
To incorporate new commits into your feature branch, you use merge
1.Creates an extra merge commit every time you need to incorporate changes
2.Pollutes your feature branch history
As an alternative to merging, you can rebase the feature branch into master.
1.Incorporates all the new commits in the master branch
2. Rewrites the project history by creating brand new commits for each commit in the original branch
