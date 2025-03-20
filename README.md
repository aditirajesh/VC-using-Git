# VC-using-Git

## Task 1:
   **Initialize, Commit, and Branch Basics**
    
      - Initialize a new Git repository.
      - Create a few files and commit them.
      - Create a new branch, make changes, and merge it back to the main branch.

   **Soln:**
     
     -Created one file <file1.txt> under task1 folder,
     -two branches <branch1> and <master>, 
     -and merged <branch1> into <master>

## Task 2:
   **Using .gitignore and Tracking Files**
  
    
    - Set up a `.gitignore` file to exclude certain files or directories.
    - Verify that ignored files are not tracked by Git.


  **Soln:**
  
        -Created 3 files, <file2_1.py>, <textfile.txt> - the file to be ignored, and the .gitignore file under task2 folder. - <master> branch
        -added textfile.txt in the .gitignore file
        -used git status to track files being tracked. 

## Task 3:
**Undoing Changes and Reverting Commits**

    - Experiment with undoing changes in your working directory and commits.


  **Soln:**
  
          -Created file <file3_1.txt> under task3 folder - <master> branch
          -made multiple edits and commits 
          -Used git <checkout>/ git restore to restore last commit for unstaged files 
          -For staged files, used git reset to revert to last changes 
          -For undoing commits, used git revert 

## Task 4:
 **Simulating and Resolving Merge Conflicts**
 
    - Create a scenario that produces a merge conflict and resolve it.

 **Soln:**
 
       -Created file <file4_1.txt> under task4 folder - <master> branch
       -Created a commit, and a new branch under it - <4a>
       -went to <file1.txt> under branch <4a> and made changes to some lines 
       -Merged with <master> branch, resolved conflict, then pushed the final text to the remote server. 

## Task 5:
**Interactive Rebasing for Clean Commit History**
  
    - Use interactive rebase to tidy up your commit history.

**Soln:**

    -Created file <file5_1.txt> under task5 folder, <master> branch
    -Created multiple commits with mistakes/high similarity 
    -ran interactive rebase to reword incorrect commits and squash similar commits together
    -pulled from remote server to ensure changes are upto date
    -force pushed commits onto the server.

## Task 6:
**Stashing Changes for Context Switching**
    
    - Learn how to use Git stash to save uncommitted work temporarily.

**Soln:** 

    - Created <file6_1.txt> in task6 folder, under master branch 
    - made commit of the original file and pushed it to remote 
    - made changes to file, added to staging before switching to another branch
    - came back to master branch, used <git stash list> to list stash, <git stash pop> to use the topmost stash 
    and <git stash drop> to drop the top most stash 
    - used git stash apply to apply changes to the working directory, then commited it. 

    ![My Screenshot](https://github.com/user-attachments/assets/741e992d-427c-40bc-905a-7f316b7e9d67)

## Task 7:
**Cherry-Picking Commits Between Branches**
    
    - Selectively apply a commit from one branch to another using cherry-pick.

**Soln:**

    - created <file7_1.txt> under task7 folder, master branch 
    - added lines, staged the file and commited it successfully 
    - switched to branch1
    - cherry picked commit made in master branch and applied it to branch1 
    - pushed changes onto remote server, where branch1 now has <file7_1.txt>
    
## Task 8:
 **Using Git Hooks for Automated Checks**
    
    
    - Set up a Git hook to run scripts (like linters or tests) before commits are finalized.
    
**Soln:**

    - created <commit_msg.py>, <file8_1.py> under task8 folder, master branch 

    for pre-commit hook
    - went to hooks directory under .git and wrote a pre-commit file, checking to see if there are any debugging print commands in the file. if it is present, it will show an error
    - made the file executable and saved it 
    - staged <file8_1.py> and committed, made checks before successfully committing. 

    for commit-msg hook
    - wrote code to check the commit message in the <commit-msg.py> file. it prints out the number of arguments, as well as the arguments of the commit. 
    - linked the <commit-msg.py> file present in the task8 folder with the commit-msg hook present in the hook folder 
    - stage <commit-msg.py> and committed, printed the necessary information. 

## Task 9:
  **Working with Remote Repositories and Collaboration**
   
    - Simulate a collaborative workflow with remote repositories.

  **Soln:**

    - created file <file9_1.txt> in task9 folder, master branch 
    - made changes to file, committed and pushed to remote. 
    - created new branch called feature from master, and made changes to <file9_1.txt>
    - pushed the changes into remote 
    - Compared and pulled request in remote, successfully merging feature into the master branch 
    - pulled the changes from remote onto the local repository


  
