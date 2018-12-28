# Git and GitHub

## Process Push Files into GitHub

#### Step #1: Git Initialization
```console
rafsanjani@mrz:~$ git init
```

**Note:** Initialized empty Git repository in ~PATH/.git/

##### Step #1.1: Git Reinitialization
```console
rafsanjani@mrz:~$ git init
```
**Note:** If we retype it! Reinitialized existing Git repository in ~PATH/.git/

&nbsp;
&nbsp;

#### Step #2: Adding File(s) and Folder(s) into Git

##### Step #2.1: Adding One-by-One

```console
rafsanjani@mrz:~$ git add anyName.txt anyName.sh anyName.py DeepLearning MachineLearning Bioinformatics NLP
```

##### Step #2.2: Adding All Together

```console
rafsanjani@mrz:~$ git add *
```
**Note:** We can add all file(s), and folder(s) at a time!

&nbsp;
&nbsp;

#### Step #3: Remove File(s), or Folder(s) from Git

##### Step #3.1: Remove One-by-one

```console
rafsanjani@mrz:~$ git add rm --cached anyName.txt anyName.sh anyName.py DeepLearning MachineLearning Bioinformatics NLP
```

##### Step #3.2: Remove All Together
```console
rafsanjani@mrz:~$ git add rm --cached *
```

&nbsp;
&nbsp;

####  Step #4: Check Current Status
```console
rafsanjani@mrz:~$ git status
```
**Note:** We can monitor current condition of file(s), or folder(s)!

&nbsp;
&nbsp;

####  Step #5: Git Commit
```console
rafsanjani@mrz:~$ git commit -m 'Write Something'
```

&nbsp;
&nbsp;

####  Step #6: Prepare to Send ( Push ) Information to GitHub

##### Step #6.1: Trying to access remotely GitHub Repository
```console
rafsanjani@mrz:~$ git remote add origin https://github.com/anyUserName/anyName.git
```

##### Step #6.2: Fix Fatal Error when trying to access remotely GitHub Repository
```console
rafsanjani@mrz:~$ git remote rm origin
```

&nbsp;
&nbsp;

####  Step #7: Send ( Push ) Information to GitHub
```console
rafsanjani@mrz:~$ git push -u origin master --force
```

&nbsp;
&nbsp;

## Most Frequent Uses:
```console
rafsanjani@mrz:~$ git add *
```
```console
rafsanjani@mrz:~$ git commit -m 'New Changes'
```
```console
rafsanjani@mrz:~$ git status
```
```console
rafsanjani@mrz:~$ push -u origin master 
```
