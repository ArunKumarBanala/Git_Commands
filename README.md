# Git_Commands
List of Commonly used Git commands

Getting & Creating Projects:
----------------------------
    Command	                                                    Description
------------------------------------------------------------------------------------------------------------------------------
    git init	                                                 Initialize a local Git repository
    git clone ssh://git@github.com/[username]/
        [repository-name].git	                                 Create a local copy of a remote repository
    
Basic Snapshotting:
-------------------
    Command	                                                    Description
-------------------------------------------------------------------------------------------------------------------------------
    git status	                                                 Check status
    git add [file-name.txt]	                                     Add a file to the staging area
    git add -A	                                                 Add all new and changed files to the staging area
    git commit -m "[commit message]"	                         Commit changes
    git rm -r [file-name.txt]	                                 Remove a file (or folder)
    
Branching & Merging:
--------------------
    Command	                                                    Description
----------------------------------------------------------------------------------------------------------------------------------
    git branch	                                                 List branches (the asterisk denotes the current branch)
    git branch -a	                                             List all branches (local and remote)
    git branch [branch name]	                                 Create a new branch
    git branch -d [branch name]	                                 Delete a branch
    git push origin --delete [branchName]	                     Delete a remote branch
    git checkout -b [branch name]	                             Create a new branch and switch to it
    git checkout -b [branch name] origin/[branch name]	         Clone a remote branch and switch to it
    git checkout [branch name]	                                 Switch to a branch
    git checkout -	                                             Switch to the branch last checked out
    git checkout -- [file-name.txt]	                             Discard changes to a file
    git merge [branch name]	                                     Merge a branch into the active branch
    git merge [source branch] [target branch]	                 Merge a branch into a target branch
    git stash	Stash                                            changes in a dirty working directory
    git stash clear	                                             Remove all stashed entries

Sharing & Updating Projects:
----------------------------
    Command	                                                    Description
----------------------------------------------------------------------------------------------------------------------------------
    git push origin [branch name]	                             Push a branch to your remote repository
    git push -u origin [branch name]	                         Push changes to remote repository (and remember the branch)
    git push	                                                 Push changes to remote repository (remembered branch)
    git push origin --delete [branch name]	                     Delete a remote branch
    git pull	                                                 Update local repository to the newest commit
    git pull origin [branch name]                                Pull changes from remote repository
    git remote add origin ssh://git@github.com/[username]/
      [repository-name].git	                                     Add a remote repository
    git remote set-url origin ssh://git@github.com/[username]/
      [repository-name].git	                                     Set a repository's origin branch to SSH

Inspection & Comparison:
------------------------
    Command	                                                    Description
------------------------------------------------------------------------------------------------------------------------------------
    git log	                                                     View changes
    git log --summary	                                         View changes (detailed)
    git diff [source branch] [target branch}	                 Preview changes before merging
    
-- ===================================================================================================

# Sample Git Commands:

1.Create folder in our Local system(STEM)

2. Clone the repository into local machine folder
    
    $ git clone https://arunbanala@bitbucket.org/stems-classes.git

3. Goto that folder
    
    $ cd stems-classes

4. Goto the branch(dev) from master
    
    $ git checkout dev

5. Initialize the existing Git repository in D:/STEMS/stems-classes/.git/

    $ git init

6. Adding all the files to the repository

    $git add .

7. Commiting the code to repository

    $git commit -m "initial commit"

8. push all the files to central repository

    $git push -u origin --all

----------------------------------------------------------------------

->To download records from Github to local machine

1.Launch git bash in the folder where we want to store or send the file

2. git init

3. git clone https://github.com/ArunKumarBanala /ArunKumar Banala.github.io.git


->To send files from local machine to the github repository to the particular branch.

1. git remote add origin https://github.com/ArunKumarBanala /ArunKumarBanala.github.io.git

2. git status

3. git pull origin master

4. git status

5. git add -A  

    this is to add all files to the github into particular branch

6. git commit -a -m "updated pages"

7. git status

8. git push --set-upstream origin master (to store into server)
    
    Git push
---------------------------------

Everyday tasks in Company

1. git pull

2. git checkout -b 'practice_Angularjs' (to create branch)

3. git push --set-upstream origin practice_Angularjs  (to update automatically in the server while doing in the local system)










