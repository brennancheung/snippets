Custom snippets for vim
===

With Vundle:

    Plugin 'MarcWeber/vim-addon-mw-utils'
    Plugin 'tomtom/tlib_vim'
    Plugin 'garbas/vim-snipmate'

In `.vimrc`:

    " Snipmate
    imap kj <esc>a<Plug>snipMateNextOrTrigger
    smap kj <Plug>snipMateNextOrTrigger

Installing custom snippets

    mkdir -p ~/.vim/after
    cd ~/.vim/after
    git clone git@github.com:brennancheung/snippets.git

Finish installing

    :PluginInstall
