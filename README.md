# Manjaro
custom configuration files for my system

#### Grub
Location: /etc/default/grub
set GRUB_TIMEOUT to zero for a faster and smoother boot.

#### Swapfile usage
Location: /etc/sysctl.d/99-swappiness.conf
vm.swappiness=10 to reduce hdd/ssd swapfile usage. only use it when really needed. This will keep the system fast and clean.



## Firefox

#### /home/yovvel/.mozilla/firefox/9mbxgjrk.default-release/chrome/userChrome.css/userChrome.css
Customization file to remove the horizontal tabs bar on top of the screen.
to make it work, set toolkit.legacyUserProfileCustomizations.stylesheets to true in about:config.
