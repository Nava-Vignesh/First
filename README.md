# First Repo
This is my first Repository in Github.  
This is the Notes of my learning of  basic git.  


- Public: Visible to anyone  
- Private: Visible only to you  

## README.md
A special markdown file that contains:
- Project name
- Purpose
- Features
- Usage instructions

---

# Setting Up Git Locally

## Requirements
- Code editor (e.g., VS Code)  
- Terminal (Git Bash / Command Prompt / Mac/Linux Terminal)

## Verify Installation

git --version


## Configuration

git config --global user.name "Your Name"
git config --global user.email "your-email@example.com
"


## View Configuration

git config --list


---

 # Git File States

Git tracks files in four states:

1. Untracked  
   New file, not known to Git  

2. Modified  
   File changed but not staged  

3. Staged  
   File added and ready to commit  

4. Committed (Unchanged)  
   Changes saved in Git history  

---

# Essential Git Commands and Workflow

### Initialize Repository : git init
#### Check Status              :  git status  
#### Clone Repository              : git clone <repository-link>  
#### Add Files (Stage)             : git add <filename> or for all files - git add .  
#### Commit Changes                : git commit -m "Meaningful message"  
  
#### Connect to Remote Repository : git remote add origin <repository-link>  
#### Push Code                    : git push origin main  
First time : git push -u origin main    
#### Pull Code : git pull origin main 

---

# Branching

Branches allow multiple developers to work without affecting the main code.

#### Check Branches                 :  git branch  
<p> <i> Rename Branch </i>                  :  git branch -m <new-name>  </p>
<p> <b> Create and Switch Branch </b>       :  git checkout -b <branch-name> </p>  
<p> <b> Switch Branch </b>    :  git checkout  <branch-name> </p>  
<p> <b> Delete Branch </b>    :  git branch -d <branch-name> </p> 

---

# Merging and Pull Requests

## Merge Branch Locally

git checkout main
git merge <branch-name>

## Compare Branches

git diff <branch-name>

## Pull Requests (PR)
- Used in team collaboration
- Submit changes for review
- Senior developers review and approve
- Code is merged into the main branch

