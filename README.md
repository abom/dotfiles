# dotfiles

these are my current system configurations 

## structure

every root directory in this repo is for specific application and all files underneath are to be linked relative to the home dir e.g ( PATH/TO/DOTFILES/i3/.config/i3/config    -> /home/USERNAME/.config/i3/config )


## using the configurations

- fork the repo
- install [stow](https://www.gnu.org/software/stow/) or [nistow](https://github.com/xmonader/nistow) to manage these dotfiles
- cd repo dir && stow dir


## deps
- rofi
- i3lock 


## keybindings

- alt+w: finding window
- alt+r: rofi launcher 
- alt+k: process killer
- alt+m: math evaluator
- alt+l: lock screen
- alt+s: duckduckgo search
- alt+a: all rofi apps
- alt+shift+q: close window