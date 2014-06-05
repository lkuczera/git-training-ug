git-training-ug
===============

Hacking git for fun and profit!

Start with:
- git config --global  push.default current
- export PS1="\w:\$(__git_ps1)$ "

Install bash-completion & git-completion if __git_ps1 is not found on your system.

** Updating your fork **
```
git remote add lkuczera git@github.com:lkuczera/git-training-ug.git
git checkout master
git pull lkuczera
```
- now is time for fun, resolve conflicts

```
git status
git add .
git commit -a
git push origin master 
```

