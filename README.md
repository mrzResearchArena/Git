# Git-GitHub

## Push Files into GitHub

#### Step 2: Generate a socket
```console
rafsanjani@mrz:~$ screen -S anySocketName
```


#### Step #1: Git Initialization
	:~$ 	// 

```console
rafsanjani@mrz:~$ git init
```

**Note:** Initialized empty Git repository in `~PATH/.git/'

###### Step #1.1: Git Reinitialization

```console
rafsanjani@mrz:~$ git init
```
**Note:** If we retype it! Reinitialized existing Git repository in `~PATH/.git/'


#### Step #2: Add files/folders in .git (One-by-one)

:~$ git add a.txt b.sh c.py Deep Vision Machine NLP

	Step#3.1: Add files/folders in .git (All together)
	:~$ git add *
	// We can add all files/folders at a time.

	Step#3.2: Remove files/folders in .git (One-by-one)
	:~$ git rm --cached a.txt b.sh c.py Deep Vision Machine NLP

####  Step #3: Check Current Status
	:~$ git status
	// We can monitor current condition of files/folders.

####  Step #4: Git Commit
	:~$ git commit -m 'Write Something'

####  Step #5: Access Remote GitHub
	:~$ git remote add origin https://github.com/mrzResearchArena/Git-VCS.git
	
	Step#6.1: Fatal Error (Remote GitHub)
	:~$ git remote rm origin

####  Step #6: Push files/folders in GitHub Remotely
	:~$ git push -u origin master --force


--------------------------------------------------------------------------------
Most Frequent Usage:
1. git add *
2. git commit -m 'New Changes'
3. git status
4. git push -u origin master
