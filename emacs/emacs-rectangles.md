# Emacs Rectangles

Complete documentation: [Rectangles](https://www.gnu.org/software/emacs/manual/html_node/emacs/Rectangles.html)

Start rectangle selection: `C- SPC` (`rectangle-mark-mode`). Move the cursor to
the rectangle bottom right corner.

- `C-x r k`  : kill the text of the region-rectangle
- `C-x r M-w`: save the text of the region-rectangle
- `C-x r y`  : yank the text

- `C-x r t string RET`: insert
- `M-x string-insert-rectangle RET string RET`: insert
- `C-x r o`: insert blank space to fill the space of region (pushing existing
    content right)

- `C-x r d`: delete 
- `C-x r c`: clear the region-rectangle by replacing all of its contents with
    spaces
