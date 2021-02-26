# install

homebrew

```sh
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

commandline tools

```sh
brew install \
bash \
ddrescue \
dialog \
git \
gnupg \
gnu-sed \
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
xz
```

start tor service

```sh
brew services start tor
```

pip

```sh
/opt/homebrew/bin/python3 -m pip install mysql-connector ansible
```

Applications

```sh
brew tap homebrew/cask-drivers
brew install --cask \
nextcloud \
whatsapp \
visual-studio-code \
veracrypt \
vlc \
transmission \
tor-browser \
thunderbird \
spotify \
slack \
skype \
signal \
onyx \
libreoffice \
jumpcut \
brave-browser \
appcleaner \
android-file-transfer \
blueharvest \
arduino \
garmin-express \
menumeters \
rar \
tuxera-ntfs \
viber \
viscosity \
microsoft-excel \
microsoft-powerpoint \
microsoft-word \
vmware-fusion
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
mail.db.idle_limit -> 30000000
```

Firewall disable/enable 0/1

```sh
sudo defaults write /Library/Preferences/com.apple.alf globalstate -int 0
```
