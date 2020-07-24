# neovim setting

### Install neovim
```console
sudo add-apt-repository ppa:neovim-ppa/stable
sudo apt-get update
sudo apt-get install neovim
```

### Prepare config file
```console
mkdir -p ~/.config/nvim/
mv config/nvim/init.vim ~/.config/nvim/init.vim
```

### PlugInstall
```console
nvim
:PlugInstall
```

### Change comand nvim to vim
```console
echo "alias vim='nvim'" >> ~/.bashrc
source ~/.bashrc
```
