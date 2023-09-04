--> To make a folder -  mkdir <folder name>.
--> To move from one folder to another folder -  cd ./name(child) || cd ..(parent).
--> git init - make a repo and will also create a .git file which has all the relevant logic for 
version control.
--rm -rf .git - will delete the repo means now we cant control the project through git. and will
delete the .git file.
--> To see all available folder and file -  ls || ls -a.
--> To create a file inside a folder -  touch <filename>.

--> Working area - all the files/folder in local machine and not handled by git.
   - Staged area/Tracked area - all the files/folders and code changes that are going to be part of
    of next version will be put in stage area.
   - Repository area - contains all the history of your previous version.Also contains all
    the version of your project.

--> git add <filename> - to move file or changes from Working area to staging area.
--> git rm --cached <filename> - to move file from to staging area to working area.
--> git add .|| git add -A - fot all the file.

--> commit - particular version of your project.Take snapshot of files in staging area and
             make version of a project out of it.
--> git log - to see the list of all commit.

Note - when any file is in the staging area and you make any changes in that file, then that changes will
       reflect in working area

--> git restore <filename> - remove all the changes from file which is in staging area but 
                             not commited(remove changes from working area).

--> Note - if any changes is made into a file(staging area) then that change first goes into
    working area anf after git add it goes into staging area.  

--> to remove changes from staging area - git restore --staged <filename>.  
                                          this command will move changes from staging area
                                          to working area and after that we can remove that changes
                                          using git restore.                             

--> diff between git rm and git restore - if you want to move whole file to untracked state then go for- git rm
                                          otherwise if you want to move changes to stage area or working area the go for - git restore.

--> git diff commit1id commit2id - will show all the changes between to commit.

--> git remote  - show all the remote connection.

--> Remote connection - helps to connect two repo to share the file and data.

--> git remote add <remotename> <remote url> - to add the local repo to remote repo.

--> git remote rm <remotename> - will delete the connection between two repo.

--> git remote rename <oldname> <newname> - will rename the remote connection.

--> git push <remote connection name> master  - to push the code from local repo to remote repo.
    git push origin master