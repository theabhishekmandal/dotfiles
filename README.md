# dotfiles
## Use these commands to make bare repository
git init --bare $HOME/dotfiles
alias config='/usr/bin/git --git-dir=$HOME/dotfiles/ --work-tree=$HOME' (add this alias to .bashrc or .zshrc)
bash
zsh
config config --local status.showUntrackedFiles no

