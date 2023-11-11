# dotfiles
list of my dotfiles for installing my environment on any computer.

### xfce4 config files

install on ubuntu:
```sudo apt install xubuntu-desktop```

#### icons 
- kora
```
mkdir -p ~/.local/share/icons
cp ./kora/
```

go into appearance to then select kora icons

#### Colors and darkmode

appearance > style > yaru-purple-dark


#### Panel

panel > backup and restore > load the panel-config tar file

#### GTK files

```
mkdir -p ~/.config
mv ./gtk-2.0 ~/.config
mv ./gtk-3.0 ~/.config
mv ./gtk-4.0 ~/.config
```

#### zsh
mv ./zshrc ~/ 

#### git
mv ./gitconfig ~/
