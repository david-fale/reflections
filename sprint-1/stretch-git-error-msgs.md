#Figure 1

1. user is checking the status of git hub
2. user has staged a modified file called "git-track-and-commit-challenge.md"
3. some changes have not been staged these are "deleted: ../git-and-github-deepdive/README.md" and "deleted: git-reflection-tidy-track-challenge.md"

I learned how to check the status of git using "git status" and how important it is. I learned about staging files using "git add <filename>" then commiting them with "git commit -m <message>". Using git status is useful for seeing what files/changes havent been staged before sending commits.

#Figure 2

1. user is checking the status of the fork he made using "git remote -v"
2. user is syncing with the origin repository using "git pull"
3. The automatic merge failed because a file was deleted from the main repository and the user is trying to merge it with the file still on his fork
4. user is checking the status of git 
5. user is in the master branch and has staged 2 files
6. there is an unmerged branch with a deleted file
7. user has not staged a deleted file called " ../git-and-github-deepdive/README.md"

I learned how to fork a repository and why you would want to. Main reasons are for opensource software making it easier to collaborate on projects without giving unnecessary acess to the main repository. You can fork a repo from the github page of the main repository. After you have forked it you can link it to the origin repository using "git remote add origin <link to origin>" then using git pull to sync the repository. I learned how to resolve conflicts manually by deleting or editing the conflicts till it is resolved. 

#Figure 3

1. user has checked the logs to see what has changed on the origin aka the original repository
2. each log has come up with a short description and more info

I learned about how to use the "git log" function to be able to see when changes were made and what the changes were. you can do this using commands such as "git log --oneline" to get a shorter version with less information. "git log -p" to get more information showing the hash info, date, user who made the change, file changed, how much was changed and much more (it even shows the content of the file).



