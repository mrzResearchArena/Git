## Introduction

&nbsp;

#### Step #1: Git initialization
```console
user@machine:~$ git init    # Note: Initialized empty Git repository in ~PATH/.git/
```

&nbsp;

#### Step #2: Adding files, and directories into Git
```console
user@machine:~$ git add anyName.txt anyName.sh anyName.py DeepLearning MachineLearning Bioinformatics NLP     # Note: Adding One-by-One
user@machine:~$ git add *    # Note: Or, we can use "git add ."; we can add all {files, directories} at the same times.
```

&nbsp;

#### Step #3: Remove files, and directories from Git
```console
user@machine:~$ git add rm --cached anyName.txt anyName.sh anyName.py DeepLearning MachineLearning Bioinformatics NLP    # Note: Remove One-by-one
user@machine:~$ git add rm --cached *    # Note: Remove all Together
```

&nbsp;

####  Step #4: Check current status
```console
user@machine:~$ git status    # Note: We can monitor current condition of files and directories.
```

&nbsp;

####  Step #5: Git commit
```console
user@machine:~$ git commit -m 'Write Something' # Note: Save the files and directories.
```

&nbsp;

####  Step #6: Prepare to Send ( Push ) Information to GitHub

```console
user@machine:~$ git remote add origin https://github.com/anyUserName/anyName.git    # Trying to access remotely GitHub repository
user@machine:~$ git remote rm origin    # Fix the fatal err when trying to access remotely GitHub repository
```

&nbsp;

####  Step #7: Push information to GitHub (Local PC --> GitHub)
```console
user@machine:~$ git push -u origin master --force # Note: Dangerious Commands, remote all existances and add new.
```

&nbsp;

####  Step #7: Rename
```console
user@machine:~$ git mv <oldFileName> <newFileName>
user@machine:~$ git mv anyName.fasta anyName.fasta
```
