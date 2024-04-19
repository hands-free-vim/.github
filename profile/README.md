# Hands Free Vim 

Collection of projects for controlling [neovim](https://neovim.io/) with [Talon](https://talonvoice.com/) and [Cursorless](https://github.com/cursorless-dev/cursorless). You can also find us on the Talon voice [Slack](https://talonvoice.com/chat) in the #vim channel.

## The Problems

1. Maintaining your own talon-specific neovim settings/tools is tedious
2. Using a normal terminal from Talon is not great UX; it's not easy to access history, etc
3. Editing/navigating neovim by vocie with Talon is tedious
4. No cursorless in neovim

## The Solutions

1. All code related to Talon, neovim (editing and terminal) and cursorless use in 2 repositories: [talon.nvim](https://github.com/hands-free-vim/talon.nvim) and [neovim-talon](https://github.com/hands-free-vim/neovim-talon)
3. Use neovim as your terminal! Easy shell history buffer access in any terminal (zsh on any operating system, Windows terminal, Windows Git bash, etc)
4. Support automatic title updates, tabs, terminal, etc
5. Introduce cursorless into neovim ([eventually](https://github.com/cursorless-dev/cursorless/pull/2256))
