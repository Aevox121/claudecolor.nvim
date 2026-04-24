# claudecolor.nvim

A Neovim colorscheme inspired by the Claude website — warm cream/ink paper aesthetic with a terracotta accent. Light and dark variants.

## Install (lazy.nvim)

```lua
{
  "Aevox121/claudecolor.nvim",
  lazy = false,
  priority = 1000,
  config = function()
    vim.cmd.colorscheme("claudecolor-light") -- or "claudecolor-dark" / "claudecolor"
  end,
}
```

## Variants

- `claudecolor-light` — warm cream paper (`#FAF9F5`)
- `claudecolor-dark` — warm dark ink (`#262624`)
- `claudecolor` — follows `vim.o.background`

## Status

Work in progress. Tracked as T-0079 in the parent task system.
