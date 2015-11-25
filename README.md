# playbook-dev-env

Debian

It does the following:

* Install my .vimrc
* Install oh-my-zsh
* Add oh-my-zsh plugin
* Install fzf
* Add fzf script

# Installation
```
$ ansible-playbook -i hosts -e "user=`whoami` git_username=a git_usermail=a@b.com" site.yml
```
