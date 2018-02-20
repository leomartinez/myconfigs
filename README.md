# Configuraciones personales

Este es un conjunto de configuraciones personales para el entorno de trabajo que fui descubriendo con el tiempo.

Hay configuraciones tanto de sistema operativo como de aplicaciones que utilizo en el día a día laboral.

## Entorno de trabajo

El sistema operativo que utilizo es [Debian](https://www.debian.org) en su versión **estable**.

## Config de SO

.

## Config de aplicaciones

Algunas aplicaciones permiten una buena personalización.

### Vim/Neovim

**[Vim](http://www.vim.org)** es uno de los editores de consola más utilizados en el universo ___\*nix/Linux___.

En el caso de **[neovim](https://neovim.io)** se trata de, según su web ___literally the future of vim___.

El archivo de configuración se llama [`.vimrc`](archivos/vimrc) y va en el home del usuario ( `$HOME` ). El contenido es el siguiente: 

```
set number
set expandtab
set shiftwidth=4
set softtabstop=4
set tabstop=4
set autoindent
set smartindent
set nocompatible
set nohlsearch
set incsearch
set ruler
set so=7
filetype plugin indent on
colorscheme desert
syntax enable
set laststatus=2
set statusline=%F%m%r%h%w\ [FORMAT=%{&ff}]\ [TYPE=%Y]\ [ASCII=\%03.3b]\ [HEX=\%02.2B]\ [POS=%04l,%04v][%p%%]\ [LEN=%L]
let perl_extended_vars=1
```

El archivo descargado se debe renombrar a `.vimrc` 
