# Practical 6

## Aim
To learn and practice Git and GitHub commands for version control and repository management.

## Objectives
- To configure Git with username and email.
- To create and manage a Git repository.
- To add files to the staging area.
- To commit changes.
- To connect a local repository with GitHub.
- To push changes to a GitHub repository.

## Commands Used

```bash
git config --global user.name "Your Name"
git config --global user.email "your-email@gmail.com"

git init
git status
git add .
git commit -m "Initial commit"
git remote add origin <repository-url>
git push -u origin main
