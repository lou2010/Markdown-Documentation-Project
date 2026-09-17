# Connecting to a Repository Remotely 
Now that you have a repository set up and you have Git on your computer, the two have to be linked so that you have a remote connection between the local Git repository on your computer and the GitHub repository. After following these directions, you will have that connection between your local Git repository and your GitHub repository. 
Before starting, click on the repository to get the url for its structure. The structure will typically be set up like this: `https://github.com/<GitHub account name>/<repository name>.git`.  You should pull this from the GitHub website so it can be correctly entered on the Git command line.
In Git, you have to direct the command line to the folder where the file you had created in the previous lesson is located. It was suggested to use the desktop as getting there is easiest. This tutorial will guide you to that file for this tutorial.
1.	Open GitBash.
2.	On the command line write `cd desktop` to direct Git to your desktop where the file has been saved.
3.	Enter in `cd` followed by the folder that holds your file. This directs Git to what will be the local Git repository that will be connected.
4.	Write `git init` to convert your folder to a local Git repository. You must do this step when the command line is in the intended folder.
5.	Put this command into the command line: `git remote add origin`. On that same line, paste in the URL for your GitHub repository from the GitHub website. This command creates the connection between the local Git repository on your desktop and GitHub repository.
6.	Press Enter.
7.	Enter this on the command line: `git remote -v`. If you receive two lines that say `origin` followed by the GitHub URL, and “fetch” on one line and “push” on the other, this means that you have successfully configured a remote connection.
At this point, you have made a file, created a GitHub account, a GitHub repository, and now have a remote connection between your local computer and GitHub. Now the next step is to do a commit.
