Exercise 1
----------
mkdir Git project one
cd Git project one
git init
New-Item README.mdl
git add .
git commit -m "Initial commit"
git branch -m master main  
git remote add origin https://github.com/your-username/Git project one.git
git push -u origin main
git checkout -b dev
git checkout -b test
git checkout dev
git branch -d test
