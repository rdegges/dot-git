# dot-git

My Git dotfiles.

These are personalized for my own usage, but you can use them however you'd
like.


## Installation

The below commands will download the project, and setup Git.


``` bash
sudo apt install git hub
git clone git@github.com:rdegges/dot-git.git ~/Drive/Sync/Dotfiles/git
ln -s ~/Drive/Sync/Dotfiles/git/gitconfig ~/.gitconfig
git config --global user.email "r@rdegges.com"
git config --global user.name "Randall Degges"
```
