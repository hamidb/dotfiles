# Dotfiles

## Vim
### 1. Install 
#### Install Vim with Python Support

```
cd /tmp && git clone https://github.com/vim/vim.git && cd vim

./configure --with-features=huge \
--enable-multibyte \
--enable-pythoninterp=yes \
--enable-python3interp=yes \
--enable-cscope \ 
--prefix=/usr/local

make && sudo make install
```
### 2. Setup
#### Setup NeoBundle

1. 
```
curl https://raw.githubusercontent.com/Shougo/neobundle.vim/master/bin/install.sh > install.sh
sh ./install.sh
```

2. Make sure `vi` is linked to `vim` and `~/.vimrc` is being sourced.
3. Launch vim, run `:NeoBundleInstall`
