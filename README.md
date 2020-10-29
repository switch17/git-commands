# **Git Commands**

###	**git init**   
-	Initialises an empty git repo with a .git folder

###	**git status** 
-	 Shows the staging area files and untracked files

###	**git add filename.extension**
-	Adds specified file(s) to staging area file to staging area

###	**git  add .**
-	Adds all the files from the current directory to staging area

###	**git commit -m "commit message goes here"**
-	Commits changes to the git repo, -m = message

###	**git log**
-	 Shows the logs of commits made

###	**git diff filename.extension**
-	Shows the differences (changes made)

###	**git checkout filename.extension**
-	Restores the file to its very previous version 

###	**git rm --cached filename.extension**
-	Unstags / Removes the file from the staging area

###	**git rm --cached  -r filename.extension**
-	 \-r => recursive

###	**touch .gitignore**
-	Create a .gitignore  file in main dir, open this file and type filename.extension or folder-name of all the files that you don't wanna add to the git repo, each entry should be on a new line 


## **Creating Remote Repo**

###	**git remote add origin paste-your-repo.url/from.git**
-	Tells local git repo about transferring data to remote repo, also here word 'origin' is name  of remote repo

###	**git push -u origin main**
-	Pushes local repo to remote using u flag to master branch(default)


## **Cloning**

###	**git clone paste-repo.url/from.git**
-	Creates a copy of remote repo on your local machine


## **Branching**

###	**git branch**
-	Shows all the available branches

###	**git branch new-branch-name**
-	Creates new branch 'new-branch-name' (no extension)

###	**git checkout specific-branch-name**
-	Switches from current branch to branch 'specific-branch-name'



## **Merging with master branch (current branch: master)**

###	**git merge branch-name**
-	Merges the branch with master branch, add commit message if needed 
-	( :q! to exit VIM )


## **Forking**
-	Creates a copy of someone else’s repo on remote git account
    1. 	 Search a remote git repository
	2.   Fork it
	3.   Clone it on your local machine
	4.   Make changes
    5.   Commit changes
	6.   Make Pull request
    7.   Resolve merge conflict (if any)
