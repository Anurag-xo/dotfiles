# Built-in Vim Commands

This document lists **only the built-in Vim commands** that are part of the default Vim functionality.

---

## Navigation

| Command    | Description                            |
| ---------- | -------------------------------------- |
| `h`        | Move cursor left                       |
| `j`        | Move cursor down                       |
| `k`        | Move cursor up                         |
| `l`        | Move cursor right                      |
| `w`        | Move to the start of the next word     |
| `b`        | Move to the start of the previous word |
| `e`        | Move to the end of the next word       |
| `0`        | Move to the start of the line          |
| `$`        | Move to the end of the line            |
| `gg`       | Move to the start of the file          |
| `G`        | Move to the end of the file            |
| `Ctrl + o` | Jump to previous location              |
| `Ctrl + i` | Jump to next location                  |

---

## Editing

| Command    | Description                                   |
| ---------- | --------------------------------------------- |
| `i`        | Enter insert mode before the cursor           |
| `a`        | Enter insert mode after the cursor            |
| `I`        | Enter insert mode at the start of the line    |
| `A`        | Enter insert mode at the end of the line      |
| `o`        | Insert a new line below and enter insert mode |
| `O`        | Insert a new line above and enter insert mode |
| `x`        | Delete character under the cursor             |
| `dd`       | Delete current line                           |
| `yy`       | Yank (copy) current line                      |
| `p`        | Paste after the cursor                        |
| `P`        | Paste before the cursor                       |
| `u`        | Undo last change                              |
| `Ctrl + r` | Redo last change                              |
| `.`        | Repeat last command                           |

---

## Searching and Replacing

| Command          | Description                                             |
| ---------------- | ------------------------------------------------------- |
| `/pattern`       | Search forward for a pattern                            |
| `?pattern`       | Search backward for a pattern                           |
| `n`              | Go to the next search result                            |
| `N`              | Go to the previous search result                        |
| `:%s/old/new/g`  | Replace all occurrences of `old` with `new` in the file |
| `:%s/old/new/gc` | Replace all occurrences with confirmation               |

---

## File and Buffer Management

| Command     | Description                           |
| ----------- | ------------------------------------- |
| `:e <file>` | Open a file                           |
| `:w`        | Save current file                     |
| `:w <file>` | Save current file as `<file>`         |
| `:q`        | Quit current window                   |
| `:q!`       | Force quit without saving             |
| `:wq`       | Save and quit                         |
| `:qa`       | Quit all windows                      |
| `:qa!`      | Force quit all windows without saving |
| `:bn`       | Go to the next buffer                 |
| `:bp`       | Go to the previous buffer             |
| `:bd`       | Delete current buffer                 |
| `:ls`       | List all buffers                      |

---

## Window Management

| Command         | Description                                 |
| --------------- | ------------------------------------------- |
| `:sp <file>`    | Split window horizontally and open `<file>` |
| `:vsp <file>`   | Split window vertically and open `<file>`   |
| `Ctrl + w + h`  | Move to the left window                     |
| `Ctrl + w + j`  | Move to the window below                    |
| `Ctrl + w + k`  | Move to the window above                    |
| `Ctrl + w + l`  | Move to the right window                    |
| `Ctrl + w + =`  | Make all windows equal size                 |
| `Ctrl + w + _`  | Maximize current window height              |
| `Ctrl + w + \|` | Maximize current window width               |
| `Ctrl + w + c`  | Close current window                        |

---

## Visual Mode

| Command    | Description                        |
| ---------- | ---------------------------------- |
| `v`        | Enter visual mode (character-wise) |
| `V`        | Enter visual mode (line-wise)      |
| `Ctrl + v` | Enter visual mode (block-wise)     |
| `y`        | Yank (copy) selected text          |
| `d`        | Delete selected text               |
| `c`        | Change selected text               |
| `>`        | Indent selected text               |
| `<`        | Unindent selected text             |

---

## Marks and Registers

| Command        | Description                        |
| -------------- | ---------------------------------- |
| `m<letter>`    | Set a mark at the current position |
| `<letter>`     | Jump to a mark                     |
| `'<letter>`    | Jump to the line of a mark         |
| `:marks`       | List all marks                     |
| `"<register>y` | Yank text into a register          |
| `"<register>p` | Paste text from a register         |
| `:reg`         | List all registers                 |

---

## Miscellaneous

| Command                 | Description                             |
| ----------------------- | --------------------------------------- |
| `:set number`           | Show line numbers                       |
| `:set nonumber`         | Hide line numbers                       |
| `:set relativenumber`   | Show relative line numbers              |
| `:set norelativenumber` | Hide relative line numbers              |
| `:set wrap`             | Enable line wrapping                    |
| `:set nowrap`           | Disable line wrapping                   |
| `:set hlsearch`         | Highlight search results                |
| `:set nohlsearch`       | Disable search highlighting             |
| `:set paste`            | Enable paste mode (disable auto-indent) |
| `:set nopaste`          | Disable paste mode                      |
| `:help <topic>`         | Open help for a specific topic          |
