linux command note
==================
### wifi configuration

/etc/wpa_supplicant/wpa_supplicant.config   
wpa_passphrase _wifi_name_ _wifi_password_   
scan_ssid=1   
key_mgmt=WPA-PSK   

### kernel version
uname -a

### package update
apt update //system package list update   
apt full-upgrade //system package upgrade(dependency incl)   

### command information
info _ps_ // ps command information

### network connection information
ifconfig

### ssh agent
eval "$(ssh-agent -s)"   
ssh-add _ssh_id_path_   

### cat
cat -n _path_ //display line number

### more
space or f //page-down   
b //page-up, not work   
/_string_to_find_ //find string, n: next find   
q //quite   

### echo
\> : create new file and overwrite   
\>> : create new file and add
