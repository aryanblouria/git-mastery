# git-mastery
My repo for learning Git commands

- ### GIT commands:

  - clone a Repository:
   ```bash
  git clone <URL>
  ``` 
  - Initialising a GIT Repository:
   ```bash
    git init
    ``` 

  - Getting stagging status:
  ```bash
  git status
  ```
  - Show git log:
  ```bash
  git log
  ```
    - Add Files to Staging Area:
   ```bash
   git add .
   ``` 
  - Commit changes:
   ```bash
   git commit -m " "
   ```
   - Change Working Branch:
   ```bash
   git checkout 'branch_name'
   ```
    - Push Command:
   ```bash
    git push <remote name> <branch name>
    ```
    - Creating new Branch:
    ```bash
    git switch -c <new-branch-name>
    ``` 
    or 
    ```bash 
    git branch <new-branch-name>
    ```
    - Pull latest commit from remote:
   ```bash	
    git pull <remote> <branch>
    ```
    - View all branches:
    ```bash
    git branch
    ```
    - Delete Branch:
    ```bash
    git branch -d <branch-name>
    ```
    - Merge Repository: 
    ```bash
    git merge <repo name>
    ```
    - Compare Difference Between 2 commits
   ```bash
    git diff <commit_1 id> <commit_2 id> 
    ```
