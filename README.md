# dotfiles

WIP


## Installation

### Homebrew

Install [Homebrew](https://brew.sh) and dependencies:

```bash
brew tap homebrew/bundle
brew bundle
```

### ZSH

Removes .zshrc from $HOME (if it exists) and symlinks the .zshrc file from the .dotfiles

```bash
ln -sf $HOME/.dotfiles/.zshrc $HOME/.zshrc
```

### VS Code (after installation)

```bash
ln -sf $HOME/.dotfiles/vscode/settings.json $HOME/Library/Application\ Support/Code/User/settings.json
ln -sf $HOME/.dotfiles/vscode/keybindings.json $HOME/Library/Application\ Support/Code/User/keybindings.json
ln -sf $HOME/.dotfiles/vscode/snippets/ $HOME/Library/Application\ Support/Code/User/snippets
````
