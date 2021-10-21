# PersonalLinux
##Comandos para personalizar o Ubuntu:

´
sudo apt install fonts-hack-ttf

git clone https://github.com/daniruiz/flat-remix

git clone https://github.com/daniruiz/flat-remix-gtk

mkdir -p ~/.icons && mkdir -p ~/.themes

cp -r flat-remix/Flat-Remix* ~/.icons/ && cp -r flat-remix-gtk/Flat-Remix-GTK* ~/.themes/

cp -r flat-remix/Flat-Remix* ~/.icons/ && cp -r flat-remix-gtk/themes/* ~/.themes/

sudo apt install dconf-editor

gsettings set org.gnome.shell.extensions.dash-to-dock extend-height false
gsettings set org.gnome.shell.extensions.dash-to-dock dock-position BOTTOM
gsettings set org.gnome.shell.extensions.dash-to-dock transparency-mode FIXED
gsettings set org.gnome.shell.extensions.dash-to-dock dash-max-icon-size 64
gsettings set org.gnome.shell.extensions.dash-to-dock dash-max-icon-size 48
gsettings set org.gnome.shell.extensions.dash-to-dock dash-max-icon-size 38
gsettings set org.gnome.shell.extensions.dash-to-dock unity-backlit-items true
´
