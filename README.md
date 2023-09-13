# Gihub-Test -Basic Git Commands

- Initialize a new Git repository:  
  ```git init```

- Add files to staging:  
  ```git add .```

- Commit changes:  
  ```git commit -m "message"```

- Push changes to a remote branch:  
  ```git push origin <branch-name>```
![Screenshot from 2023-09-12 16-15-49](https://github.com/Sejal-brilworks/Gihub-test/assets/144772574/14c52f72-b457-406f-af63-db081c7ae947)
![Screenshot from 2023-09-12 16-15-49](https://github.com/Sejal-brilworks/Gihub-test/assets/144772574/47cfaa7f-32bd-4e5a-afd9-5a199a423e06)
![Screenshot from 2023-09-12 16-15-49](https://github.com/Sejal-brilworks/Gihub-test/assets/144772574/4ad9350e-467d-473e-9b55-15df1d27115d)
![Screenshot from 2023-09-12 16-15-49](https://github.com/Sejal-brilworks/Gihub-test/assets/144772574/65585b27-705d-4b1b-84a5-d14140f172ed)

---

## Branch Operations

- Create a new branch:  
  ```git branch <branch-name>```

- Switch to a branch:  
  ```git checkout <branch-name>```

- Delete a branch:  
  ```git branch -d <branch-name>```
![Screenshot from 2023-09-12 16-15-49](https://github.com/Sejal-brilworks/Gihub-test/assets/144772574/b0b80e42-2447-4a7c-adb3-fb256e09b7fc)

---

## Repository Setup Steps

1. **Initialize the Repo**:  
   ```git init```

2. **Clone Repo**:  
   ```git clone https://github.com/Brilworks-Interns/mern.git```

3. **Rename Main Branch**:  
   ```git branch main master_sejal.y```

---

## Git Configuration

1. **Install Git**:  
   ```sudo apt install git-all```  
   Verify installation:  
   ```git --version```

2. **Configure User Information**:  
   ```
   git config --global user.name "sejalyadav"
   git config --global user.email "sejal.y@Brilworks.com"
   git config --list
   ```
![Screenshot from 2023-09-13 07-23-58](https://github.com/Sejal-brilworks/Gihub-test/assets/144772574/4da334ec-2505-4e2c-a85b-e15dc7150dce)

3. **SSH Configuration**:  
   Navigate to: `Settings > Developer Settings > Personal Access Token`, then create one. 

---

## Git Concepts and Commands

- **cherry-pick**:  
  The `cherry-pick` command lets you take a commit from one branch and apply it to another.

- **git diff**:  
  Shows changes between your current working directory and your staging area.
  ![Screenshot from 2023-09-12 17-41-29](https://github.com/Sejal-brilworks/Gihub-test/assets/144772574/7d8c5344-7a2a-4b9c-95d0-6972f8a62867)

- **git log**:  
  Displays the most recent commits with author names, and timestamps.
  # Basic Git Commands

- Initialize a new Git repository:  
  ```git init```

- Add files to staging:  
  ```git add .```

- Commit changes:  
  ```git commit -m "message"```

- Push changes to a remote branch:  
  ```git push origin <branch-name>```
![Screenshot from 2023-09-12 16-15-49](https://github.com/Sejal-brilworks/Gihub-test/assets/144772574/14c52f72-b457-406f-af63-db081c7ae947)
![Screenshot from 2023-09-12 16-15-49](https://github.com/Sejal-brilworks/Gihub-test/assets/144772574/47cfaa7f-32bd-4e5a-afd9-5a199a423e06)
![Screenshot from 2023-09-12 16-15-49](https://github.com/Sejal-brilworks/Gihub-test/assets/144772574/4ad9350e-467d-473e-9b55-15df1d27115d)
![Screenshot from 2023-09-12 16-15-49](https://github.com/Sejal-brilworks/Gihub-test/assets/144772574/65585b27-705d-4b1b-84a5-d14140f172ed)

---

## Branch Operations

- Create a new branch:  
  ```git branch <branch-name>```

- Switch to a branch:  
  ```git checkout <branch-name>```

- Delete a branch:  
  ```git branch -d <branch-name>```
![Screenshot from 2023-09-12 16-15-49](https://github.com/Sejal-brilworks/Gihub-test/assets/144772574/b0b80e42-2447-4a7c-adb3-fb256e09b7fc)

---

## Repository Setup Steps

1. **Initialize the Repo**:  
   ```git init```

2. **Clone Repo**:  
   ```git clone https://github.com/Brilworks-Interns/mern.git```

3. **Rename Main Branch**:  
   ```git branch main master_sejal.y```

... [additional steps truncated for brevity]

---

## Git Configuration

1. **Install Git**:  
   ```sudo apt install git-all```  
   Verify installation:  
   ```git --version```

2. **Configure User Information**:  
   ```
   git config --global user.name "sejalyadav"
   git config --global user.email "sejal.y@Brilworks.com"
   ```

3. **SSH Configuration**:  
   Navigate to: `Settings > Developer Settings > Personal Access Token`, then create one. 

---

## Git Concepts and Commands

- **cherry-pick**:  
  The `cherry-pick` command lets you take a commit from one branch and apply it to another.

- **git diff**:  
  Shows changes between your current working directory and your staging area.
  ![Screenshot from 2023-09-12 17-41-29](https://github.com/Sejal-brilworks/Gihub-test/assets/144772574/7d8c5344-7a2a-4b9c-95d0-6972f8a62867)

- **git log**:  
  Displays the most recent commits with author names, and timestamps.
  ![Screenshot from 2023-09-13 07-08-24](https://github.com/Sejal-brilworks/Gihub-test/assets/144772574/b00b239c-a330-46c5-9fb1-825984ffd2af)

- **Push, Merge, Pull, Fetch**:  
   - **Push**: Send changes to the remote.  
   - **Merge**: Combine branch changes.  
   - **Pull**: Equivalent to `Fetch + Merge`.  
   - **Fetch**: Download changes without merging.

- **Tag in Git**:  
  A tag is a reference to a specific commit in the repo's history, often used for release points like "v1.0".

- **.gitignore**:  
  This file in a Git repo specifies which files or directories should be ignored by Git. Examples include:  
   - Specific files: `my_file.txt`
   - File patterns: `*.log`
   - Directories: `/directory_to_ignore/`
   - ![Screenshot from 2023-09-12 18-22-19](https://github.com/Sejal-brilworks/Gihub-test/assets/144772574/a7e39fdf-90f5-4275-84c5-5bc0270a30a6)
   
- ** Remote** :
- **`git remote show <remote_name>`**: Show information about a remote repository.
- **`git remote remove <remote_name>`**: Remove a remote repository.
- **`git remote -v`** : check current remote repo
 
- ![Screenshot from 2023-09-13 07-41-08](https://github.com/Sejal-brilworks/Gihub-test/assets/144772574/da0ac3c9-d75f-4437-b95a-1e92aa95450f)

- **`git show`** : Show various objects like commits, tags, etc.

![Screenshot from 2023-09-13 07-44-33](https://github.com/Sejal-brilworks/Gihub-test/assets/144772574/054b9551-162a-4c29-bfaa-51f71a30aa83)

- **git fetch --all** : Fetch all remotes.
- 
![Screenshot from 2023-09-13 07-46-22](https://github.com/Sejal-brilworks/Gihub-test/assets/144772574/96d6a19f-a1e0-4b1f-9aca-e14063269444)


```
##  `cherry-pick`

The `git cherry-pick` command is used to apply the changes introduced by a specific commit onto another branch.

1. **Identify the Commit Hash**:  
   View the commit history and get the hash of the bug-fix commit:
   ```bash
   git log feature-branch
   ```
   Assume the commit hash of the fix is `a12345b`.

2. **Checkout the Target Branch**:  
   Switch to the branch where you want to apply the bug-fix commit, in this case, `main`:
   ```bash
   git checkout main
   ```

3. **Apply the Commit using cherry-pick**:  
   ```bash
   git cherry-pick a12345b
   ```
 commit master branch 
![Screenshot from 2023-09-13 10-34-11](https://github.com/Sejal-brilworks/Gihub-test/assets/144772574/fcd14765-37c8-4eef-8c8b-2479a182e192)


crated pull request : https://github.com/Brilworks-Interns/mern/pull/4
Practice Github commads : https://github.com/Sejal-brilworks/Gihub-test






