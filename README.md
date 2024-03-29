# Personal Dotfiles for programs run on my Macbook

The goal is to organize all of my dotfiles in a version
controlled folder and **symlinked** into place using a script.

## Install Homebrew formulae and casks

When setting up a new Mac, you may want to install some common Homebrew items.

```
./brew.sh
```

Some of the functionality of these dotfiles depends on formulae installed by `brew.sh`.

## Configure NeoVim

Link the nvim config to a spot that nvim expects.

`ln ~/dotfiles/nvim ~/.config/nvim`

## Resources

[dotfiles: Your unofficial guide to dotfiles on GitHub](https://dotfiles.github.io/tutorials)
[Managing Your Dotfiles](https://www.anishathalye.com/2014/08/03/managing-your-dotfiles/)


<!-- TODO(rylan): To update OhMyZSH, run `"$ZSH/tools/upgrade.sh"` then overwrite the oh-my-zsh folder in dotfiles dir. Then symlink? Should this even be tracked? -->

