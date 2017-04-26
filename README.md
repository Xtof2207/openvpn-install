## openvpn-management
OpenVPN [road warrior](http://en.wikipedia.org/wiki/Road_warrior_%28computing%29) installer and management script for Debian, Ubuntu and CentOS.

This script will let you setup your own VPN server in no more than a minute (except 4096 certificate creation :) ), even if you haven't used OpenVPN before. It has been designed to be as unobtrusive and universal as possible.

### Installation
Run the script and follow the assistant:

bash ./openvpn-management.sh

Was only tested under Debian Jessie via Vmware Workstation

Once it ends, you can run it again to add more users, remove some of them or even completely uninstall OpenVPN.

### Credits
This script is based on work from https://github.com/Nyr/openvpn-install, same licence apply

### Creating users (option 4 & 5)
- if without password you will get an .ovpn file all included
- with password, you will get a .zip file with cert, key, ovpn files needed inside

### Save / Restore function added

Working in org or cn mode

Easy-Rsa 3.0.1

Features to add :
- Manage more then one openvpn services on one computer
- VPN IP address range to manage (for the moment, fixed in script)
- Modify vars via questions and answers (2048/4096 encryption, org/cn mode, Country, Province etc....)
- Manage traffic direction (All traffic via VPN or just for routed networks)
- Make working together OVPN + OTP
- Add monitoring management functions
