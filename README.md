# How to setup 
1. Clone this repository
2. Run `install.sh`
3. Open up new window to initiate `zsh` shell

# Manual install after the script
1. install node.js and npm 
`sudo apt-get install nodejs` 
`sudo apt install npm`
2. update npm to lastest version to use coc and its extension for neovim
`nvm list-remote`
`nvm install (Latest LTS: Fermium)`
3. install ranger 
`sudo apt-get install ranger`
4. go to ranger dir under .dotfiles and stow the ranger config
`stow ranger`
 
# Solutions to common errors
Error: vim-hexokinase needs updating
1. Install Go
`sudo apt-get install golang`
2. Remove vim-hexokinase dir under plugged dir
3. reinstall hexokinase in the vim

Referernce: [Jake Wiesler](https://www.youtube.com/watch?v=70YMTHAZyy4&list=PL1C97G3GhlHdANMFUIXTcFr14R7b7EBj9)
