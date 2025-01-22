# Bash Command Cheat Sheet

## Navigation
```bash
pwd                      # Print the current working directory
ls                       # List files in the current directory
ls -a                    # List all files, including hidden files
ls -l                    # List files with detailed information
cd <directory>           # Change directory
cd ..                    # Move up one directory level
cd ~                     # Move to the home directory
```

## File Operations
```bash
touch <file>             # Create an empty file
cat <file>               # Display the contents of a file
cp <source> <destination> # Copy a file or directory
mv <source> <destination> # Move or rename a file/directory
rm <file>                # Delete a file
rm -r <directory>        # Delete a directory and its contents
```

## Directory Operations
```bash
mkdir <directory>        # Create a new directory
rmdir <directory>        # Delete an empty directory
tree                     # Display directory structure (requires installation)
```

## File Viewing
```bash
cat <file>               # View the contents of a file
less <file>              # View the file one page at a time
head <file>              # Display the first 10 lines of a file
tail <file>              # Display the last 10 lines of a file
tail -f <file>           # Continuously monitor a file for changes
```

## Searching
```bash
grep <pattern> <file>    # Search for a pattern in a file
grep -r <pattern> <directory> # Search recursively in a directory
find <directory> -name <name> # Find files/directories by name
```

## Disk Usage
```bash
df -h                    # Display free disk space in human-readable format
du -h                    # Show disk usage of files and directories
du -sh <directory>       # Show total disk usage for a directory
```

## Permissions
```bash
chmod +x <file>          # Make a file executable
chmod 755 <file>         # Change file permissions
chown <user>:<group> <file> # Change ownership of a file
```

## Miscellaneous
```bash
Ctrl + C                  # Stop the current command
Ctrl + Z                  # Suspend the current command
Ctrl + R                  # Search command history
!!                        # Run the last executed command
!<command>                # Run the last command starting with <command>
history                   # Show command history
alias <name>="<command>"  # Create a shortcut for a command
unalias <name>            # Remove an alias
```