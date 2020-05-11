# shinakawa
品川ワークス

1.proxy

export http_proxy=http://127.0.0.1:1087

export https_proxy=$http_proxy

source ~/.zshrc

2.on my zshのインストール

3.brewのインストール

 /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"
 
4.neovimのインストール

brew install neovim

5.deinのインストール

cd ~/

curl https://raw.githubusercontent.com/Shougo/dein.vim/master/bin/installer.sh > installer.sh

mkdir ~/.cache/dein

sh ./installer.sh ~/.cache/dein

~/.config/nvim/init.vim

6. ctagsのインストール

brew install --HEAD universal-ctags/universal-ctags/universal-ctags

