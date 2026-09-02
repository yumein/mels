 ```
--proxy-server="socks5://127.0.0.1:6767"
 ```
 ```
mkdir -p ~/bin

cat > ~/bin/termux-file-editor << 'EOF'
vim "$1"
EOF

chmod +x ~/bin/termux-file-editor
 ```
 ```
set background=dark

set fileformat=unix
set fileformats=unix,dos

syntax enable

set expandtab
set tabstop=4
set shiftwidth=4
set softtabstop=4

set backspace=indent,eol,start

set autoindent
filetype plugin indent on

set nofoldenable

set belloff=all

set termguicolors

set laststatus=2
set noshowmode
set showcmd
set ruler

set textwidth=0
set nowrap
set sidescroll=1
set sidescrolloff=4

set timeoutlen=1000
set ttimeoutlen=50

set hidden
set confirm
set autowrite
set autoread

set nobackup
set noswapfile

set encoding=utf-8
set fileencoding=utf-8
set fileencodings=utf-8,gb18030

set hlsearch
set incsearch
set ignorecase
set smartcase

 ```
