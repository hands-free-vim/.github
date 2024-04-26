# Hands Free Vim 

Collection of projects for controlling [neovim](https://neovim.io/) with [Talon](https://talonvoice.com/) and [Cursorless](https://github.com/cursorless-dev/cursorless). You can also find us on the Talon voice [Slack](https://talonvoice.com/chat) in the #vim channel.

## The Problems

1. Maintaining your own Talon-specific neovim settings/tools is tedious
2. Using a normal terminal from Talon is not great UX; it's not easy to access history, etc
3. Editing/navigating neovim with Talon is tedious
4. No cursorless in neovim

## The Solutions

1. All code related to Talon, neovim (editing and terminal) and cursorless use in 2 repositories: [neovim-talon](https://github.com/hands-free-vim/neovim-talon) and [talon.nvim](https://github.com/hands-free-vim/talon.nvim)
3. Use neovim as your terminal! Easy shell history buffer access in any terminal (zsh on any operating system, Windows terminal, Windows Git bash, etc)
4. Support automatic title updates, tabs, terminal, etc
5. Use cursorless for neovim editing and in any terminal: [cursorless.nvim](https://github.com/hands-free-vim/cursorless.nvim) 

## FAQ

### Is cursorless really going to be supported in neovim?

Yes, beta support has been released in [cursorless.nvim](https://github.com/hands-free-vim/cursorless.nvim). It is without any hats though atm. So you are able to target rows, paints, tokens, etc but no “air” or “blue bat” for now. But it helps a lot already in the terminal. For better text editing experience, it is still recommended to use cursorless in vscode.

### Do I need all the repositories of hands-free-vim?

No, you only need the 3 repositories: [neovim-talon](https://github.com/hands-free-vim/neovim-talon), [talon.nvim](https://github.com/hands-free-vim/talon.nvim) and optionally [cursorless.nvim](https://github.com/hands-free-vim/cursorless.nvim) if you just want to use it. For contributing, the other repositories are useful.
