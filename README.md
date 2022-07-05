# One-vivid

A modified version of [onebuddy](https://github.com/Th3Whit3Wolf/onebuddy)

## Prequisites

Requires neovim version 0.5 or greater

### Getting Started

You have to make sure you install [tjdevries/colorbuddy.vim](https://github.com/tjdevries/colorbuddy.vim) Only termguicolors are supported and that will not change.

#### Vim Plug

```vim
Plug 'tjdevries/colorbuddy.vim'
Plug 'eduhcs/one-vivid'

" And then somewhere in your init.vim, to set the colorscheme
lua require('colorbuddy').colorscheme('one-vivid')
```

### Packer

```lua
use {"eduhcs/one-vivid", requires = "tjdevries/colorbuddy.vim"}
```
