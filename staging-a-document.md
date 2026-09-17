# Staging a Document
Once you have a working file in your local repository to upload, you have to stage the file in Git. Staging a file makes it ready to be committed. What makes the file staged is the Git command `git add`. 
1.	Make any changes to your file in VS Code and save it (Ctrl+S).
2.	Open Git Bash.
3.	Direct Git to the local Git repository on your computer.
4.	On the command line, type `ls` to see what files are in your folder. Confirm the file you are looking to stage is in there.
5.	On the next command line write `git add` followed by your file name.
6.	Write `git status` to see whether the file is ready to be committed.
7.	Look for `Changes to be committed:` where your file name should be below it. Your file is now ready to be committed.
If your file name contains a space, add quotation marks. For example, the command could look like this: `git add "Practice File.md"`.
