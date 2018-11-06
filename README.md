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
rm -rf $HOME/.zshrc
ln -s $HOME/.dotfiles/.zshrc $HOME/.zshrc
```

### VS Code (after application has been installed)

```bash
ln -s $HOME/.dotfiles/vscode/settings.json $HOME/Library/Application\ Support/Code/User/settings.json
ln -s $HOME/.dotfiles/vscode/keybindings.json $HOME/Library/Application\ Support/Code/User/keybindings.json
ln -s $HOME/.dotfiles/vscode/snippets/ $HOME/Library/Application\ Support/Code/User/snippets
````
