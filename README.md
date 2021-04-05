 1  Github commands
 
 2  git init
 
 3  git remote add origin https://github.com/vaitheeshwaran/simple.git
 
 4  git status
 
 5  git push -u origin master
 
 6  git add README.md
 
 7  vi README.md
 
 8  git add README.md (OR) git add . # To add all changes you have made
 
 9  git commit -m "first commit" (OR) git commit -a -m "commit msg" # To appen all your addfiles
 
 10  git push -u origin master
 
 11  vi README.md
 
 12  git commit -m "first commit"
 
 13  git add README.md
 
 14  git commit -m "second commit"
 
 15  git remote add origin https://github.com/vaitheeshwaran/simple.git
 
 16  git push -u origin master
 
 17  git config --global user.name "vaitheeshwaran"
 
 18  git config --global user.email "vaitheeshhh@gmail.com"
 
 19  vi README.md
 
 20  git add README.md
 
 21  git commit -m "second commit"
 
 22  git push -u origin master

=============================

To remove the file from the Git repository and the filesystem

git rm file1.txt
git commit -m "remove file1.txt"

To remove the file only from the Git repository and not remove it from the filesystem

git rm --cached file1.txt
git commit -m "remove file1.txt"

============================

To move file from one directory to another directory in git

git mv source/hello.html Destination
git status
git commit -m "changes msg"
git push origin master

============================
To change the directory name 

git mv oldfolder newfolder

Note: Don't need to create already newfolder 

===========================

Modified in existing commit
