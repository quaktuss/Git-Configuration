# Git clone

```bash
git clone https://github.com/quaktuss/Git-Configuration.git
cd Git-Configuration/
```


 ## Set up a commit template by adding `.gitmessage` to `commit.template`


```bash
git config --global commit.template ~/.gitmessage
```

## Configure the default Git editor to use Vim
 ```bash
 git config --global core.editor "vim"
 export GIT_EDITOR=vim
 ```