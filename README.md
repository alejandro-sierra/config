#config

creamos la carperta .config/nvim/init.vim
le introducimos estos datos:

set runtimepath^=~/.vim runtimepath+=~/.vim/after
let &packpath=&runtimepath
source ~/config/.vimrc


Ahrora instalamos el ejecutador de plug:
https://github.com/junegunn/vim-plug

y por ultimo instalamos los pluggins.
