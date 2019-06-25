# AutoScriptVPS

Auto SSH VPN Script ( Ssh/VPN )
Recommended OS: Debian 7 x 64 or 32

Service Include
Openssh : 22 , 444
Dropbear : 143 , 109
Squid : 8000 , 3128
SSL : 443
Openvpn : 1194 (ip:81/client.ovpn)
Webmin : ip:10000
DDOS Deflate
Fail2Ban

Run this command

SSHVPN SCRIPT
wget https://raw.githubusercontent.com/kyojenmoon/VPSauto/master/deb7script.sh && chmod +x deb7script.sh && ./deb7script.sh

OCS PANEL SCRIPT
wget https://raw.githubusercontent.com/kyojenmoon/VPSauto/master/ocsscript.sh && chmod +x ocsscript.sh && ./ocsscript.sh
OCS PANEL mod EZ Connect SCRIPT
wget https://raw.githubusercontent.com/kyojenmoon/VPSauto/master/EZmod.sh && chmod +x EZmod.sh && ./EZmod.sh

If you get error in ocs install this to the serverthat have error
apt-get install libxml-parser-perl

Ubuntu 16.04 x64 or Debian 8.10 x64Softether Script
wget https://raw.githubusercontent.com/kyojenmoon/VPSauto/master/SEsetup.sh && chmod +x SEsetup.sh && ./SEsetup.sh
