_________________________________________________________________________________________
Basic Git Commands
git init
git add .
git commit -m "message"
git push origin branch name
_________________________________________________________________________________________

create branch 
git branch branchname
_________________________________________________________________________________________
checkout branch 
git checkout branch name

_________________________________________________________________________________________
delete  branch 
git branch-d branch name
_________________________________________________________________________________________
step 0 : initialalize the Repo
          git init 
step 1 : clone repo 
        git clone https://github.com/Brilworks-Interns/mern.git

step 2 : rename main branch to master_sejal.y
         git branch main master_sejal.y

step 3 : Empty commit
         git commit --allow-empty -m "Empty Commit"

step 4 : Add something and commit and push 
        git add .
        git commit -m "initial code"
        git push origin master_sejal.y

step 5 : create subbranch 
        git checkout master_sejal.y
        git branch hello_world
        git status
        git checkout hello_world  >  create folder and file make same chnages
        git add .
        git commit -m "code chnages"
        git push origin hello_world
        git checkout origin master_sejal.y
step 6 : check and send pull request with message and send it 

My pull request : https://github.com/Brilworks-Interns/mern/pull/4
_________________________________________________________________________________________

How to config git ?

step 1 : install git 
        sudo apt install git-all
        check 
        git --version 

step 2 : config
    git config --global user.name "sejalyadav"
    git config --global user.email "sejal.y@Brilworkss.com

step 3 : ssh config
    go to setting devloper setting > Personal Access Token > create one use add password  and username as its 

_________________________________________________________________________________________

what is cherry-pick command in github ?

`cherry-pick` command allows you to take a commit from one branch and apply it onto another. 

two branches: `main` and `feature-branch`. Let's say the `feature-branch` has three commits (A, B, and C), and you only want to apply commit B to `main` without merging the entire `feature-branch`.

1. First, you'll need to get the commit hash of commit B. You can find this with: git log

2. commit hash of commit B (<commit-hash>), checkout the `main` branch: git checkout main


3. Now, apply the specific commit using cherry-pick: git cherry-pick <commit-hash>

If no conflicts, commit B's changes will now be applied to `main`.
 If there are conflicts resolve  manually.
_______________________________________________________________________________________

what is git diff ?
changes between your current working directory and your staging area.

_________________________________________________________________________________________


what is gitlog ?
display most recent commits with auther name and date & time 

_________________________________________________________________________________________

Push = Send changes to the remote.
Merge  = Combine branch changes.
Pull  = Fetch + Merge.
Fetch = Download changes without merging.
_________________________________________________________________________________________

what is tag in git ?

 tag is a reference or pointer to a specific commit in the repository's history,
 often used to mark particular points  like "v1.0", "v2.5", etc.

_________________________________________________________________________________________

what is .gitignore file ?

The `.gitignore` file in a Git repository is used to tell Git which files or directories to 
ignore and not track. 

   - **Ignore a Specific File**:
      
     my_file.txt
      

   - **Ignore All `.log` Files**:
      
     *.log
      

   - **Ignore All Files in a Directory**:

     /directory_to_ignore/

_________________________________________________________________________________________

Tasks :

crated pull request : https://github.com/Brilworks-Interns/mern/pull/4
Practice Github commads : https://github.com/Sejal-brilworks/Gihub-test


