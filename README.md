## Below are the steps Executed.
\n PS C:\Users\HP> # Step 1: Creating a New folder
PS C:\Users\HP> mkdir Git_Assignment_1


    Directory: C:\Users\HP


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----         3/31/2025   9:29 PM                Git_Assignment_1


PS C:\Users\HP> cd Git_Assignment_1
PS C:\Users\HP\Git_Assignment_1> New-Item Code.txt, Log.txt, Output.txt -ItemType File


    Directory: C:\Users\HP\Git_Assignment_1


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----         3/31/2025   9:29 PM              0 Code.txt
-a----         3/31/2025   9:29 PM              0 Log.txt
-a----         3/31/2025   9:29 PM              0 Output.txt


PS C:\Users\HP\Git_Assignment_1> #Initializing the Git Repositories
PS C:\Users\HP\Git_Assignment_1> git init
Initialized empty Git repository in C:/Users/HP/Git_Assignment_1/.git/
PS C:\Users\HP\Git_Assignment_1> #Stagging Code.txt and Output.txt
PS C:\Users\HP\Git_Assignment_1> git add .\Code.txt .\Output.txt
PS C:\Users\HP\Git_Assignment_1> #Commiting the Stagged files
PS C:\Users\HP\Git_Assignment_1> git commit -m'Added Code.txt and Output.txt'
[master (root-commit) a5128f0] Added Code.txt and Output.txt
 2 files changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Code.txt
 create mode 100644 Output.txt
PS C:\Users\HP\Git_Assignment_1> #Linking local repo to GitHub
PS C:\Users\HP\Git_Assignment_1> git remote add origin https://github.com/Mamatayadav1/Git_Assignment_1.git
PS C:\Users\HP\Git_Assignment_1> #Verify the remote repository
PS C:\Users\HP\Git_Assignment_1> git remote -v
origin  https://github.com/Mamatayadav1/Git_Assignment_1.git (fetch)
origin  https://github.com/Mamatayadav1/Git_Assignment_1.git (push)
PS C:\Users\HP\Git_Assignment_1> git branch -M main
PS C:\Users\HP\Git_Assignment_1> # Pushing the changes to GitHub
PS C:\Users\HP\Git_Assignment_1> git push -u origin main
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 240 bytes | 120.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/Mamatayadav1/Git_Assignment_1.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.
PS C:\Users\HP\Git_Assignment_1>
PS C:\Users\HP\Git_Assignment_1>
