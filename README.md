# Git config
Set your username and email address for all Git repositories on your system. This information is associated with your commits
```
git config --global user.name "Your Name"
git config --global user.email "youremail@example.com"
```
Display your global Git configuration settings
```
git config --global --list
```
Set your username and email address for a specific Git repository (overrides global settings)
```
git config user.name "Your Name"
git config user.email "youremail@example.com"
```
Display configuration settings specific to the current Git repository
```
git config --list
```

# Git Clone
git clone is primarily used to point to an existing repo and make a clone or copy of that repo at in a new directory, at another location.
```sh
git clone https://github.com/KKBUGHUNTER/Git-Notes.git
```
You can also specify a different directory name for the local clone by providing it as the second argument:
```
git clone <repository URL> <local-directory>
git clone https://github.com/KKBUGHUNTER/Git-Notes.git my-local-repo
```

# Git add 
The git add command adds new or changed files in your working directory to the Git staging area. 
```
git add *
```
`*` - representative add all file.
To add a specific file to the staging area in Git, you can use the git add command followed by the path to the file you want to stage
```
git add path/to/your-file.txt
```
if you want to add a file named "example.txt" in the current directory, you would use:
```
git add example.txt
```
If you want to stage multiple specific files, you can list them one after the other:
```
git add file1.txt file2.txt file3.txt
```
# Git Commit
Commit with a short message on the command line without opening a text editor:
```
git commit -m "Commit message"
```
Commit all changes, including untracked files
```
git commit -a -m "Commit message"
```

# Git push
Push the current branch to the default remote repository (usually named "origin"):
```
git push
```
Push the current branch to a specific branch on the remote repository
```
git push origin <branch_name>
```
Push all branches to the remote repository
```
git push --all
```

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









