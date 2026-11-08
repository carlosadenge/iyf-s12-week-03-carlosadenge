# Terminal Log – Week 3

**Student:** Carlos Adenge  
**Repository:** iyf-s12-week-03-carlosadenge

# Task 5.1: Terminal Navigation
## Commands I used:
- pwd
- ls
- cd ~/Documents
- cd ..
- cd ~
- mkdir ~/terminal-practice
- cd ~/terminal-practice
- mkdir -p my-project/src/css
- mkdir -p my-project/src/js
- mkdir -p my-project/src/images
- mkdir my-project/docs
- mkdir my-project/tests
- touch my-project/README.md
- ls -R my-project
<img width="722" height="421" alt="08 11 2026_11 17 48_REC" src="https://github.com/user-attachments/assets/257c83e3-c4e4-42b3-a503-cac9583f1b80" />

## What each command did:
- pwd → showed my current directory
- ls → listed files and folders
- cd → moved between folders
- mkdir -p → created nested folders
- touch → created an empty file
- ls -R → showed the full folder structure

# Task 5.2: File Operations
## Commands I used:
- touch index.html
- cat index.html
- cp index.html backup.html
- mv backup.html my-project/docs/
- mv index.html home.html
- rm home.html
- cp -r my-project/src my-project/src-backup
- mkdir my-project/archive
- mv my-project/src-backup my-project/archive/
- rm -r my-project/archive

## What I learned:
- touch creates a new empty file
- cat shows the content of a file
- cp copies a file
- mv moves or renames a file
- rm deletes a file
- cp -r copies a whole folder
- rm -r deletes a folder and everything inside it


# Task 5.3: Useful Terminal CommandsQuestions I answered:
- How many HTML files are in my portfolio? Bashfind . -name "*.html" | wc -l
- Which files contain the word "contact"? Bashgrep -r "contact" .
- How many lines is my CSS file? Bashwc -l styles.css
- What were my last 10 terminal commands? Bashhistory | tail -10

# Task 5.4: Shell Script Basics
### What I did:
- Created a file called new-project.sh
- Added a script that automatically creates a project folder structure
- Made the script executable using chmod +x
- Tested the script by creating a project called my-awesome-app

## Command used to run the script:
- bash new-project.sh my-awesome-app


# Task 6.1: Git Basics
## Commands I practiced:
- git config --global --list
- git status
- git log --oneline
- git add styles.css
- git commit -m "Style: add navigation hover underline"
- git add new-project.sh
- git commit -m "Add: project setup shell script"
- git push origin main
- <img width="622" height="310" alt="08 11 2026_13 01 07_REC" src="https://github.com/user-attachments/assets/c56a4e0a-46a3-4339-b035-3ee49f035ca0" />


## What I learned:
- How to check Git configuration
- How to stage files with git add
- How to make meaningful commit messages
- How to view commit history with git log

# Task 6.2: Branching & Merging
## Commands I used:
- git checkout -b feature/about-page
- git add about.html
- git commit -m "Update: improve about page content"
- git checkout main
- git merge feature/about-page
- git branch -d feature/about-page
- git push origin main
- <img width="640" height="376" alt="08 11 2026_11 58 42_REC" src="https://github.com/user-attachments/assets/48faa583-7051-4591-989c-88ac22401599" />


# What I learned:
- How to create a new branch
- How to switch between branches
- How to merge a feature branch into main
- How to delete a branch after merging


 # Merge Conflict Practice
### Commands I used:
- git checkout -b branch-one
- git add about.html
- git commit -m "Update: about page from branch one"
- git checkout main
- git checkout -b branch-two
- git add about.html
- git commit -m "Update: about page from branch two"
- git checkout main
- git merge branch-one
- git merge branch-two
- git add about.html
- git commit -m "Fix: resolve merge conflict in about.html"
- git branch -d branch-one
- git branch -d branch-two
- git push origin main
- <img width="615" height="370" alt="08 11 2026_13 02 09_REC" src="https://github.com/user-attachments/assets/d7bc0459-508f-4f07-a333-7b760d2d205c" />


### How a merge conflict happens when two branches change the same line
- How to open the file and remove conflict markers
- How to complete the merge with a clear commit messageat I learned:



