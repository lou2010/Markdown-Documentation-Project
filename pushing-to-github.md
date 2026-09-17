# Pushing a File to GitHub
Now that the file has been committed, you are ready to do the final step: pushing the file to the online GitHub repository.  It will be visible depending on the public/private visibility settings you chose when you first created the GitHub repository.

1.	On the command line, enter `git status`.
2.	Confirm the branch you are on. It should say `main`. Some may say `master`, although Git has moved away from using that in favor of `main`.
3.	If `git status` says `main`, enter `git push -u origin main` on the command line. If it says `master`, enter `git push -u origin master` on the command line. 
4.	Go back to GitHub and see that the file you had created has been uploaded from the local Git repository to the remote Git repository.

Congratulations! You finished creating the document and uploading it to GitHub using Git. Learning more about Git would help to add some complexity to your project such as adding multiple documents at once.
