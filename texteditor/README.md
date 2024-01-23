# NeoVIM

<!--toc:start-->
- [NeoVIM](#neovim)
  - [Instal action](#instal-action)
  - [Package manager](#package-manager)
  - [Directory tree](#directory-tree)
  - [Code highlight](#code-highlight)
<!--toc:end-->

Here you can find some explanation of the used plugins

## Instal action

Install [nvim](https://github.com/neovim/neovim/blob/master/INSTALL.md)

Amazon Cloudshell install:
```bash
#!/usr/bin/env bash
sudo yum groups install -y Development\ tools
sudo yum install -y cmake
sudo yum install -y python34-{devel,pip}
sudo pip-3.4 install neovim --upgrade
(
cd "$(mktemp -d)"
git clone https://github.com/neovim/neovim.git
cd neovim
make CMAKE_BUILD_TYPE=Release
sudo make install
)
cp /usr/local/bin/nvim ~/.local/bin/
```

## Package manager

[Lazy](https://github.com/folke/lazy.nvim)

## Directory tree

[Neo-tree](https://github.com/nvim-neo-tree/neo-tree.nvim)

## Code highlight

[Tree-sitter](https://github.com/nvim-treesitter/nvim-treesitter)


