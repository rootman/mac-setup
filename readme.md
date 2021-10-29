# Setup Mac

## Reference
http://sourabhbajaj.com/mac-setup/

## Steps

Update System: Apple menu () > About This Mac > Software Update.

```sh
# xcode command line tools
xcode-select --install

# install rosetta 2
softwareupdate --install-rosetta

# install homebrew
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"

# install tools
brew install \
ack \
composer \
git \
php \
zsh

# quicklook plugins
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

# install apps
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

# set zsh as default shell
chsh -s /usr/local/bin/zsh

# install oh my zsh
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"

# install nvm
# https://github.com/nvm-sh/nvm#install--update-script
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.0/install.sh | bash

# install yarn
npm install -g yarn
```
