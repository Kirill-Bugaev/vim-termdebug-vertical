# vim-termdebug-vertical
Patched termdebug.vim plugin with support of vertical split between Source and Debugger windows

## Installation
Replace original termdebug.vim file. Don't forget to make backup copy.

## Options
Force Termdebug opens windows with vertical split
```vim
let g:termdebug_vertsource = 1
```
Place Source window left
```vim
let g:termdebug_leftsource = 1
```
Move focus on Source window after Termdebug is opened
```vim
let g:termdebug_focussource = 1
```
