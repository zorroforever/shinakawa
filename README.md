# shinakawa
品川ワークス

## proxy
```
export http_proxy=http://127.0.0.1:1087
export https_proxy=$http_proxy
source ~/.zshrc
```
## on my zshのインストール
```
sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```
## brewのインストール
 ```
 /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"
 ```
## neovimのインストール
```
brew install neovim
```
## deinのインストール
```
cd ~/
curl https://raw.githubusercontent.com/Shougo/dein.vim/master/bin/installer.sh > installer.sh
mkdir ~/.cache/dein
sh ./installer.sh ~/.cache/dein
~/.config/nvim/init.vim
```
## ctagsのインストール
```
brew install --HEAD universal-ctags/universal-ctags/universal-ctags
```
