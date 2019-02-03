# vim-termdebug-vertical
Patched termdebug.vim plugin (Last Update: 2018 Jun 3) with support of vertical split between Source and Debugger windows

## Installation
If last update of your termdebug.vim is newer, don't install. Otherwise replace original termdebug.vim file (/usr/share/vim/vim81/pack/dist/opt/termdebug/plugin/termdebug.vim on my system). Don't forget to make backup.

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
Disable debug toolbar
```vim
let g:termdebug_disable_toolbar = 1
```

## Other
Source window id is reflected in `g:termdebug_sourcewin` variable.

`g:Termdebug_InstallWibar()` is wrapper for `s:InstallWibar()` function.

`g:Termdebug_RemoveWibar()` removes Termdebug wibar of current window.
