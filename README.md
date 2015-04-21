myConfig
========

# Vim 

sudo apt-get install vim

cp .vimrc ~/

git clone https://github.com/gmarik/Vundle.vim.git ~/.vim/bundle/Vundle.vim

* Install Vim Plugins

:PluginInstall

# Tmux 

sudo apt-get install tmux

cp -f .tmux.conf ~/

# Bash (NOT Recommended)

cp -f .bashrc .bash_aliases ~/

# ZSH (Recommended)

sudo apt-get install zsh

* Install oh-my-zsh

wget https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh -O - | sh

chsh -s `which zsh`

cp -f .zshrc .zsh_aliases ~/

source ~/.zshrc

# Idea

File > Import Settings -- settings.jar
