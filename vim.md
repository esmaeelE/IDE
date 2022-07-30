
## nerdtree

`git clone https://github.com/preservim/nerdtree.git ~/.vim/pack/vendor/start/nerdtree

vim -u NONE -c "helptags ~/.vim/pack/vendor/start/nerdtree/doc" -c q`

    set t_Co=256   " This is may or may not needed.
    set background=light
    set background=dark
    colorscheme PaperColor

    nnoremap <leader>n :NERDTreeFocus<CR>
    nnoremap <C-n> :NERDTree<CR>
    nnoremap <C-t> :NERDTreeToggle<CR>
    nnoremap <C-f> :NERDTreeFind<CR>

## color

`git clone https://github.com/NLKNguyen/papercolor-theme.git ~/.vim/pack/colors/start/papercolor-theme`


## debug

`https://docs.python.org/3/library/pdb.html`


python3 -m pdb barname.py

or use `breakpoint()` upper line to put a brakpint


