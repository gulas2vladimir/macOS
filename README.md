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
go \
helm \
htop \
inetutils \
ipcalc \
jq \
kubectx \
kubernetes-cli \
midnight-commander \
mysql-client \
nmap \
pass \
python \
sslscan \
tor \
watch
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
appcleaner \
blueharvest \
docker \
garmin-express \
jumpcut \
libreoffice \
macfuse \
menumeters \
microsoft-auto-update \
microsoft-excel \
microsoft-powerpoint \
microsoft-word \
nextcloud \
onyx \
rar \
signal \
skype \
slack \
spotify \
thunderbird \
tor-browser \
transmission \
viber \
viscosity \
visual-studio-code \
vlc \
whatsapp
```

Enable Touch ID for sudo

/etc/pam.d/sudo
```
auth 	   sufficient     pam_tid.so # Touch ID
auth       sufficient     pam_smartcard.so
auth       required       pam_opendirectory.so
account    required       pam_permit.so
password   required       pam_deny.so
session    required       pam_permit.so
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
