
***********************************

## Install script for yiimp on Ubuntu Server 16.04

USE THIS SCRIPT ON FRESH INSTALL UBUNTU Server 16.04 !

Connect on your VPS =>
- adduser pool
- adduser pool sudo
- su - pool
- sudo apt-get -y install git
- git clone https://github.com/xavatar/yiimp_install_scrypt.git
- cd yiimp_install_scrypt/
- sudo bash install.sh (Do not run the script as root)
- sudo bash screen-scrypt.sh (in tuto youtube, i launch the scrypt with root... it does not matter)
- NOT MANDATORY => sudo bash screen-stratum.sh (CONFIGURE BEFORE START this script... add or remove algo you use).


