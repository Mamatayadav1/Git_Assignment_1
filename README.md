# Git Assignment 1

## Step 1: Creating a New Folder
```powershell
mkdir Git_Assignment_1
cd Git_Assignment_1
```

**Directory Structure:**
```
Directory: C:\Users\HP

Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----         3/31/2025   9:29 PM                Git_Assignment_1
```

## Step 2: Creating Required Files
```powershell
New-Item Code.txt, Log.txt, Output.txt -ItemType File
```

**Created Files:**
```
Directory: C:\Users\HP\Git_Assignment_1

Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----         3/31/2025   9:29 PM              0 Code.txt
-a----         3/31/2025   9:29 PM              0 Log.txt
-a----         3/31/2025   9:29 PM              0 Output.txt
```

## Step 3: Initializing Git Repository
```powershell
git init
```
```
Initialized empty Git repository in C:/Users/HP/Git_Assignment_1/.git/
```

## Step 4: Staging Code.txt and Output.txt
```powershell
git add .\Code.txt .\Output.txt
```

## Step 5: Committing the Staged Files
```powershell
git commit -m "Added Code.txt and Output.txt"
```
```
[master (root-commit) a5128f0] Added Code.txt and Output.txt
 2 files changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Code.txt
 create mode 100644 Output.txt
```

## Step 6: Linking Local Repo to GitHub
```powershell
git remote add origin https://github.com/Mamatayadav1/Git_Assignment_1.git
```

## Step 7: Verifying the Remote Repository
```powershell
git remote -v
```
```
origin  https://github.com/Mamatayadav1/Git_Assignment_1.git (fetch)
origin  https://github.com/Mamatayadav1/Git_Assignment_1.git (push)
```

## Step 8: Renaming Branch to Main
```powershell
git branch -M main
```

## Step 9: Pushing the Changes to GitHub
```powershell
git push -u origin main
```
```
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 240 bytes | 120.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/Mamatayadav1/Git_Assignment_1.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.
```
