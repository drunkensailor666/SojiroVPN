## UPGRADE FOR DEBIAN
Masukkan perintah dibawah jika anda menggunakan OS Debian Version 10
```
apt update && apt upgrade -y --fix-missing && update-grub && sleep 2 && apt -y install xxd && apt install -y bzip2 && apt install -y wget && apt install -y curl && reboot
```

##  UPGRADE FOR UBUNTU
Masukkan perintah dibawah jika anda menggunakan OS Ubuntu Version 18 atau 20
### (optional beberapa VPS mengalami masalah nginx ipv6)
```
sudo sed -i 's/^\(GRUB_CMDLINE_LINUX_DEFAULT=".*\) ipv6.disable=1\(.*"\)$/\1 ipv6.disable=0\2/' /etc/default/grub
sudo sed -i 's/^\(GRUB_CMDLINE_LINUX=".*\) ipv6.disable=1\(.*"\)$/\1 ipv6.disable=0\2/' /etc/default/grub
sudo update-grub
sudo reboot
```
```
apt update && apt upgrade -y && update-grub && sleep 2 && reboot
```

## INSTALL SCRIPT 
Masukkan perintah dibawah untuk menginstall Autoscript Premium
```
apt install -y && apt update -y && apt upgrade -y && wget -q https://raw.githubusercontent.com/drunkensailor666/SojiroVPN/main/premi.sh && chmod +x premi.sh && ./premi.sh
```
## UPDATE SCRIPT 
```
wget -q https://raw.githubusercontent.com/drunkensailor666/SojiroVPN/main/update.sh && chmod +x update.sh && ./update.sh
```

## NOTE 
```
JANGAN MALING SCRIPT INI BANG KALAU MAU CHAT AJA t.me/sojiroseta666
```