# gitCommands
useul git commands

To create a new branch
git checkout -b branchname

To switch back 
git checkout master

---
To add git ignore to an existing repository:

Commit all pending changes, then run this command:

git rm -r --cached .
This removes everything from the index, then just run:

git add .
Commit it:

git commit -m ".gitignore is now working"
