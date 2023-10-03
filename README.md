# FSDLAB

## Git Commands 

### Creating a Local Repository:
```
swarshah@Swars-Mac VisionPro % git init
Reinitialized existing Git repository in /Users/swarshah/Desktop/Programming/VisionPro/.git/
```
### Adding and Commiting Changes:
```
swarshah@Swars-Mac VisionPro % git add .
swarshah@Swars-Mac VisionPro % git commit -m "first commit" 
[main (root-commit) 76c0790] first commit
 31 files changed, 1656 insertions(+)
 create mode 100644 .DS_Store
 create mode 100644 Apple vision canvas images/Vision00001.png
 create mode 100644 Apple vision canvas images/Vision00002.png
 create mode 100644 Apple vision canvas images/Vision00003.png
 create mode 100644 Apple vision canvas images/Vision00004.png
 create mode 100644 Apple vision canvas images/Vision00005.png
 create mode 100644 Apple vision canvas images/Vision00006.png
 create mode 100644 Apple vision canvas images/Vision00007.png
 create mode 100644 Apple vision canvas images/Vision00008.png
 create mode 100644 Apple vision canvas images/Vision00009.png
 create mode 100644 Apple vision canvas images/Vision00010.png
 create mode 100644 Apple vision canvas images/Vision00011.png
 create mode 100644 Apple vision canvas images/Vision00012.png
 create mode 100644 Apple vision canvas images/Vision00013.png
 create mode 100644 Apple vision canvas images/Vision00014.png
 create mode 100644 Apple vision canvas images/Vision00015.png
 create mode 100644 Apple vision canvas images/Vision00016.png
 create mode 100644 Apple vision canvas images/Vision00017.png
 create mode 100644 Apple vision canvas images/Vision00018.png
 create mode 100644 Apple vision canvas images/Vision00019.png
 create mode 100644 Apple vision canvas images/Vision00020.png
 create mode 100644 Apple vision canvas images/Vision00021.png
 create mode 100644 Apple vision canvas images/Vision00022.png
 create mode 100644 Apple vision canvas images/Vision00023.png
 create mode 100644 Apple vision canvas images/Vision00024.png
 create mode 100644 Apple vision canvas images/Vision00025.png
 create mode 100644 Apple vision image.png
 create mode 100644 index.html
 create mode 100644 logo.png
 create mode 100644 script.js
 create mode 100644 style.css
```
### Linked Local Repository to Remote Repository:
```
swarshah@Swars-Mac VisionPro % git branch -M main
swarshah@Swars-Mac VisionPro % git remote add origin https://github.com/swarshah09/FSDLAB.git
```
### Push Changes to Remote Repository:
```
swarshah@Swars-Mac VisionPro % git push -u origin main
Enumerating objects: 31, done.
Counting objects: 100% (31/31), done.
Delta compression using up to 8 threads
Compressing objects: 100% (31/31), done.
Writing objects: 100% (31/31), 9.81 MiB | 5.67 MiB/s, done.
Total 31 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/swarshah09/FSDLAB.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.
```

### Pull Changes from Remote Repository:
```
git pull origin master
```
### Create and Manage Branches:
```
To create a new branch, use:
git checkout -b new-branch-name

To switch between branches:
git checkout branch-name

To merge branches:
git merge branch-name
```
