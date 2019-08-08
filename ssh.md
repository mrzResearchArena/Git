## SSH Key Generator for the Username and Password

&nbsp;
&nbsp;


#### Step #2: Fixed the SSH Key Error
```console
user@machine:~$ ssh-add ~/.ssh/id_rsa    # Note: Fixed the fatal error when "git clone".
```

&nbsp;
&nbsp;

#### Step #1: Generate SSH Key
```console
user@machine:~$ ssh-keygen    # Note: In  location there will be at least two files {id_rsa, id_rsa.pub}.
```

&nbsp;
&nbsp;


#### Step #3: Set Key to GitHub Repo
Setting (right side) --> SSH and GPG keys (left side) --> Then add the `id_rsa.pub` information into the box.

&nbsp;
&nbsp;
&nbsp;
&nbsp;

Acknowledgement:
1. [Mohammad Ashikuzzaman](https://github.com/ashikuzzaman-ar/)
