# wi-fi TP-LINK-TL-WN821N

https://github.com/Mange/rtl8192eu-linux-driver
You will need to have Secure Boot disabled if your computer is equipped with that feature

sudo apt install build-essential linux-headers-generic dkms git
git clone https://github.com/Mange/rtl8192eu-linux-driver.git
sudo dkms add ./rtl8192eu-linux-driver
sudo dkms install rtl8192eu/1.0
reboot 
after reboot my adapter is work.

cd ./rtl8192eu-linux-driver
make clean
