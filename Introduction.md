## Introduction

&nbsp;
&nbsp;

#### Step #1: Git Initialization
```console
user@machine:~$ git init    # Note: Initialized empty Git repository in ~PATH/.git/
```

&nbsp;
&nbsp;

#### Step #2: Adding File(s), and Folder(s) into Git
```console
user@machine:~$ git add anyName.txt anyName.sh anyName.py DeepLearning MachineLearning Bioinformatics NLP     # Note: Adding One-by-One
user@machine:~$ git add *    # Note: Or, we can use "git add ."; we can add all {files, directories} at the same times.
```

&nbsp;
&nbsp;

#### Step #3: Remove File(s), or Folder(s) from Git
```console
user@machine:~$ git add rm --cached anyName.txt anyName.sh anyName.py DeepLearning MachineLearning Bioinformatics NLP    # Note: Remove One-by-one
user@machine:~$ git add rm --cached *    # Note: Remove all Together
```

&nbsp;
&nbsp;

####  Step #4: Check Current Status
```console
user@machine:~$ git status    # Note: We can monitor current condition of files and directories.
```

&nbsp;
&nbsp;

####  Step #5: Git Commit
```console
user@machine:~$ git commit -m 'Write Something' # Note: Save the files and directories.
```

&nbsp;
&nbsp;

####  Step #6: Prepare to Send ( Push ) Information to GitHub

##### Step #6.1: Trying to access remotely GitHub Repository
```console
user@machine:~$ git remote add origin https://github.com/anyUserName/anyName.git
```

##### Step #6.2: Fix Fatal Error when trying to access remotely GitHub Repository
```console
user@machine:~$ git remote rm origin
```

&nbsp;
&nbsp;

####  Step #7: Send ( Push ) Information to GitHub
```console
user@machine:~$ git push -u origin master --force # Note: Dangerious Commands, remote all existances and add new.
```
