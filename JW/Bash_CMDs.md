# Useful Git Bash Commands

## Basic Commands
- **`git init`**: Initializes a new Git repository.
- **`git clone <repository>`**: Clones an existing repository.
- **`git status`**: Shows the status of the working directory and staging area.
- **`git add <file>`**: Adds a file to the staging area.
- **`git commit -m "message"`**: Commits changes with a message.
- **`git push`**: Pushes changes to the remote repository.
- **`git pull`**: Fetches and merges changes from the remote repository.

## Branching and Merging
- **`git branch`**: Lists all branches.
- **`git branch <branch>`**: Creates a new branch.
- **`git checkout <branch>`**: Switches to the specified branch.
- **`git merge <branch>`**: Merges the specified branch into the current branch.

## Viewing History
- **`git log`**: Shows the commit history.
- **`git log --oneline`**: Shows the commit history in a compact format.
- **`git diff`**: Shows changes between commits, commit and working tree, etc.

## Undoing Changes
- **`git reset <file>`**: Unstages a file.
- **`git checkout -- <file>`**: Discards changes in the working directory.
- **`git revert <commit>`**: Reverts a commit by creating a new commit.

## Configuration
- **`git config --global user.name "name"`**: Sets the username.
- **`git config --global user.email "email"`**: Sets the email address.

# General Workflow for Creating a New Directory and File

1. Open Git Bash.

2. Navigate to the location where you want to create the new directory:
   ```bash
   cd path/to/location
   ```
   
3. Create a new directory:
	```bash
	mkdir new_dir_name
	```
	
4. Navigate to new dir:
	```bash
	cd new_dir_name
	```
	
5. Create a new file:
	```bash
	touch new_file_name.file
	```
	
6. Initialize a new Git repository:
	```bash
	git init
	```
	
7. Add the new file to the staging area:
	```bash
	git add new_file_name.file
	```
	
8. Commit the new file:
	```bash
	git commit -m "Message for documentation"
	```
	
9.Push the changes to GitHub:
	```bash
	git push origin main
	```
	
	
THIS SHOULD WORK MAYBE