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


```

