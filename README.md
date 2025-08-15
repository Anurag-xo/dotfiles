# My Dotfiles

![image](https://github.com/user-attachments/assets/115f941e-18c2-412e-bd6a-e05f01117c0a)

Welcome to my personal dotfiles repository. This collection of configuration files is tailored for a productive and visually appealing development environment. It primarily features configurations for Neovim, Zsh, Tmux, and Wezterm.

## What's Inside?

This repository contains configurations for the following tools:

- **Neovim**: A highly customized Neovim setup with a modern and clean UI, extensive plugin support, and LSP integration.
- **Zsh**: A powerful and user-friendly shell configuration with Zinit for plugin management, Powerlevel10k for a stunning prompt, and various plugins for enhanced productivity.
- **Tmux**: A terminal multiplexer configuration that's both functional and easy to use, with plugins for session management and a custom theme.
- **Wezterm**: A GPU-accelerated terminal emulator with a clean, minimalist design and a custom color scheme.

## Prerequisites

Before you begin, ensure you have the following installed:

- [Git](https://git-scm.com/)
- [Stow](https://www.gnu.org/software/stow/)
- [Zsh](https://www.zsh.org/)
- [Neovim](https://neovim.io/)
- [Tmux](https://github.com/tmux/tmux)
- [Wezterm](https://wezfurlong.org/wezterm/)
- A [Nerd Font](https://www.nerdfonts.com/) (the configuration uses `MesloLGS Nerd Font Mono`)

## Installation

1.  **Clone the repository**:

    ```bash
    git clone https://github.com/your-username/dotfiles.git ~/.dotfiles
    ```

2.  **Navigate to the repository**:

    ```bash
    cd ~/.dotfiles
    ```

3.  **Use Stow to create symlinks**:

    Stow is used to manage the symlinks from this repository to your home directory. The configuration is structured to be compatible with Stow.

    ```bash
    stow .
    ```

    This command will create symlinks for all the configuration files in this repository to their respective locations in your home directory.

4.  **Install Tmux plugins**:

    - Start Tmux.
    - Press `Ctrl + a` followed by `I` (uppercase i) to install the plugins.

5.  **Install Neovim plugins**:

    - Start Neovim.
    - The plugins will be automatically installed by `lazy.nvim`.

## Key Features

### Neovim

- **Plugin Manager**: [lazy.nvim](https://github.com/folke/lazy.nvim)
- **Theme**: A custom, clean, and modern look.
- **LSP**: Integrated Language Server Protocol support for intelligent code completion, diagnostics, and more.
- **File Explorer**: [nvim-tree](https://github.com/nvim-tree/nvim-tree.lua) for a modern file explorer.
- **Fuzzy Finder**: [Telescope](https://github.com/nvim-telescope/telescope.nvim) for fast and efficient file searching.
- **Keybindings**: A comprehensive set of keybindings for a seamless workflow. See `KEY_BINDINGS.md` for more details.

### Zsh

- **Plugin Manager**: [Zinit](https://github.com/zdharma-continuum/zinit)
- **Prompt**: [Powerlevel10k](https://github.com/romkatv/powerlevel10k)
- **Plugins**:
  - `zsh-syntax-highlighting`: For syntax highlighting in the shell.
  - `zsh-autosuggestions`: For fish-like autosuggestions.
  - `fzf-tab`: For tab completion with `fzf`.
  - `zoxide`: A smarter `cd` command.

### Tmux

- **Prefix**: `Ctrl + a`
- **Plugins**:
  - `tpm`: Tmux Plugin Manager
  - `vim-tmux-navigator`: For seamless navigation between Vim and Tmux panes.
  - `tmux-resurrect`: Persists Tmux sessions after a computer restart.
  - `tmux-continuum`: Automatically saves sessions.
  - `tmux-tokyo-night`: A custom theme.

### Wezterm

- **Font**: `MesloLGS Nerd Font Mono`
- **Theme**: A custom, minimalist theme with a clean color palette.
- **UI**: A tab-less, decoration-less design for a distraction-free experience.

## Contributing

Feel free to open an issue or submit a pull request if you have any suggestions or improvements.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.