# another_dotfiles_repository

<!--toc:start-->
- [another_dotfiles_repository](#anotherdotfilesrepository)
  - [Overview](#overview)
  - [Whats inside](#whats-inside)
    - [Terminal](#terminal)
    - [IDE](#ide)
<!--toc:end-->

## Overview

That is a configuration collection for using in different *nix based environments.
It based on tools and guides that availabvle in the net.

Published only for storing and accessing it outside of the private networks.

## Whats inside 

### Terminal 

The work mostly related with living in console so the terminal is a crucial part.
At the moment of writting my terminal is hyper.js. It might be changed in future.

Configuration is available here: [terminal](terminal/hyper/config/hyper.js)
To make it work properly it require patched Nerd font: [font](terminal/fonts/README.md)

### IDE

As a terminal IDE the choice is NeoVim, because ... well just wanted to try it out.
Result is amazing, the guide of how it works and why you can get here: [youtube_course](https://www.youtube.com/watch?v=zHTeCSVAFNY&list=PLsz00TDipIffreIaUNk64KxTIkQaGguqn)
My configuration is slightly deviated with some personal requireements that comes from job specific and vscode experience.


### Shell 

As a shell using `zsh`.
1. Install [guide](https://github.com/ohmyzsh/ohmyzsh/wiki/Installing-ZSH)
2. Install ohmyzsh [guide](https://github.com/ohmyzsh/ohmyzsh?tab=readme-ov-file#basic-installation)
3. Copy the zsh profile from `terminal/zsh/.zshrc` to your home dir

#### Shell theme 

As a theme is used powerlevel10k. How to install use it you can find [here](https://github.com/romkatv/powerlevel10k)

#### Aliases

Few aliases used:
- terraform [guide](https://github.com/zer0beat/terraform-aliases)
- kubectl [guide](https://github.com/ahmetb/kubectl-aliases)


TODO:
- add aliases instalation as a confgiguration
- do the same with shell theme
- add an automation for cli tool instalation required for nvim like black, terraform, etc.
- automation for fonts install
- look at [dotbot](https://github.com/anishathalye/dotbot) as a potentual automation tool
