# Neovim Configuration

This repository contains my personal Neovim configuration. Neovim is a highly extensible text editor built on the Vim text editor.

## Installation

1. Clone this repository to your local machine:

   ```shell
   git clone https://github.com/your-username/nvim-config.git
   ```

2. Install Neovim (if not already installed). Refer to the official Neovim documentation for installation instructions.

3. Copy the configuration files to the appropriate location:

   ```shell
   cp -r nvim-config/* ~/.config/nvim/
   ```

4. Launch Neovim synchronize plugin with packer.

   ```vim
   :PackerSync
   ```

5. Check installed LSPs.
   ```vim
   :Mason
   ```

## Features

- Syntax highlighting for various programming languages (You can include your favorite anytime)
- Code linting and formatting
- Autocompletion
- Custom key mappings
- Plugin management with Packer
- Clean design
- File explorer with nvim tree
- Github integration
- Auto-pairing

## Customization

Feel free to customize the configuration to suit your needs. The main configuration file is located at `~/.config/nvim/init.vim`. You can add or remove plugins, change key mappings, and modify settings according to your preferences.

## Contributing

If you have any suggestions or improvements, feel free to open an issue or submit a pull request.
