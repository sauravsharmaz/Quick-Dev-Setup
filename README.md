# ðsublime-settings
a simple config for sublime text 4

```

{
	"color_scheme": "Monokai.sublime-color-scheme",
	"theme": "Default.sublime-theme",
	"ignored_packages":
	[
		"Vintage",
	],
	"font_face": "Fira Code Medium",
	"font_options":
	[
	    "gray_antialias",
	    "subpixel_antialias"
	],
	"font_size": 15,
	"line_padding_top": 1,
	"auto_complete": true,
}


```

# Install Zsh Guide
```
https://www.tecmint.com/install-zsh-in-ubuntu/
```
# Oh-my-zsh theme ð´
```
sh -c "$(wget -O- https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

# HomeBrew 
```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```
# CopyQ
```
https://linuxhint.com/install-copyq-ubuntu/
```
# Albert ð
```
https://albertlauncher.github.io/installing/
```
# OBS
```
sudo apt install obs-studio
```
# VLC ð½
```
sudo apt install vlc
```
# Other Required Softwares
```
Chrome
Choco + Node
7-Zip
Brave
Notion
Postman
power toys
telegram
Trello
FireFox
VS Code
Sublime
```
# generate SSH Keys ð
```
ssh-keygen -t ed25519 -C "saurav@example.com"
```
## add agent ðµï¸
```
eval "$(ssh-agent -s)"
ssh-add ~/.ssh/id_ed25519
```
# ð® Steam
```
sudo apt install steam-installer
```
# JAVA â
```
https://www.digitalocean.com/community/tutorials/how-to-install-java-with-apt-on-ubuntu-18-04
```
# Node
```
sudo apt install nodejs
```
# Brightness config
## Step up:
```
gdbus call --session --dest org.gnome.SettingsDaemon.Power --object-path /org/gnome/SettingsDaemon/Power --method org.gnome.SettingsDaemon.Power.Screen.StepUp
```

## Step down:
```
gdbus call --session --dest org.gnome.SettingsDaemon.Power --object-path /org/gnome/SettingsDaemon/Power --method org.gnome.SettingsDaemon.Power.Screen.StepDown
```

## Hyper Terminal

```
https://hyper.is/
```
## Install these required packages
```
curl -sL https://deb.nodesource.com/setup_16.x -o /tmp/nodesource_setup.sh
sudo bash /tmp/nodesource_setup.sh
sudo apt install nodejs
npm install --global pure-prompt
git clone https://github.com/zsh-users/zsh-syntax-highlighting.git
hyper i hyper-mac-controls
```

## Make Ubuntu Dock Show only windows Indicators from Current WorkSpace
```
gsettings set org.gnome.shell.extensions.dash-to-dock isolate-workspaces true
```

## WSL Ubuntu Network Error solution
```
https://askubuntu.com/questions/1248825/how-can-i-fix-internet-connection-issues-on-wsl2#:~:text=Follow%20the%20steps%3A%201%20Right%20click%20on%20your,checkbox%20specifying%20IPv6%20connection%2C%20uncheck%20it.%20img.%20
```
```
https://support.purevpn.com/how-to-disable-ipv6-linuxubuntu
```







