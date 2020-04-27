# install

homebrew

```sh
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

commandline tools

```sh
brew install \
ansible \
bash \
ddrescue \
dialog \
git \
gnupg \
htop \
inetutils \
ipcalc \
jq \
midnight-commander \
mysql-client \
nmap \
pass \
python \
tor \
wget \
woof \
xz \
youtube-dl
```

start tor service

```sh
brew services start tor
```

applications

```sh
brew cask install \
android-file-transfer \
appcleaner \
arduino \
blueharvest \
burn \
firefox \
garmin-express \
google-chrome \
gpg-suite \
java \
jumpcut \
libreoffice \
menumeters \
onyx \
owncloud \
rar \
skype \
slack \
spotify \
thunderbird \
tor-browser \
transmission \
tuxera-ntfs \
tuxguitar \
viber \
viscosity \
visual-studio-code \
vlc \
vmware-fusion \
whatsapp \
xquartz
```

commandline iStats

```sh
sudo gem install iStats
```

Firefox

```ini
browser.cache.disk.enable -> False
browser.cache.memory.enable -> False
network.dnsCacheExpiration -> 0
```

Thunderbird

```ini
mailnews.default_news_sort_order -> 2
mailnews.default_news_sort_type -> 18
mailnews.default_sort_order -> 2
mailnews.default_sort_type ->18
mail.server.default.offline_download -> False
mail.server.default.autosync_offline_stores -> False
mail.identity.default.reply_on_top -> 1
mail.identity.default.compose_html -> True
mail.server.default.check_all_folders_for_new -> True
```

Firewall disable/enable 0/1

```sh
sudo defaults write /Library/Preferences/com.apple.alf globalstate -int 0
```
