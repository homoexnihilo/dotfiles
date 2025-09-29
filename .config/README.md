# Dotfiles

This repo contains my current dotfiles. 


They are tracked using a git bare repo.

This can be made with:

* git init --bare $HOME/.cfg
* alias config='/usr/bin/git --git-dir=$HOME/.cfg/ --work-tree=$HOME'
* config config --local status.showUntrackedFiles no
* echo "alias config='/usr/bin/git --git-dir=$HOME/.cfg/ --work-tree=$HOME'" >> $HOME/.bashrc

taken from (https://www.atlassian.com/git/tutorials/dotfiles)
