🌟 Git Cheat Sheet for Beginners 🌟
📌 1. Basic Git Setup
1.1. Configure Git
Set your username:
git config --global user.name "Your Name"

Set your email:
git config --global user.email "your.email@example.com"

Check your Git configuration:
git config --list

1.2. Initialize a Repository
Create a new Git repository:
git init
1.3. Clone a Repository
Clone an existing repository from GitHub:
git clone https://github.com/user/repo.git
📂 2. Working with Your Repository
2.1. Check Repository Status
Show the current status of your working directory:
git status
2.2. Add Changes to Staging
Add a specific file to the staging area:
git add filename

Add all modified files to the staging area:
git add .

2.3. Commit Your Changes
Commit your changes with a message:
git commit -m "Describe what you changed"
🌿 3. Branching & Merging
3.1. Create & Switch Branches
Create a new branch:
git branch new-branch-name

Switch to another branch:
git checkout new-branch-name

3.2. Merge Branches
Merge a branch into the current branch:
git merge branch-name
🔄 4. Push & Pull
4.1. Push to a Remote Repository
Push your changes to the remote repository (origin):
git push origin branch-name
4.2. Pull from a Remote Repository
Fetch and merge changes from the remote branch to your local branch:
git pull origin branch-name
🔧 5. Undoing Changes
5.1. Discard Changes
Discard local changes in a specific file:
git checkout -- filename
5.2. Unstage Changes
Remove a file from the staging area without deleting the actual file:
git reset filename
5.3. Amend the Last Commit
Modify the most recent commit with new changes:
git commit --amend -m "Updated commit message"
📜 6. Viewing History & Differences
6.1. View Commit History
Show the commit history in your repository:
git log
6.2. View Changes Between Commits
See the difference between two commits:
git diff commit1 commit2
🌍 7. Remote Repositories
7.1. Add a Remote Repository
Link a new remote repository:
git remote add origin https://github.com/user/repo.git
7.2. List Remote Repositories
List all remote connections (URLs) for your repository:
git remote -v
💾 8. Stashing Changes
8.1. Stash Uncommitted Changes
Save your changes temporarily without committing:
git stash
8.2. Apply Stashed Changes
Reapply previously stashed changes:
git stash apply
🎉 End of Cheat Sheet!
