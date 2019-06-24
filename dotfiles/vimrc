" plugins
call plug#begin('~/.vim/plugged')
Plug 'flazz/vim-colorschemes'
Plug 'vim-airline/vim-airline'
Plug 'vim-airline/vim-airline-themes'
Plug 'Yggdroot/indentLine'
Plug 'townk/vim-autoclose'
call plug#end()

" visuals
syntax on
filetype plugin indent on
set t_Co=256
colorscheme molokai_dark
let g:airline_theme='simple'

highlight LineNr ctermfg=8 ctermbg=none

" transparent bg
highlight Normal ctermbg=none
highlight NonText ctermbg=none

:let mapleader = ";"

" numbering
set number
"set relativenumber
set cursorline " highlight current line
highlight CursorLine term=bold cterm=bold ctermbg=black

"highlight OverLength ctermbg=red ctermfg=white guibg=#592929
"match OverLength /\%81v.\+/

set backspace=indent,eol,start

:set shiftwidth=2
:set autoindent
:set smartindent

filetype indent on " load filetype-specific indent files
set wildmenu " visual autocomplete for command menu
set showmatch " highlight matching [{()}]
set incsearch " search as characters are entered
set hlsearch " highlight matches

let g:tex_conceal = ""

" move vertically by visual line
nnoremap <Down> gj
nnoremap <Up> gk

" air-line
set laststatus=2
let g:airline_powerline_fonts=1
let g:airline#extensions#whitespace#mixed_indent_algo=1

"" if !exists('g:airline_symbols')
""     let g:airline_symbols = {}
""     endif
""
""     " unicode symbols
""     let g:airline_left_sep = '»'
""     let g:airline_left_sep = '▶'
""     let g:airline_right_sep = '«'
""     let g:airline_right_sep = '◀'
""     let g:airline_symbols.linenr = '␊'
""     let g:airline_symbols.linenr = '␤'
""     let g:airline_symbols.linenr = '¶'
""     let g:airline_symbols.branch = '⎇'
""     let g:airline_symbols.paste = 'ρ'
""     let g:airline_symbols.paste = 'Þ'
""     let g:airline_symbols.paste = '∥'
""     let g:airline_symbols.whitespace = 'Ξ'
""
""     " airline symbols
""     let g:airline_left_sep = ''
""     let g:airline_left_alt_sep = ''
""     let g:airline_right_sep = ''
""     let g:airline_right_alt_sep = ''
""     let g:airline_symbols.branch = ''
""     let g:airline_symbols.readonly = ''
""     let g:airline_symbols.linenr = ''
