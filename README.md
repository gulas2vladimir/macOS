brew
```sh
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

commandline tools
```sh
brew install dialog mc pass wget python3 gnupg2 tor youtube-dl git woof ansible inetutils
```

start tor service
```sh
brew services start tor
```

applications
```sh
brew cask install \
java \
adium \
appcleaner \
thunderbird \
google-chrome \
firefox \
vlc \
xld \
transmission \
blueharvest \
viscosity \
vmware-fusion \
torbrowser \
garmin-express \
android-file-transfer \
arduino \
libreoffice \
visual-studio-code \
teensy \
spotify \
jubler \
tuxera-ntfs \
burn \
owncloud \
yujitach-menumeters \
gpg-suite \
jumpcut
```

commandline iStats
```sh
sudo gem install iStats
```

Firefox
```
browser.cache.disk.enable -> False
browser.cache.memory.enable -> False
network.dnsCacheExpiration -> 0
```

Thunderbird
```
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

Disable -0 /Enable -1 Firewall
```
sudo defaults write /Library/Preferences/com.apple.alf globalstate -int 0
```
