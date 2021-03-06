# Libernet
Libernet is open source web app for tunneling internet using SSH, V2Ray on OpenWRT with ease.

## Requirements
- bash
- screen
- jq
- Python 3
- OpenSSH
- sshpass
- V2Ray
- go-tun2socks
- badvpn-tun2socks (legacy)
- php7
- php7-cgi
- php7-mod-session
- php7-mod-json

## Working Features:
- SSH with proxy
- V2Ray trojan
- V2Ray vmess

## Installation
- Clone this repository on OpenWRT via terminal: ```git clone https://github.com/lutfailham96/libernet```
- Run install script: ```cd libernet && bash install.sh```

## Default Username & Password
- Username: admin
- Password: libernet

## Additional Information
In the home menu, check 'Use tun2socks legacy' to use badvpn-tun2socks or uncheck to use go-tun2socks instead.
