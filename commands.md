Git Cheat Sheet for Beginners
1. Basic Commands
1.1. Setting Up Git
Set your username:
git config --global user.name "Your Name"

Set your email:
git config --global user.email "your.email@example.com"

Check the configuration settings:
git config --list

1.2. Initialize a Repository
Initialize a new Git repository:
git init
1.3. Clone a Repository
Clone an existing repository:
git clone https://github.com/user/repo.git
2. Working with the Repository
2.1. Check the Status
Show the working tree status:
git status
2.2. Add Changes to Staging Area
Add a specific file to the staging area:
git add filename

Add all files to the staging area:
git add .

2.3. Commit Changes
Commit staged changes with a message:
git commit -m "Your commit message"
3. Branching & Merging
3.1. Create a New Branch
Create a new branch:
git branch new-branch-name

Switch to a branch:
git checkout new-branch-name

3.2. Merge Branches
Merge a branch into the current branch:
git merge branch-name
4. Pushing & Pulling
4.1. Push to a Remote Repository
Push changes to the remote repository:
git push origin branch-name
4.2. Pull from a Remote Repository
Fetch and merge changes from the remote repository:
git pull origin branch-name
5. Undoing Changes
5.1. Discard Changes in a File
Discard local changes in a file:
git checkout -- filename
5.2. Unstage a File
Remove a file from the staging area without deleting the actual file:
git reset filename
5.3. Amend the Last Commit
Amend the most recent commit with new changes:
git commit --amend -m "Updated commit message"
6. Git Log & Diff
6.1. View Commit History
Show the commit history:
git log
6.2. Show Changes Between Commits
Show changes between commits:
git diff commit1 commit2
7. Remote Repositories
7.1. Add a Remote Repository
Add a remote repository:
git remote add origin https://github.com/user/repo.git
7.2. List Remote Repositories
List remote repositories:
git remote -v
8. Stashing Changes
8.1. Stash Uncommitted Changes
Save uncommitted changes for later:
git stash
8.2. Apply Stashed Changes
Reapply stashed changes:
git stash apply
