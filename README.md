# termux_2.0
pkg install git
pkg install unzip
pkg install zip
pkg install bash
pkg install tsu
pkg install termux-api #вылезет запрос о предоставлении рут 
git clone https://github.com/Fablys/termux_1.0
cd termux_1.0
unzip GWC.zip -d /data/data/com.termux/files/home
cd /data/data/com.termux/files/home/GWC
chmod 777 cons.sh
bash cons.sh
