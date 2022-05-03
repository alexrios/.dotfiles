# DOTFILES REPO USAGE

### Packages
> cd ~
 
> pacman -S yay

> wget -c https://gist.github.com/865f7f3b92ccc8d5c5f1fe8908cdf936 -o packages.txt

> yay -S --needed --noconfirm - < ~/packages.txt

### Cloning
> cd ~

IF ~/.gitignore not exists THEN
> echo '*' > ~/.gitignore

> git clone --no-checkout git@github.com:alexrios/.dotfiles.git

> cd ~/.dotfiles

> git config core.worktree '../../' 
(because the PWD in this comand is the .git dir)

> git reset --hard origin/main
ALL FILES WILL BE OVERRIDEN ! ! !

### Adding new files
> git add -f ../.vimrc

