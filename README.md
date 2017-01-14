Christian's dotfiles
====================

dotfiles for:
* tmux
* vim

Install
---------
```bash
sudo apt install git powerline
```
### Vim  
```bash
sudo apt install vim  
ln -s ~/src/dotfiles/vimrc ~/.vimrc
```  
#### Vundle  
```bash
git clone https://github.com/VundleVim/Vundle.vim.git ~/.vim/bundle/Vundle.vim
vim -i NONE -c VundleUpdate -c quitall
```
#### YouCompleteMe
```bash
sudo apt install build-essential cmake python-dev python3-dev
cd ~/.vim/bundle/YouCompleteMe
./install.py
```
_might need to add something for the virtualenv_
### tmux
```bash
sudo apt install tmux
```
#### tpm (Tmux Plugin Manager)
```bash
git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm
```
