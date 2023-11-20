# Emacs Text Editing & Manipulation Key Bindings (Shortcuts)

## Generic 


* Cut (kill): `C-w`
* Copy (kill-ring-save): `M-w`
* Paste (yank): `C-y`
* Paste next/yank-next: `M-y`
* Indent: `C-x TAB` or `C-M-\`
* Unindent: `C-x r k` or `C-u - C-x TAB`
* Search word under cursor: `M-b C-s C-w` (move to beginning, search, yank)


## word


* kill: M-d
* delete backward: `M-DEL`, `C-backspace`
* capitalize: M-c
* downcase: M-l
* upcase: M-u
* transpose: M-t
* mark: M-@


## line


* kill: `C-k`
* kill backward: `C-u 0 C-k` or `C-0 C-k`
* copy line (no newline): `C-a C-SPC C-e M-w`
* copy line with newline: `C-a C-SPC C-n M-w`



## paragraph


* delete until end: M-k
* delete backward : C-x DEL


## s-expressions


* kill forward: `C-M-k`


Marks


This is a mechanism to work with regions, contiguous text between a mark
(set with `C-SPC` or automatically) and the point.

There are special commands to expanding the region.


Source: <evernote:///view/17667994/s112/34ec1016-ea44-48bf-bf05-ecf666f0433f/3eef4926-7cf7-4de7-b920-ded985c70af5>
