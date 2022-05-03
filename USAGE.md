# DOTFILES REPO USAGE

### Cloning
> cd ~

> git clone --no-checkout git@github.com:alexrios/.dotfiles.git

> cd ~/.dotfiles

> git config core.worktree '../../' 
(because the PWD in this comand is the .git dir)

> git reset --hard origin/main
ALL FILES WILL BE OVERRIDEN ! ! !

### Adding new files
> git add -f ../.vimrc

