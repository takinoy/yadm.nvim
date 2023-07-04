# yadm.nvim

Do you manage your dotfiles with [yadm](https://yadm.io)?  
Do you like using the [vim-fugitive](https://github.com/tpope/vim-fugitive)
plugin in neovim?

If the answer to both questions is yes, then yadm.nvim is the plugin for you!

This simple plugin allows you to manage your yadm repo with fugitive in neovim
as if it were any other repository.

## default configuration

```lua
require("yadm").setup({
    yadm_dir = vim.fn.expand("$XDG_DATA_HOME/yadm/repo.git"),
})
```
