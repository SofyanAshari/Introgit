## Day 70 Intro Git
# Step One :
git init
ls -a
git status
touch readme.txt
open readme.txt
git add readme.txt
git status
git commit -m "Commit Readme.txt"
git log

# Step Two :
touch file1.txt file2.txt
open file1.txt file2.txt
git add . //this is for add/save all file
git status

# Step Three :
git diff readme.txt

# Step Four :
git checkout readme.txt

# Step Five :
Create Github Account
Login
Create Repository

# Step Six (for github using AUTH login):
git status
git add .
git remote set-url origin https://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@github.com/SofyanAshari/Introgit.git
git remote add origin https://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@github.com/SofyanAshari/Introgit.git
git push origin -u main
