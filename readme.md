# Setup Mac

## Reference

http://sourabhbajaj.com/mac-setup/

## Steps

### Update System

Apple menu () > About This Mac > Software Update.

### xcode command line tools

```sh
xcode-select --install
```

### rosetta 2

```sh
softwareupdate --install-rosetta
```

### homebrew

```sh
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

### tools

```sh
brew install \
ack \
composer \
git \
php \
zsh
```

### quicklook plugins

```sh
brew install --cask \
qlcolorcode \
qlstephen \
qlmarkdown \
quicklook-json \
qlprettypatch \
quicklook-csv \
betterzip \
webpquicklook \
suspicious-package
```

### apps

```sh
brew install --cask \
1password \
android-file-transfer \
brave-browser \
cheatsheet \
discord \
docker \
dropbox \
figma \
firefox \
google-chrome \
iterm2 \
microsoft-teams \
mongodb-compass \
native-access \
rectangle \
sequel-pro \
slack \
spotify \
toggl-track \
visual-studio-code \
vlc \
alfred \
whatsapp
```

### set zsh as default shell

```sh
chsh -s /usr/local/bin/zsh
```

### install oh my zsh

```sh
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

### nvm

https://github.com/nvm-sh/nvm#install--update-script

```sh
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.0/install.sh | bash
```

### yarn

```sh
npm install -g yarn
```
