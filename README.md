# Vim Cheatsheet for myself

Inspired & Sources from [thevaluable.dev](https://thevaluable.dev)

- [Vim for beginners](https://thevaluable.dev/vim-commands-beginner/)
- [Vim for Intermediate Users](https://thevaluable.dev/vim-intermediate/)

## Move

- `%`: move to the matching bracket.
- `CTRL-e`: Scroll the window downwards.

## Text objects

- `diw`: Delete Inside Word
- `cis`: Change Inside Sentence (delete inside sentence and start INSERT mode)
    - A sentence should be ended with "."
- `yip`: Yank(copy) Inside Paragraph

## Buffers

Each buffers match each files. Buffers in Vim are not same with Tabs in other IDEs. Buffers can be hidden(inactive).

- `:buffers` shows buffers list.
- `CTRL-^` switchs to the alternative buffer.
- `:bn` switchs to the Next Buffer.
- `:bp` switchs to the Previous Buffer.

## Windows

Windows in Vim are spaces that show the contents of the buffers. Closing windows does not mean closing buffers.

### New windows
- `:new` creates a new window.
- `CTRL-w s` Splits the current window horizontally. (and opens the same buffer in the new window)
- `CTRL-w v` splits the current window Vertically. (and opens the same buffer in the new window)
- `CTRL-w ^` splits the current window with the alternative buffer.
- `CTRL-w n` splits the current window with the new file edit.

### Move windows
- `CTRL-w r` rotates the window.
- `CTRL-w R` rotates the window reverse.
- `CTRL-w x` exchanges the next window.

## Tabs

Tabs contain windows.

- `:tabnew` or `:tabe` opens a new tab.
- `:tabclose` or `:tabc` closes the current tab.
- `:tabonly` or `:tabo` cloese other tabs. (like clicking the close button with pressing option key in Safari)

- `gt` goes to the next tab.
- `gT` goes to the previous tab.


