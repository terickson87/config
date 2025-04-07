# config

https://www.atlassian.com/git/tutorials/dotfiles

`alias config='/usr/bin/git --git-dir=$HOME/.cfg/ --work-tree=$HOME'`

`git clone --bare <git-repo-url> $HOME/.cfg`

`config config --local status.showUntrackedFiles no`
