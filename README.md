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
