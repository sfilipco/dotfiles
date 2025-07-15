# dotfiles

Configuration files managed using [chezmoi](https://www.chezmoi.io/).

## Requirements

Brew. Then:

```
touch ~/.zshrc.local
brew install \
  MisterTea/et/et \
  alacritty \
  chezmoi \
  fd \
  fzf \
  gh \
  ghostty \
  neovim \
  npm \
  nushell \
  ripgrep \
  rust \
  rust-analyzer \
  tmux \
  tpm

```

## Tmux

Install plugins with `C-A I`.
Start session with `tmux $TMUX_OPTIONS new-session -As auto`.

## Neovim

Using [LazyVim](https://www.lazyvim.org/).
