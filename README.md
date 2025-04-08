Exercise 1
----------
PS E:\amalitech projects\Git\first-project> git init
Initialized empty Git repository in E:/amalitech projects/Git/first-project/.git/
PS E:\amalitech projects\Git\first-project> echo amalitech >file.txt
PS E:\amalitech projects\Git\first-project> git branch -m master main
PS E:\amalitech projects\Git\first-project> git branch -m main master
PS E:\amalitech projects\Git\first-project> git branch -m master main
PS E:\amalitech projects\Git\first-project> git add .
PS E:\amalitech projects\Git\first-project> git commit -m "initial commit"
[main (root-commit) b0f946e] initial commit      
 2 files changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 file.txt
 create mode 100644 myfile.txt
PS E:\amalitech projects\Git\first-project> git remote add origin https://github.com/muodilo/first-project.git
PS E:\amalitech projects\Git\first-project> git push -u origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (4/4), 296 bytes | 98.00 KiB/s, done.
Total 4 (delta 0), reused 0 (delta 0), pack-reused 0       
To https://github.com/muodilo/first-project.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.
PS E:\amalitech projects\Git\first-project> git checkout -b dev
Switched to a new branch 'dev'
PS E:\amalitech projects\Git\first-project> git checkout -b test
Switched to a new branch 'test'
PS E:\amalitech projects\Git\first-project> git checkout dev
Switched to branch 'dev'
PS E:\amalitech projects\Git\first-project> git branch -d test
Deleted branch test (was b0f946e).
PS E:\amalitech projects\Git\first-project>

exercise 2
----------
