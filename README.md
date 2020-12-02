# debian-custom-setup

## realtech wifi driver installation (optional)

1). clone https://github.com/lijovijayan/rtlwifi_new
2). change directory to rtlwifi_new
3). execute below commands
    sudo apt-get install linux-headers-generic build-essential git
    git clone https://github.com/lwfinger/rtlwifi_new
    cd rtlwifi_new
    make
    sudo make install
    sudo modprobe rtl8723be
    echo "options rtl8723de ant_sel=1" | sudo tee /etc/modprobe.d/rtl8723de.conf
    
## arc-dark theme installation
  sudo apt install arc-theme

## papirus icon theme installation
  sudo apt install papirus-icon-theme

## grub-customizer installation
  sudo apt install grub-customizer
 
## extra configs
  https://linuxconfig.org/how-to-install-macos-theme-on-ubuntu-20-04-focal-fossa-linux#:~:text=Open%20up%20the%20Gnome%20Tweaks,into%20your%20~%2FDownloads%20directory.
