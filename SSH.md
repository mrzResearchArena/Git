### Set Environment: Password, Username, Utilities:

&nbsp;

#### Step #1: Generate SSH Key:
```console
user@machine:~$ ssh-keygen    # Note: In "/home/user/.ssh" location there will be at least two files {id_rsa, id_rsa.pub}.
```

&nbsp;


- ##### Step #1.1: Fixed the SSH Key Error (Optional):
  ```console
  user@machine:~$ ssh-add ~/.ssh/id_rsa    # Note: Fixed the fatal error when "git clone".
  ```

&nbsp;

#### Step #2 Set Key to GitHub Repo as Password:
Setting (right side) --> SSH and GPG keys (left side) --> Then add the `id_rsa.pub` information into the box.

&nbsp;


#### Step #3: Set the Username and Email:
```console
user@machine:~$ git config --global user.name 'your username'
user@machine:~$ git config --global user.email 'your email'
user@machine:~$ cat ~/.gitconfig   # Ensure the setup
user@machine:~$ git config --list  # Ensure the setup (Optional)
```

&nbsp;
&nbsp;

Acknowledgement:
>1. [Mohammad Ashikuzzaman](https://github.com/ashikuzzaman-ar/), who teaches me the concept.
