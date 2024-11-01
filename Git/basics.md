- **`git init`** ->
	- initializes a git repository
	- creates a directory named `.git` that contains repository files
- **`git add <filenam>`** ->
	- starts tracking the given files
	- enter `.` to track all files
- **`git commit`** ->
	- add `--amend` at end to include anything else with the prev commit
- **`git clone <url>`** ->
	- copies an existing git repo
	- add a name at the end if you want to name is something else
- **`git status`** -> 
	- determine which files are in which state
- **`git reset`** -> 
	- removes filed from the staged area
- **`git checkout -- .`** ->
	- resets all changes to the working directory

## basic configuration
```bash
# set user name
git config --global user.name "Haris Ahmad"
# set email
git config --global user.email harizahmad100@gmail.com
# set the default branch name
git config --global init.defaultBranch main
# set the defeault text editor
git config --global core.editor micro
```

