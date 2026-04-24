# claude.nvim

A Neovim colorscheme inspired by the Claude website — warm cream/ink paper aesthetic with a terracotta accent. Light and dark variants.

## Install (lazy.nvim)

```lua
{
  "Aevox121/claude.nvim",
  lazy = false,
  priority = 1000,
  config = function()
    vim.cmd.colorscheme("claude-light") -- or "claude-dark" / "claude"
  end,
}
```

## Variants

- `claude-light` — warm cream paper (`#FAF9F5`)
- `claude-dark` — warm dark ink (`#262624`)
- `claude` — follows `vim.o.background`

## Status

Work in progress. Tracked as T-0079 in the parent task system.
