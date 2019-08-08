## Multiple Users Remotely Collaboration

#### Step #1: Clone a Project from the GitHub Repo (Local PC <-- GitHub Repo)
```console
user@machine:~$ git clone git@github.com:username/project.git    # Note: Initialized in very first time for a particular project. 
```

&nbsp;
&nbsp;


##### Step #2: Push to the GitHub Repo (Local PC --> GitHub Repo)
```console
user@machine:~$ git push -u orgin master    # Note: Merge with the project
```

&nbsp;
&nbsp;

##### Step #3: Pull from the GitHub Repo (Local PC <-- GitHub Repo)
```console
user@machine:~$ git pull    # Note: This is will act `git clone`; but, `git pull` ensure the upgraded GitHub Repo.
```
&nbsp;
&nbsp;
&nbsp;

Acknowledgement:
1. [Mohammad Ashikuzzaman](https://github.com/ashikuzzaman-ar/)
