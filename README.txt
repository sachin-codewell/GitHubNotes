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

--> git add <filename> - to move file from Working area to staging area.
--> git rm --cached <filename> - to move file from to staging area to working area.
--> git add .|| git add -A - fot all the file.

--> commit - particular version of your project.Take snapshot of files in staged area and
             make version of a project out of it.





