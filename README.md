# systemback-install_pack-1.9.4
This Install Pack contains the Systemback Debian installation packages.
These packages are compatible with the following Linux distributions:

Debian 10.0 Buster
Ubuntu 18.04 (Bionic Beaver)
Ubuntu 20.04 (Focal Fossa))


To install the program just run the 'install.sh' installer script with root privileges in terminal, like this:

 

git clone https://github.com/fconidi/systemback-install_pack-1.9.4.git
tar xvf systemback-install_pack-1.9.4.tar.xz
cd systemback-install_pack-1.9.4/
chmod +x install.sh
sudo ./install.sh

or

 sudo sh install.sh

If you want to install the program with debug packages, just run the 'install.sh' installer script with '-d' option:

 sudo ./install.sh -d

or

 sudo sh install.sh -d

If the installation is successful, the following message appears:

 Systemback installation is successful.

If the installation is failed, you will receive the following error message:

 Systemback installation is failed!
