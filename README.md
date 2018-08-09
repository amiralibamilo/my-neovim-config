Requirements:
you need to have nodejs installed

Run the following commands:
install neovim
```
sudo apt-get install neovim
```
create nvim config
```
mkdir ~/.config/nvim && cd ~/.config/nvim
```
install vim plug
```
curl -fLo ~/.local/share/nvim/site/autoload/plug.vim --create-dirs \
    https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim
```
open nvim and enter :PlugInstall
