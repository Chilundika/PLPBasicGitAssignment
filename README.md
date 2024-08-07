
### Assignment Objective:

In this assignment, we were expected to gain some practical experience whilst learning the foundation of how things work on GitHub. Namely;
how to create a repository, link the folder on the GitHub to the folder in a local drive, commit and push changes made to the files.

### Steps Taken:

1. **GitHub Repository Creation:**
- I signed in to my GitHub account.
- Generated a new repository and gave it a name "PLPBasicGitAssignment".
- Created it with a README file as the first entry.

2. **Local Folder Setup:**
- Started a new folder on the current machine and named it as "PLPBasicGitAssignment".
- I opened the terminal and went into created folder performing the command "cd path/to/PLPBasicGitAssignment".

3. **Git Initialization:**
- Creates a new git repository at the local folder using the command **git init**.

4. **Connecting to GitHub:**
- Linked the local repository to the GitHub repository with the command:- Linked the local repository to the GitHub repository with the command:

**git remote add origin https://github.com/Chilundika/PLPBasicGitAssignment.git**


5. **Creating a File:**
- Saved a new text file with a name "hello. txt" and added the text "Hello, Git!" to it using:txt and added the text "Hello, Git!" to it using:

write Hello, Git! to the file hello. txt


6. **Committing Changes:**
- Staged the changes using:- Staged the changes using:

**git add hello. txt**

- Committed the changes with the message "Add hello. txt with a greeting" using:- Committed the changes with the message "Add hello. txt with a greeting" using:
  
**git commit -m “Added hello. txt, a file containing a greeting”**


7. **Renaming Branch:**
- Renamed the "master" branch to "main" using:- Renamed the "master" branch to "main" using:

To rename the current branch locally to main and ensure the online head points to it **git branch -m master main**


8. **Pushing to GitHub:**
- Attempted to push the committed changes to GitHub using:- Attempted to push the committed changes to GitHub using:
  
git push using the upstream repository with the branch main.


### CHALLENGES ENCOUNTERED:

1. **Branch Name Issue:**
- Originally, the branch name was going to be “master” instead of “main.”


2. **Push Rejection Error:**
- Encountered an error while pushing changes due to differences in local and remote repositories:- Encountered an error while pushing changes due to differences in local and remote repositories:

**The Error Message**
error: did not manage to force-update some refs to ‘https://github. com/Chilundika/PLPBasicGitAssignment. git’
hint: They stated that updates were rejected because the remote contains work that you do not want.
hint: have locally. This is usually as a result of another repository pulling on it or pushing into it;
hint: the same ref. Using this, you can integrate the changes done on the remote branch, which is,
hint: can the student please pull using the ‘‘git pull’’ command before pushing again.
hint: Read a brief ‘Note about fast-forwards’ in the ‘git push — help’ section.


3. **Merge Refusal Error:**
- Encountered an error while merging due to unrelated histories:- Encountered an error while merging due to unrelated histories:

fatal: excluding those incidents that are unrelated to each other.


### SOLUTION TO CHALLENGES:

1. **Branch Name Issue:**
- Renamed the "master" branch to "main" using:- Renamed the "master" branch to "main" using:
  
**git branch -m master main**


2. **Push Rejection Error:**
- Fetched the latest changes from the remote repository using:- Fetched the latest changes from the remote repository using:

**git fetch origin**

- Tried to synchronize the marks of the remote ‘main’ branch with the marks of the local ‘main’ branch and faced the conflict stating different histories.

3. **Merge Refusal Error:**
- Merged the remote "main" branch into the local "main" branch using the "--allow-unrelated-histories" flag:- Merged the remote "main" branch into the local "main" branch using the "--allow-unrelated-histories" flag:

**git merge origin/main --allow-unrelated-histories**

- Resolved any merge conflicts, committed the changes, and then successfully pushed the local "main" branch to GitHub using:- Resolved any merge conflicts, committed the changes, and then successfully pushed the local "main" branch to GitHub using:

**git push -u to the remote under the branch main**


### Verification:

- Confirmed that both "hello. txt" and "README. pull requests that use .md" files in the ‘main’ branch in the GitHub framework.

Consequently, the assignment objective was fulfilled, and all the considered issues were addressed while following these steps.

