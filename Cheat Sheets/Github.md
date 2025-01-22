# Git Command Cheat Sheet

## Setup Commands

```bash
git config --global user.name "Your Name" # Set your username 
git config --global user.email "you@example.com" # Set your email 
git config --list # View your settings

```

## Repository Commands (Basic Workflow)
```bash
git status                                      # Check the status of your repo
git add <file>                                  # Stage a specific file
git add .                                       # Stage all changes in the current directory
git commit -m "Commit message"                 # Commit changes with a message
git push origin <branch-name>                  # Push changes to a remote branch
git pull origin <branch-name>                  # Pull changes from a remote branch
```

## Branching
```bash
git branch                                      # List all branches
git branch <branch-name>                        # Create a new branch
git checkout <branch-name>                      # Switch to a branch
git checkout -b <branch-name>                   # Create and switch to a new branch
git merge <branch-name>                         # Merge a branch into the current one
git branch -d <branch-name>                     # Delete a branch
```

## Stashing
```bash
git stash                                       # Save changes without committing
git stash list                                  # List stashed changes
git stash apply                                 # Reapply stashed changes
git stash drop                                  # Delete a specific stash
```

## Undoing Changes
```bash
git restore <file>                              # Discard changes in a file
git reset <file>                                # Unstage a file
git reset --hard                                # Reset your repo to the last commit
git revert <commit-hash>                        # Undo a specific commit
```

## Viewing Histor
```bash
git log                                         # View commit history
git log --oneline                               # Compact commit history
git diff                                        # Show unstaged changes
git diff <branch1> <branch2>                    # Show differences between branches
```

## Tagging
```bash
git tag                                         # List all tags
git tag <tag-name>                              # Create a tag
git push origin <tag-name>                      # Push a tag to the remote repository
```

## Collaborating
```bash
git fetch                                       # Download updates from a remote repo
git pull                                        # Fetch and merge updates from a remote repo
git push                                        # Push changes to a remote repo
git push origin --delete <branch-name>          # Delete a remote branch
```

## Shortcuts
```bash
git checkout .                                  # Revert all unstaged changes
git commit -am "Commit message"                 # Stage and commit all changes
```