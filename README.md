
# GitHub Concepts
This projects explains about GitHub Concepts Theoritically and Practically.

## Git and GitHub
**YouTube Video**

https://youtu.be/I4_NJoV92pQ?si=0KimLGCDJMa8h0MA

## Git Architecture and Git Stages

1. Working Directory.
2. Staging Area.
3. Local Repository.
4. Remote Repository - GitHub.

**YouTube Video**
https://youtu.be/0me1X5oWbfM?si=I39q9yf9d0OlEddM

## Commands to Push Code to Remote Repository

Pre-Requisites

Git Should be Installed in System
https://git-scm.com/download/

GitHub Account Should be Created
git config --global user.name "DevOpsCloudAutomation"
git config --global user.email "Pavankumarkj347@Gmail.com"

git config --list

Create a Personal Access Token in GitHub and Add it in Local System.
MacBook: KeyChain Access.
Windows: Credentials Manager.

Note
We Cannot Use Username and Password as GitHub Support for Password Authentication was Removed.

### Practical

Create Remote Repository.

Create a Project in Local System.

Push Code to Remote Repository.

Working Directory | Staging Area | Local Repository | Remote Repository

### Commands
git init - Create Local Repository in Project.
git status - Check Status of New and Modified Files.
git add . - Add All Files from Working Directory to Staging Area.
git commit -m <Commit_Messsage> - Move Files from Staging Area to Local Repository.
git remote add origin <Remote_Repository_Url> - Add Remote Repository Url to .git Local Repository.
git push origin <Branch_Name> - Add Files from Local Repository to Remote Repository.

**YouTube Video**

https://youtu.be/e7dQ-wmOTS4?si=BGVlSa60bNBcmEFG

## Git Reset and Git Revert

git log

git log --oneline

### Git Reset

Get Back Files from Staging Area to Working Directory.

git reset
Get All Files from Staging Area to Working Directory.

git reset <File_Name>
Get Particular Single file from Staging Area to Working Directory.

### Git Revert

git revert <Commit_ID>
Delete Files from Local Repository.
