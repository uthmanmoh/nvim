# My NeoVim Configuration

This set of configuration was taken from [LazyVim](https://github.com/LazyVim/LazyVim) and modified to my liking.

![Neovim Start](./assets/Neovim.png)

![Neovim editing](./assets/TextEditing.png)

![Neovim Search](./assets/Telescope.png)

## Installation

- Install nvim. On macOS, you can use Homebrew:
```bash
brew install neovim
```
- Clone this repository to `~/.config/nvim`:
```bash
git clone https://github.com/uthmanmoh/nvim ~/.config/nvim
```

- Setup a [Nerd Font](https://www.nerdfonts.com/). I use JetBrainsMono Nerd Font. You can install it using
```bash
brew tap homebrew/cask-fonts
brew install --cask font-jetbrains-mono-nerd-font
```
- Make sure you set the font in your terminal emulator to the Nerd Font you installed, and restart the terminal.
- You may also need to install these tools for certain things to work:
```bash
brew install ripgrep fzf fd
```
See [ripgrep](https://github.com/BurntSushi/ripgrep) and [fzf](https://github.com/junegunn/fzf) for more information.

- Start neovim:
```bash
nvim
```
