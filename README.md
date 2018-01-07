# vim
thanks shoulinwang help

vim

cd ~ && rm -rf .vim
git clone --recursive https://github.com/RenHuijian/vimrc .vim
ln -s ~/.vim/init.vim .vimrc

gvim

git clone --recursive https://github.com/RenHuijian/vimrc vimfiles
neovim in linux

cd ~ && rm -rf .vim
git clone --recursive https://github.com/RenHuijian/vimrc .vim
ln -s ~/.vim ~/.config/nvim
neovim in windows

cd %USERPROFILE%\AppData\Local
git clone --recursive https://github.com/RenHuijian/vimrc nvim
Plugins

ack.vim
bufexplorer
fzf.vim
fzf
lightline
molokai
nerdtree
plantuml-syntax
python-mode
tagbar
typescript-vim
vim-commentary
vim-fugitive
vim-go
vim-javascript
vim-jdaddy
vim-markdown
vim-repeat
vim-signature
vim-surround
Key Mappings

The leader is ,.

Plugin related mapping

<leader>e :Open Nerdtree
<leader>o :Open FZF
<leader>be :Open Bufexplorer
<F8> :Open Tagbar
<leader>g :Ack Search
