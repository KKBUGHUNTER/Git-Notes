# Git branch
List all the branches in your Git repository, with the current branch highlighted
```
git branch
```
Create a new branch based on your current branch
```
git branch <new_branch_name>
```
Delete a branch (use -d to ensure it's fully merged or -D to force deletion)
```
git branch -d <branch_name>
```
or
```
git branch -D <branch_name>
```
Create a new branch and immediately switch to it
```
git checkout -b <new_branch_name>
```
or
```
git switch -c <new_branch_name>
```
# Git checkout
Switch to an existing branch, making it the active branch
```
git checkout <branch_name>
```
Create a new branch with no commit history
```
git checkout --orphan <new_branch_name>
```

# Git merge
Merge a Feature Branch into the Current Branch:
Switch to the branch you want to merge the changes into (e.g., the main branch), and then use the git merge command to merge the changes from a  branch:
```
git checkout main
git merge <branch_name>
```
Provide a custom commit message while performing the merge
```
git merge feature-branch -m "Merge <branch> into main"
```

![git branch](https://github.com/KKBUGHUNTER/Git-Notes/assets/91019132/39691bc0-4cc4-4494-980f-d49a1185235a)
