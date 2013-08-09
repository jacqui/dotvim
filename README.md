# ~/.vim

These are my vim dotfiles. While I wrote a small amount of the code here, it's mostly the work of the inimitable Tim Pope. I thank him for the vim-fu.

## Setup 

```
cd
git clone git@github.com:jacqui/dotvim.git .vim
ln -s ~/.vim/.vimrc ~/.vimrc
ln -s ~/.vim/.vimrc.local ~/.vimrc.local
cd .vim
git submodule init
git submodule update
```

## Note

I tried to keep my setup functional for both regular and gui versions of vim, but frankly they're best when used in macvim. 


