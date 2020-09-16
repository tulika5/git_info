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
