# General

> Some settings and tools that I'm using in every platform.

## Insomnia

> Similar to Postman, but it's free and may be a bit simpler.

[Download from here](https://insomnia.rest/download)

## Font

[Download font from here](https://www.jetbrains.com/lp/mono/)

## NeoVim

My NeoVim configuration that I'm using currently can be found in the following repository: [ducktordanny/nvim-config](https://github.com/ducktordanny/nvim-config)

```sh
# install neovim for example on mac os
brew install neovim

# install ripgrep since it will be needed for telescope
brew install ripgrep

cd ~/.config/nvim # you may need to create this folder
git clone git@github.com:ducktordanny/nvim-config.git .
```

It uses lazy.nvim to manage the plugins, and just to mention some of the plugins that I'm using to give a hint:

- nvim-treesitter/nvim-treesitter
- nvim-telescope/telescope.nvim
- jose-elias-alvarez/null-ls.nvim
- neovim/nvim-lspconfig
- nvim-tree/nvim-tree.lua
- akinsho/bufferline.nvim

And many more, checkout the repo if you're interested.

## VSCode Extensions

Settings can be found in the [`./vscode/settings.json`](./vscode/settings.json) file.

- Angular Language Service
- Better Comments
- Bracket Pair Colorizer
- colorize
- ES7 React/Redux/GraphQL/React-Native snippets
- Simple React Snippets
- ESLint
- Prettier - Code formatter
- HTML Biscuits
- indent-rainbow
- Live Share
- Markdown Preview Enhanced
- PostCSS Language Support
- Power Mode
- Pylance
- Tailwind CSS IntelliSense
- Community Material Theme (Ocean High Contrast)
- background

## WebStorm

[From toolbox](https://www.jetbrains.com/toolbox-app/)

Extensions:

- Material Theme UI (Darker Themes > Oceanic Theme)
- Power Mode II
- Rainbow Brackets
- Wallaby
- Prettier
- Indent Rainbow
- Atom Material Icons

Background:

> Most of the pictures that I use can be found in the `./images` folder
