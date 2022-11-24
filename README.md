# My . Files

I decided to put my .files on here to easily move them between machines.

```
sudo apt install zsh mosh tmux curl -y 
```
Set shell to ZSH
```
chsh -s $(which zsh)
```

clone repo
```
git clone 
```

install ruby and gem

`sudo apt install ruby gem -y`

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

Install homebrew
```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```
Install colorls

`gem install colorls`


Tmux 
```
$ git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm
```
Changed binding to `Ctrl+SPACE`