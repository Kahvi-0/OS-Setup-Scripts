**Verify regular and source repo**

[Kali repos](https://www.kali.org/docs/general-use/kali-linux-sources-list-repositories/)
  
  Note that use https rather than http
  
 Docker: https://linuxhint.com/install_docker_kali_linux/

## Installs

    sudo apt-get update && sudo apt-get upgrade
    sudo apt-get install seclists libguestfs-tools gedit mingw-w64 python3-pip gobuster golang node.js npm conky python3-aiohttp
    
    #For ALFA wireless NIC
    #sudo apt-get install realtek-rtl88xxau-dkms
    
    cd /opt && sudo git clone  https://github.com/SecureAuthCorp/impacket.git && cd impacket && sudo pip install .
    pip install xlrd --upgrade
    pip install wheel
    
    sudo mkdir /usr/share/windows-privesc
    sudo cd /usr/bin && sudo wget https://raw.githubusercontent.com/Kahvi-0/HomeNetworkConfigs/master/Kali/windows-resources?token=ALC32BPDHKAJKMYDKDF2OYTAARQNI && sudo chmod +x /usr/bin/windows-privesc


[Virtual box guest addons](https://www.kali.org/docs/virtualization/install-virtualbox-guest-additions-kali/)


##  Tools and others

wget https://gist.githubusercontent.com/joswr1ght/22f40787de19d80d110b37fb79ac3985/raw/9377612eeea89aed2b226a870e76ac12965d6694/easy-simple-php-webshell.php
mv easy-simple-php-webshell.php /usr/share/webshells/php/simple-shell.php

cd /usr/share/wordlists/dirb
wget https://raw.githubusercontent.com/Kahvi-0/Tools-and-Concepts/master/Toolbox/common_extensions.txt

[Toolbox](https://github.com/Kahvi-0/Tools-and-Concepts/tree/master/Toolbox)


**To have auto complete for root user**

Copy .zshrc file contents to roots .zshrc


## Setting the default XFCE

https://www.kali.org/docs/general-use/xfce-faq/


## Setting the default terminal emulator

Set keyboard shortcut for command: 

xfce4-terminal

# Startup 
Move startup.sh to /etc/init.d/ and make it executable

Move .conkyrc to home
