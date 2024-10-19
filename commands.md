#Git commands

# Git Commands for DevOps

## 1. Directory and File Operations
```bash
mkdir git-for-devops         # Create a new directory
cd git-for-devops/          # Change into the new directory
pwd                         # Print working directory
touch bibba.txt nibbi.txt   # Create new files
ls -lath                    # List files with detailed information
ls                          # List files
```

## 2. Git Initialization
```bash
git init                    # Initialize a new Git repository
```

## 3. File Editing
```bash
vim hello.txt               # Open hello.txt in Vim
vi nibbi.txt                # Open nibbi.txt in Vim
```

## 4. Checking Git Status
```bash
git status                  # Show the working tree status
```

## 5. Staging Changes
```bash
git add nibbi.txt           # Stage nibbi.txt for commit
git add bibba.txt           # Stage bibba.txt for commit
git add hello.txt           # Stage hello.txt for commit
git add nibbu.txt           # Stage nibbu.txt for commit
```

## 6. Committing Changes
```bash
git commit -m "first commit"                  # Commit staged changes with a message
git commit -m "adding new changes to nibbi"   # Commit changes to nibbi.txt
git commit -m "added nibbu"                    # Commit changes to nibbu.txt
```

## 7. Configuring Git
```bash
git config --global user.email "itachiaman71@gmail.com"  # Set global user email
```

## 8. Branching
```bash
git checkout -b dev          # Create and switch to a new branch called dev
git checkout master           # Switch to the master branch
git checkout dev              # Switch to the dev branch
git branch                    # List all branches
```

## 9. Viewing Logs
```bash
git log                       # Show commit logs
git log --oneline             # Show commit logs in a simplified format
```

## 10. Restoring and Removing Files
```bash
git restore nibbi.txt         # Restore nibbi.txt from the last commit
rm -rf nibbi.txt              # Remove nibbi.txt from the working directory
```

## 11. Miscellaneous Commands
```bash
gitstatus                     # Check the status (note: this command might be a typo for 'git status')
ll                            # List files with details (alias for ls -l)
```
```
