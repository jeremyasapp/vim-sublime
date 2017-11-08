# vim-sublime
An effort to make vim look like sublime.  
Currently supports the following languages:
- Python

## Install

If you don't have one already, create the directory *~/.vim*  
In that directory, copy the *colors* and *syntax* folders from this repository.

In your *~/.vimrc*, paste following lines:

```
syntax on
colorscheme monokai
```

If your temrinal supports true color, add:

```
set termguicolors
```

You are good to go!

## Italic

You can activate or deactivate italics depending on whether your font and your terminal support it.  
To do so, simply add the following to your *~/.vimrc*:

```
let g:monokai_term_italic = 1
```

If you are running through some issues with italics, try the following guide: https://www.reddit.com/r/vim/comments/24g8r8/italics_in_terminal_vim_and_tmux/

## Credits

The base for the monokai theme is taken from: https://github.com/crusoexia/vim-monokai.  
The base for the python syntax highlighting is taken from: https://github.com/kh3phr3n/python-syntax.   


