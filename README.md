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

## speed up 4 github download
```
https://download.fastgit.org/
```
## setup proxy on linux
```
export NO_PROXY=localhost,127.0.0.0/8,*.local
export ALL_PROXY=socks://127.0.0.1:7890
export HTTP_PROXY=http://127.0.0.1:7890
export FTP_PROXY=http://127.0.0.1:7890
export HTTPS_PROXY=http://127.0.0.1:7890
```
## fix http 2.0 error on AUR update
```
git config http.version 1.1
```

## mount apfs disk on linux
```
mount apfs patten on linux
sudo apfs-fuse -o allow_other /dev/sdb1 /home/haruka/apple
```

## docker need iptable install first
```
restart the docker service
```
## install goods on docker
```
sudo docker run -d --name="zk" -p 2181:2181 zookeeper
sudo docker run -d --name="redis" -p 6379:6379 redis
sudo docker run -d --name="rabbit" -p 15672:15672 5672:5672 rabbitmq:3-management
```
## swtich java version on archlinux
```
sudo archlinux-java status
sudo archlinux-java set xxx
```
