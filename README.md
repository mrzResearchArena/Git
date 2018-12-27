# Git-GitHub

1.  Step#1.0: Git Initialization
	:~$ git init
	// Initialized empty Git repository in ~PATH/.git/

    Step#1.1: Git Reinitialization
	:~$ git init (If we retype it)
	// Reinitialized existing Git repository in ~PATH/.git/

3.  Step#3.0: Add files/folders in .git (One-by-one)
	:~$ git add a.txt b.sh c.py Deep Vision Machine NLP

	Step#3.1: Add files/folders in .git (All together)
	:~$ git add *
	// We can add all files/folders at a time.

	Step#3.2: Remove files/folders in .git (One-by-one)
	:~$ git rm --cached a.txt b.sh c.py Deep Vision Machine NLP

4.  Step#4.0: Check Current Status
	:~$ git status
	// We can monitor current condition of files/folders.

5.  Step#5.0: Git Commit
	:~$ git commit -m 'Write Something'

6.  Step#6.0: Access Remote GitHub
	:~$ git remote add origin https://github.com/mrzResearchArena/Git-VCS.git
	
	Step#6.1: Fatal Error (Remote GitHub)
	:~$ git remote rm origin

7.  Step#7.0: Push files/folders in GitHub Remotely
	:~$ git push -u origin master --force

--------------------------------------------------------------------------------
Most Frequent Usage:
1. git add *
2. git commit -m 'New Changes'
3. git status
4. git push -u origin master
