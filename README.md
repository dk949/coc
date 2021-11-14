# Coc config

To be used with the [neovim config](https://github.com/dk949/nvim)

## Requirements
* nodejs
* npm

## Installation

``` sh
git clone git@github.com:dk949/coc.git $XDG_CONFIG_HOME/coc
cd $XDG_CONFIG_HOME/coc/extensions/
npm i
nvim +'CocStart' +'CocUpdate'
# Exit nvim when all plugins have been updated
```
