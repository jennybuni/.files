# My . Files

I decided to put my .files on here to easily move them between machines.

```
sudo apt install zsh mosh tmux curl -y 
```
Set shell
```
chsh -s $(which zsh)
```

Install Ohmyzsh
```
sh -c “$(wget -O- https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)”
```
Install plugins
```
git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions

git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting
```
Starship prompt
```
curl -fsSL https://starship.rs/install.sh | zsh
```


Tmux 
```
$ git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm
```
Changed binding to `Ctrl+SPACE`