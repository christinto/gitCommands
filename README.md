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
Create a .gitignore file, so to do that, you just create any blank .txt file.
Then you have to change its name writing the following line on the cmd (where git.txt is the name of the file you've just created):

rename git.txt .gitignore VIA WINDOWS STANDARD CMD LINE TERMINAL AS ADMIN :) 
Then you can open the file and write all the untracked files you want to ignore for good.
