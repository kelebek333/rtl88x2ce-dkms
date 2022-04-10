## Installation

### Manual installation
```
sudo apt-get install build-essential git dkms linux-headers-$(uname -r)
git https://github.com/kelebek333/rtl88x2ce-dkms
sudo dkms install ./rtl88x2ce-dkms
sudo cp ./rtl88x2ce-dkms/rtw88_blacklist.conf /etc/modprobe.d/rtw88_blacklist.conf
sudo update-initramfs -u
```

### PPA repository 
#### Ubuntu/Linux Mint/Pop!OS/ElementaryOS/Zorin etc.
```
sudo add-apt-repository ppa:kelebek333/kablosuz
sudo apt-get update
sudo apt install rtl8822ce-dkms
```
