# Use Kaleidoscope ksdiff for merging

`ksdiff --merge --output final.md edit-jean.md edit-chris.md`

If the base is known, then using `--base` will use the base to track "origin" of
source:

`ksdiff --merge --output final.md --base article.md edit-jean.md edit-chris.md`

How is this used by `git mergetool`?
