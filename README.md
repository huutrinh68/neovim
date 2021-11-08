# neovim setting

### Install neovim
```console
sudo apt-get install software-properties-common
sudo add-apt-repository ppa:neovim-ppa/stable
sudo apt-get update
sudo apt-get install neovim
```

### Edit .bashrc
```console
echo "export XTERM=xterm-256color" >> ~/.bashrc
```

### Install vimplug
```console
sh -c 'curl -fLo "${XDG_DATA_HOME:-$HOME/.local/share}"/nvim/site/autoload/plug.vim --create-dirs \
       https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim'
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
