# exp2
# practice2
mkdir new2
cd new2
pwd
git init
ls -la

vi fil.txt
# hello world
:wq

git add fil.txt
git commit -m "file in master"

git branch feature
git checkout feature

vi fil2.txt
ls -la

vi fil2.txt
git add fil2.txt
git commit -m "file2 in feature"

git status
ls -la

git checkout master
ls -la

git merge feature
ls -la
git log

git checkout feature
git log

git checkout master

vi new1.txt
# Hello welcome to git lab
:wq

git add new1.txt
git commit -m "new1 in master"

cat new1.txt

git checkout feature
vi new1.txt
# Hello welcome to github
:wq

git add new1.txt
git commit -m "new1 in feature"

cat new1.txt

git merge master
cat new1.txt
git status
