# Tsodingbuddy

A plain succulent 256-color theme using [colorbuddy], designed to look like Tsoding's emacs theme

[colorbuddy]: https://github.com/tjdevries/colorbuddy.nvim

## Screenshots

### Rust

![tsodingbuddy-ss](media/tsodingbuddy%20ss.png)


## Installation

```vim
" Using vim-plug
Plug 'tjdevries/colorbuddy.vim'
Plug 'tobshub/tsodingbuddy'
lua require('colorbuddy').colorscheme('tsodingbuddy')
```

```lua
-- Using packer
use { 'tobshub/tsoding-buddy', requires = 'tjdevries/colorbuddy.vim' }
require('colorbuddy').colorscheme('tsodingbuddy')
```

## Use with [express_line]

[express_line]: https://github.com/tjdevries/express_line.nvim

Enable the statusline settings in screenshots.

```lua
use { 'tjdevries/express_line.nvim', requires = 'nvim-lua/plenary.nvim' }
vim.g.cactusbuddy_express_line_enabled = true
require('colorbuddy').colorscheme('tsodingbuddy')
```
