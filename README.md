# First Repo
This is my first Repository in Github.  
This is the second line of text.
1. Introduction to Git and GitHub
Git: Git is a Version Control System (VCS) that tracks the history of changes made to your code. It is free, open-source, fast, scalable, and heavily used in the tech industry. It acts like a bank statement for your code, recording when files are added, modified, or deleted.
Primary Uses: Tracking the history of your project (allowing you to revert to previous versions if needed) and collaborating with a team to ensure developers don't overwrite each other's work.
GitHub: While Git is a software tool installed on your computer, GitHub is a website that allows developers to store, manage, and showcase their code. Developers often use GitHub links on their resumes as a portfolio of their work.
2. Getting Started with GitHub
Repositories (Repos): A repository is a folder where your project and its code are stored on GitHub. Repositories can be Public (visible to anyone) or Private (visible only to you).
README.md: A special markdown file initialized with a project that contains essential details, such as the project's name, purpose, features, and instructions on how to use it.
3. Setting up Git Locally
To use Git on your local machine, you need a code editor like Visual Studio Code (VS Code) and a terminal (Git Bash for Windows, or the default Terminal for Mac/Linux).
Verify Installation: Type git --version in your terminal to ensure it is installed correctly.
Configuration: You must link Git to your GitHub account using your username and email.
git config --global user.name "Your Name".
git config --global user.email "your-email@example.com".
To view your configuration, use: git config --list.
4. Git File States
Git tracks files through four main states:
Untracked: A newly created file that Git is not yet aware of.
Modified: An existing tracked file that has been changed but not yet added (staged).
Staged: A file that is added and ready to be committed. The video compares this to an "engagement".
Unchanged (Committed): The changes are securely recorded in the Git history. The video compares this final step to a "wedding".
5. Essential Git Commands & Workflow
Initialize a Repo: git init creates a new, empty Git repository inside a local folder.
Check Status: git status shows the current state of your code, highlighting untracked, modified, or staged files.
Clone: git clone <https-link> copies an existing repository from GitHub to your local computer.
Add (Stage): git add <filename> moves a specific file to the staging area. Using git add . stages all new and modified files at once.
Commit: git commit -m "Meaningful message" finalizes the changes and takes a snapshot of the code. Always use a descriptive message like "Add new button".
Connect Local to Remote: git remote add origin <link> links a local repository to a remote GitHub repository.
Push: git push origin main uploads your local commits to the remote GitHub repository. You can use git push -u origin main to set the upstream, meaning in the future, you only need to type git push.
Pull: git pull origin main fetches and downloads new changes from the remote GitHub repository directly into your local machine.
6. Branching
When multiple developers work on a project, or when building new features, they create separate "branches" so they don't interfere with the main codebase.
Check Branches: git branch lists all branches and highlights the current one.
Rename Branch: git branch -m <new-name> (e.g., changing "master" to "main").
Create & Switch: git checkout -b <new-branch-name> creates a new branch and instantly switches to it.
Switch Branches: git checkout <branch-name> moves you to an existing branch.
Delete Branch: git branch -d <branch-name> (Note: You cannot delete a branch if you are currently on it).
7. Merging & Pull Requests
Merging Locally: To combine code from a feature branch into the main branch, switch to the main branch and type git merge <branch-name>. You can compare branches before merging using git diff <branch-name>.
Pull Requests (PR): When working with a team on GitHub, instead of manually merging, you create a "Pull Request". This alerts senior developers or managers that you have pushed changes. They will review the code, suggest modifications, and eventually approve and merge the code into the main branch
1. Introduction to Git and GitHub
Git: Git is a Version Control System (VCS) that tracks the history of changes made to your code. It is free, open-source, fast, scalable, and heavily used in the tech industry. It acts like a bank statement for your code, recording when files are added, modified, or deleted.
Primary Uses: Tracking the history of your project (allowing you to revert to previous versions if needed) and collaborating with a team to ensure developers don't overwrite each other's work.
GitHub: While Git is a software tool installed on your computer, GitHub is a website that allows developers to store, manage, and showcase their code. Developers often use GitHub links on their resumes as a portfolio of their work.
2. Getting Started with GitHub
Repositories (Repos): A repository is a folder where your project and its code are stored on GitHub. Repositories can be Public (visible to anyone) or Private (visible only to you).
README.md: A special markdown file initialized with a project that contains essential details, such as the project's name, purpose, features, and instructions on how to use it.
3. Setting up Git Locally
To use Git on your local machine, you need a code editor like Visual Studio Code (VS Code) and a terminal (Git Bash for Windows, or the default Terminal for Mac/Linux).
Verify Installation: Type git --version in your terminal to ensure it is installed correctly.
Configuration: You must link Git to your GitHub account using your username and email.
git config --global user.name "Your Name".
git config --global user.email "your-email@example.com".
To view your configuration, use: git config --list.
4. Git File States
Git tracks files through four main states:
Untracked: A newly created file that Git is not yet aware of.
Modified: An existing tracked file that has been changed but not yet added (staged).
Staged: A file that is added and ready to be committed. The video compares this to an "engagement".
Unchanged (Committed): The changes are securely recorded in the Git history. The video compares this final step to a "wedding".
5. Essential Git Commands & Workflow
Initialize a Repo: git init creates a new, empty Git repository inside a local folder.
Check Status: git status shows the current state of your code, highlighting untracked, modified, or staged files.
Clone: git clone <https-link> copies an existing repository from GitHub to your local computer.
Add (Stage): git add <filename> moves a specific file to the staging area. Using git add . stages all new and modified files at once.
Commit: git commit -m "Meaningful message" finalizes the changes and takes a snapshot of the code. Always use a descriptive message like "Add new button".
Connect Local to Remote: git remote add origin <link> links a local repository to a remote GitHub repository.
Push: git push origin main uploads your local commits to the remote GitHub repository. You can use git push -u origin main to set the upstream, meaning in the future, you only need to type git push.
Pull: git pull origin main fetches and downloads new changes from the remote GitHub repository directly into your local machine.
6. Branching
When multiple developers work on a project, or when building new features, they create separate "branches" so they don't interfere with the main codebase.
Check Branches: git branch lists all branches and highlights the current one.
Rename Branch: git branch -m <new-name> (e.g., changing "master" to "main").
Create & Switch: git checkout -b <new-branch-name> creates a new branch and instantly switches to it.
Switch Branches: git checkout <branch-name> moves you to an existing branch.
Delete Branch: git branch -d <branch-name> (Note: You cannot delete a branch if you are currently on it).
7. Merging & Pull Requests
Merging Locally: To combine code from a feature branch into the main branch, switch to the main branch and type git merge <branch-name>. You can compare branches before merging using git diff <branch-name>.
Pull Requests (PR): When working with a team on GitHub, instead of manually merging, you create a "Pull Request". This alerts senior developers or managers that you have pushed changes. They will review the code, suggest modifications, and eventually approve and merge the code into the main branch

