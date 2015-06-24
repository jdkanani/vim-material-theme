# material-theme
Material theme for vim

Based on [Sublime Text 3 Material theme](https://github.com/equinusocio/material-theme) by [@equinusocio](https://github.com/equinusocio)

![VIM screenshot](http://i.imgur.com/VNxcv53.png)

Installation
------------

### Option 1: Manual installation

1.  Move `material-theme.vim` to your `.vim/colors` directory. After downloading the 
    vim script or package:

        $ mv colors/material-theme.vim ~/.vim/colors/

### Option 2: Pathogen installation ***(recommended)***

1.  Download and install Tim Pope's [Pathogen].

2.  Next, move or clone the `vim-material-theme` directory so that it is a subdirectory of the `.vim/bundle` directory.

        $ cd ~/.vim/bundle
        $ git clone https://github.com/jdkanani/vim-material-theme

### Modify .vimrc

After either Option 1 or Option 2 above, put the following two lines in your 
.vimrc:

    syntax enable
    set background=dark
    colorscheme material-theme

or, for the light background mode of Material Theme:

    syntax enable
    set background=light
    colorscheme material-theme
