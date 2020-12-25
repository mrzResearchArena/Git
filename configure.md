#### 1. See all the Configaration:
```console
user@machine:~$ cat ~/.gitconfig
user@machine:~$ git config --list
```

&nbsp;

#### 2. Set Editor for Commit:
```console
user@machine:~$ git config --global core.editor 'vim'    # love it!
user@machine:~$ git config --global core.editor 'vi'     # ignore it!
user@machine:~$ git config --global core.editor 'nano'   # dafault
```
- Install vim: [download/user guides](https://github.com/mrzResearchArena/IDE/blob/master/vim.md)

&nbsp;

#### 3. Set Alias and Terminal Modification for Branches:
```
# Git Aliasing:
alias gs='git status'
alias gc='git commit'
alias gco='git checkout'
alias gl='git log --oneline'
alias gb='git branch'
alias ga='git add .'

# Git branch in prompt:
parse_git_branch() {
     git branch 2> /dev/null | sed -e '/^[^*]/d' -e 's/* \(.*\)/ (\1)/'
}
export PS1="\u@\h \[\033[32m\]\w\[\033[33m\]\$(parse_git_branch)\[\033[00m\] $ "
```
- Run: **source ~/.myGit**

&nbsp;
