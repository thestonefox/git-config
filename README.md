git-config
==========

* cd user home directory `cd ~/`
* Git clone `git clone git@github.com:thestonefox/git-config.git`
* Symlink .gitconfig `ln -s git-config/.gitconfig ~/.gitconfig`
* Symlink .gitignore `ln -s git-ignore/.gitignore ~/.gitignore`
* Run helpers.sh to get git shortcuts `./helpers.sh`

Helpers
-------

The following alias shortcuts can be added by running `helpers.sh`

* gitl1 -n = shortcut for `git log --oneline -n` [usage: gitl1 -5]
* gits = shortcut for git status
* gitb = shortcut for git branch

Single Config Command
```
cd ~/ && git clone git@github.com:thestonefox/git-config.git && ln -s git-config/.gitconfig ~/.gitconfig && ln -s git-ignore/.gitignore ~/.gitignore && ./git-config/helpers.sh && source ~/.bashrc
```
