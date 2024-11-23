## Step by step

NOTE: SSH key generation isnt part of this tutorial.

## installing zsh and zplug
sudo apt install zsh zplug

## configure zsh as default
chsh -s /bin/zsh

# clone project with modified folder name
git clone git@github.com:LucasHBG/dotfiles ~/.dotfiles

# generate symbolic links
`ln -s ~/.dotfiles/.zshrc ~/.zshrc`

`ln -s ~/.dotfiles/.bashrc ~/.bashrc`

`ln -s ~/.dotfiles/.gitconfig ~/.gitconfig`
