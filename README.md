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

  
