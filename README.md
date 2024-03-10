# splash-ubuntu-custom
##My Splash Ubuntu custom

### Install custom splash

## Backup
sudo tar -zcvf backup_themes_splash.tar.gz /usr/share/plymouth/themes/*

## Clone and Install
cd ~/Downloads
git clone https://github.com/Kionovelletto/splash-ubuntu-custom.git
cd splash-ubuntu-custom
sudo cp -Rfv . /usr/share/plymouth/themes/