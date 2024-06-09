# PLPBasicGitAssignment Setup Documentation

This documentation outlines the steps I took to set up and manage the "PLPBasicGitAssignment" repository on GitHub.

### 1. GitHub Repository Creation

1. I logged in to my GitHub account.
2. I created a new repository named "PLPBasicGitAssignment":
   - I went to GitHub and clicked the "+" icon in the upper-right corner.
   - I selected "New repository."
   - I named the repository "PLPBasicGitAssignment."
   - I initialized the repository with a README file.
   - I clicked "Create repository."

### 2. Local Folder Setup

1. I created a new folder on my local machine:
   - I named it "PLPBasicGitAssignment."
   - I opened Git bash.
   - I navigated to the created folder:
     ```
     cd path/to/PLPBasicGitAssignment
     
     ```

### 3. Git Initialization

1. I initialized a new Git repository in my local folder:
   ```
   git init
   
   ```
### 4. Connecting to GitHub
1. I linked my local repository to the GitHub repository:
   ```
   git remote add origin https://github.com/Garycoco/PLPBasicGitAssignment.git
   
   ```
### 5. Create a File
Inside my local folder, I created a new text file named hello.txt using the command nano hello.txt which allowed me to enter the text to the file instantly.
I then saved the file after entering the text.

### 6. Committing Changes
1. I staged the changes
```
git add hello.txt

```
2. I committed the changes
```
git commit -m "Add hello.txt with a greeting"

```
### 7. Pushing to GitHub
I pushed the committed changes to my GitHub repository:
```
git push -u origin main

```
