# google-style-vim
A collection of vim settings to help you format code correctly.

## Installation
Vim has a very nice built-in way to organize and manage language-specific options by breaking them out into files 
and directories.  

The quick way to get started is to move all the language-specific stuff from your `~/.vimrc` file into 
a file named:  

  `~/.vim/ftplugin/language.vim` (e.g. `~/.vim/ftplugin/python.vim`)   
    
If you like most of what vim's filetype plugin is doing, but you want to override something specific,
you can place your settings in (recommended):   

  `~/.vim/after/ftplugin/language.vim` (e.g. `~/.vim/after/ftplugin/python.vim`)   
    
Finally, you need to have file type detection enabled. You should add following command to your `~/.vimrc`:    

  `filetype plugin indent on`.
