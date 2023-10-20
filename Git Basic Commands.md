<div align=center>
<h1> Git Basic Commands </h1>
</div>

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
![basic git commands 1](https://github.com/KKBUGHUNTER/Git-Notes/assets/91019132/ca3d4cdf-7329-42f7-a6d7-4200c419de6e)

