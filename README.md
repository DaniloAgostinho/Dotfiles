# Dotfiles

This project using bash-it by [Bash-it](https://github.com/Bash-it/bash-it)



#### ALIAS PERSONALIZADOS

###### .bash_profile ==========================================================================

```bash
if [ -f "${HOME}/.bashrc" ] ; then
  source "${HOME}/.bashrc"
fi

alias turn_on='cd $USERPROFILE/vm && vagrant up && vagrant ssh'
```

###### .bashrc ==========================================================================

```bash
#ALIAS PERSONALIZDOS
alias master='git checkout master'
alias pull='git pull'
alias del='git branch -D'
alias create='git checkout -b'
alias troca='git checkout'
alias br='git branch'
alias reset='git reset HEAD'
alias co='git checkout'
alias st='git status'
alias del_file='rm -rf'
alias del_dolder='rm -r'
alias project='cd credenciado-medico && git checkout master && git pull'
alias turn_off='vagrant halt && exit'
alias prod='docker start amil-apache && docker start amil-weblogic'
alias apache='docker start amil-apache'
alias weblogic='docker start amil-weblogic'
alias merge='git merge'
alias vm='cd credenciado-medico'
alias push='git push'
alias run='docker-npm run build-front'
alias containers='docker ps'
alias restart='docker stop amil-weblogic && docker stop amil-apache && docker start amil-weblogic && docker start amil-apache'

```
