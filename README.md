# Git LFS Integration for Large Binary Files

This repository demonstrates the use of Git LFS (Large File Storage) for handling large binary files efficiently.

## Task

### 1. Integrating Git LFS

- [x] Installed Git LFS on the local machine.
- [x] Initialized Git LFS for the repository.

### 2. Creating a Branch

Created a branch named `lfs` to manage large files separately.

### 3. Adding a Large File
Added a large file named test_file.zip (size > 200MB) to the repository. 
This file will be tracked by Git LFS.

### 4. Committing and Pushing

git add test_file.zip
git commit -m "Add test_file.zip using Git LFS"
git push origin lfs

### 5. Verification
Cloned the repository on another machine and verified that the large file test_file.zip 
was downloaded correctly using Git LFS.


