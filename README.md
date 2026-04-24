# claudecolor.nvim

A Neovim colorscheme inspired by the Claude website — warm cream/ink paper aesthetic with a terracotta accent. Light and dark variants.

## Install (lazy.nvim)

```lua
{
  "Aevox121/claudecolor.nvim",
  lazy = false,
  priority = 1000,
  config = function()
    vim.cmd.colorscheme("claudecolor-dark") -- or "claudecolor-light" / "claudecolor"
  end,
}
```

## Variants

- `claudecolor-light` — warm cream paper (`#FAF9F5`)
- `claudecolor-dark` — warm dark ink (`#262624`)
- `claudecolor` — follows `vim.o.background` (defaults to dark when unset)

## Status

Work in progress. Tracked as T-0079 in the parent task system.
