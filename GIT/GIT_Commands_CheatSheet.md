#GIT Essential Commands
1. **git init** - 
      This will initiate the git repository. 
      
2. **git clone** - 
     This will clone the remote repository to the local machine.
     
3. **git config --global uer.name 'username'** - 
    This will configure the global username for the git.

4. **git config --global user.mail 'test@test.com'** - 
    This will configure the global user email for the git.
    
5. **git config --global --list** -
    This will list the configured user name and email for the git
    
6. **git add filename** - This will add the file name to the staged area of the git

7. **git add * ** - This will add all the files which are not tracked to the staged area of the git

8. **git add . ** - This will add all the files which are not tracked to the staged area of the git which are in current directory.

9. **git commit -m 'commit message'** - This will commit the files which are in staged area

10. **git commit -m -a 'commit message'** - This will commit the files which are tracked, ignore the status of the stage

11. **git status** - This will list all the tracked, staged, modified files in the local repository

12. **git diff** - This will show the difference of the working version with the staged version

13. **git diff --staged** - This will show the difference between the staged version and last commit version

14. **git add <param>** :-  Use the Params as **filename**, ***.filetype** - This will add the untracked files to the git 

15. **git reset** - This will reset the files to last commit. It will keep the untracked and tracked file changes

16. **git reset --soft** - Thiw will reset the files to last commit and preserve the  untracked and tracked file changes

17. **git reset --hard** - This will reset the files to last commit and discard all the untracked and staged changes.

18. **git stash** - This will stash the staged changes. Stashed changes are temporary area where you can keep your changes if someone else wanted to work on your repository.

19. **git stash pop** - This will pop/apply the stashed changes back to your respository. Only the staged files cann be added to the stash.

20. **git stash apply** - This is same as **git stash pop** . When you have more than one stash, during reapply of the changes will come as **last in first out(LIFO)**

21. **git stash list** - This will list the current stash. 

22. **git branch** - This will show the branch details

23. **git branch mybranch** - This will create a new branch named mybranch

24. **git checkout -b newbranch** - This will create a new branch and checkout th branch

25. **git branch -d delbranch** - This will delete the branch

26. **git merge mybranch** - This will merge the mybranch changes to the current checkedout branch

27. **git merge --abort** - This will abort the merge which is happening 

28. **git remote -v** - This will show the current configured remote branch

29. **git remote set origin <giturl>** - This will set the remote repository
