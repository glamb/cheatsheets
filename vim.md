---
layout: default
title: VIM
---
## Move

`h` - move left

`j` - move down

`k` - move up

`l` - move right

`w` - jump by start of words (punctuation considered words)

`W` - jump by words (spaces separate words)

`e` - jump to end of words (punctuation considered words)

`E` - jump to end of words (no punctuation)

`b` - jump backward by words (punctuation considered words)

`B` - jump backward by words (no punctuation)

`0` - (zero) start of line

`^` - first non-blank character of line

`$` - end of line

`G` - Go To command (prefix with number - 5G goes to line 5)


## Insert

`i` - start insert mode at cursor

`I` - insert at the beginning of the line

`a` - append after the cursor

`A` - append at the end of the line

`o` - open (append) blank line below current line (no need to press return)

`O` - open blank line above current line

`ea` - append at end of word

`Esc` - exit insert mode

## Edit

`r` - replace a single character (does not use insert mode)

`J` - join line below to the current one

`cc` - change (replace) an entire line

`cw` - change (replace) to the end of word

`c$` - change (replace) to the end of line

`s` - delete character at cursor and subsitute text

`S` - delete line at cursor and substitute text (same as cc)

`xp` - transpose two letters (delete and paste, technically)

`u` - undo

`.` - repeat last command


## Delete
## Change