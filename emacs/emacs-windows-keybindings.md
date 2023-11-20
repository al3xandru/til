# Emacs Windows and Keybindings

[Windows](https://www.gnu.org/software/emacs/manual/html_node/emacs/Windows.html)

## Splitting Windows

`C-x 2` (`split-window-below`): create split below

`C-x 3` (`split-window-right`): create split to the right

## Use Other Window

`C-x o` (`other-window`)

## Disaply in another Window

`C-x 4 b` bufname

`C-x 4 f` filename

`C-x 4 r` filename: visit file read-only

`C-x 4 d` directory 

`C-x 4 C-o` bufname display buffer without trying to select it

## Deleting Windows

`C-x 0`: delete selected window (`delete-window`)

`C-x 1`: delete all windows in the selected frame except selected window
(`delete-other-windows`)

`C-x 4 0`: delete window and kill buffer (`kill-buffer-and-window)

## Resizing Windows

`C-x ^`: taller

`C-x }`: wider

`C-x {`: narrower

`C-x -`: conditional shrink

`C-x +`: make all windows same height

## Move Windows

Windowmove package defines:

- movement commands like `windmove-right`
- window movement commands like `windmove-swap-states-[up,down,left,right]`


### Scroll other window

`C-M-v` `scroll-other-window`: scroll next window upward

`C-M-S-v` or `scroll-other-window-down`: scroll next window down

`C-M-S-l` or `recenter-other-window`: recenter other window

## Winner mode

winner mode is a minor mode that records the changes in the window
configuration.

Toggle winner mode: `M-x winner-mode`

`C-c left` (`winner-undo`): undoes the last window configuration change
