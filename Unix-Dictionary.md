# Unix-Ubuntu-MacOS Commands (ctrl+alt+t)
```
sudo = run as admin
mkdir = make directory, creates a filesystem folder
ls = list files in current directory
cd = change directory
pwd = present working directory
dir = print current directory contents
wget = download from internet
apt-get = download from ubuntu repo
history = self explanatory
man = followed by a command displays the manual 
-br = brief
reboot = reboots system
lsblk = list drives and partitions
```
## Networking
```
ip -br link = network/mac addresses
ip -br addr show = network/mac addresses long form
ip -br a s = network addresses
dmidecode -t 2 = system info
ip addr show = long form IP address
```
## Boot from Linux forced from the BIOS on Linux:
```
sudo grub-install /dev/nvme0n1
sudo update-grub
```
## Add Alias Path
```
cd ~
sudo nano .zshrc
alias <alias name>="<command name>"
source ~/.zshrc
```
## Install linux IPMI to see the event log:
```
$ sudo apt install ipmitool
$ sudo ipmitool sdr >& ipmi-sdr.txt
$ sudo ipmitool sel elist >& ipmi-sel.txt
# IPMI show IP/MAC address:
$ sudo ipmitool lan print 1
```
## MACOS Helium Commands
```
base command = ./helium-wallet
import wallet = ./helium-wallet create basic --seed mobile (make sure verify:true)
```
## BASH COMMANDS 
[Cheatsheet](https://devhints.io/bash)
