# MyConfig
Install neovim
```
git clone https://github.com/neovim/neovim
cd neovim && make -j4
sudo make install
```
Install vim-plug
```
mkdir -p ~/.config/nvim/autoload ~/.config/nvim/plugged
sh -c 'curl -fLo ~/.config/nvim/autoload/plug.vim --create-dirs \
       https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim'
cp init.vim ~/.config/nvim/init.vim
```
Install nodejs
```
curl -sL install-node.vercel.app/lts | bash
```
Open neovim by cmd nvim and the enter the command below:
```
:PlugInstall
```

Install coc.nvim extensions like:
```
:CocInstall coc-json coc-tsserver
```


