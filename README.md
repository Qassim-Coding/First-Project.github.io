## git Hidden folder

There is a hidden folder called `.git` which tells you that our project is a git repo

Revise commande `git init`

## Reset 
Reset allows you to move staged changes to be unstaged. 
this is useful when you want to revert all files not being committed. 

## cloning

we can clone three ways: Https, SSh, Github cli
Since we are using Github codespaces we'll create a temporary directory in our workspace

## git config file

This gitconfig file is what stores your global configurations for git such as email, name, editor and more.
showing the contents of our .gitconfig file

```
git config --list
```
When you first install git on a machine, you are suppose to set up your name and email. 
```sh
git config --global user.name "John Smith"
git config --global user.email johnsmith@example.com
```
### https

```sh
git clone https://github.com/Qassim-Coding/First-Project.github.io/tree/421161c324df27319ca96dd61a63ce2b35993304 
```
## commit

Make a commit and commit message without opening an editor 
```sh
git commit -m "add another exclamation"
```
## log

git log will show recent git commits to the git tree
