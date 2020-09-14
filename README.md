# hello-world
Created this repository just for learning github.

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

