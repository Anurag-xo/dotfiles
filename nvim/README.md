# Neovim Keybindings

This document lists all the keybindings used in the Neovim setup.

---

## General Keybindings

| Keybinding   | Description                           |
| ------------ | ------------------------------------- |
| `<leader>`   | Set to `<Space>` (default leader key) |
| `jk`         | Exit insert mode                      |
| `<leader>nh` | Clear search highlights               |
| `<leader>+`  | Increment number under cursor         |
| `<leader>-`  | Decrement number under cursor         |

---

## Window Management

| Keybinding   | Description                    |
| ------------ | ------------------------------ |
| `<leader>sv` | Split window vertically        |
| `<leader>sh` | Split window horizontally      |
| `<leader>se` | Make splits equal size         |
| `<leader>sx` | Close current split            |
| `<leader>sm` | Maximize/restore current split |

---

## Tab Management

| Keybinding   | Description                  |
| ------------ | ---------------------------- |
| `<leader>to` | Open new tab                 |
| `<leader>tx` | Close current tab            |
| `<leader>tn` | Go to next tab               |
| `<leader>tp` | Go to previous tab           |
| `<leader>tf` | Open current file in new tab |

---

## File Explorer (nvim-tree)

| Keybinding   | Description                        |
| ------------ | ---------------------------------- |
| `<leader>e`  | Toggle file explorer               |
| `<leader>ef` | Open file explorer at current file |
| `<leader>ec` | Collapse file explorer             |
| `<leader>er` | Refresh file explorer              |

---

## Telescope (Fuzzy Finder)

| Keybinding   | Description                |
| ------------ | -------------------------- |
| `<leader>ff` | Find files                 |
| `<leader>fs` | Find string in project     |
| `<leader>fr` | Find recently opened files |
| `<leader>fc` | Find word under cursor     |

---

## LSP (Language Server Protocol)

| Keybinding   | Description               |
| ------------ | ------------------------- |
| `gd`         | Go to definition          |
| `gD`         | Go to declaration         |
| `gr`         | Find references           |
| `gi`         | Go to implementation      |
| `K`          | Show documentation        |
| `<leader>ca` | Code actions              |
| `<leader>rn` | Rename symbol             |
| `<leader>rs` | Restart LSP server        |
| `]d`         | Go to next diagnostic     |
| `[d`         | Go to previous diagnostic |

---

## Git Integration (gitsigns)

| Keybinding   | Description                  |
| ------------ | ---------------------------- |
| `]h`         | Go to next hunk              |
| `[h`         | Go to previous hunk          |
| `<leader>hs` | Stage hunk                   |
| `<leader>hu` | Undo stage hunk              |
| `<leader>hr` | Reset hunk                   |
| `<leader>hS` | Stage buffer                 |
| `<leader>hR` | Reset buffer                 |
| `<leader>hb` | Blame line                   |
| `<leader>hB` | Toggle blame for entire file |
| `<leader>hd` | Open diff                    |

---

## Commenting

| Keybinding    | Description                    |
| ------------- | ------------------------------ |
| `gc` + motion | Comment/uncomment lines        |
| `gcc`         | Comment/uncomment current line |

---

## Snippets and Auto-Completion

| Keybinding | Description                          |
| ---------- | ------------------------------------ |
| `<C-j>`    | Move down in completion menu         |
| `<C-k>`    | Move up in completion menu           |
| `<C-e>`    | Close completion menu                |
| `<C-q>`    | Send selected items to quickfix list |

---

## Trouble (Diagnostics)

| Keybinding   | Description                |
| ------------ | -------------------------- |
| `<leader>xx` | Toggle Trouble             |
| `<leader>xw` | Show workspace diagnostics |
| `<leader>xd` | Show document diagnostics  |
| `<leader>xt` | Show to-do comments        |

---

## LazyGit

| Keybinding   | Description  |
| ------------ | ------------ |
| `<leader>lg` | Open LazyGit |

---

## Miscellaneous

| Keybinding   | Description                  |
| ------------ | ---------------------------- |
| `<leader>mp` | Format current file or range |
| `<leader>l`  | Trigger linting manually     |
| `<leader>ws` | Save session                 |
| `<leader>wr` | Restore session              |
