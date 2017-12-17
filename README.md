# BreakWall
yum -y install wget


wget --no-check-certificate https://raw.githubusercontent.com/teddysun/shadowsocks_install/master/shadowsocksR.sh


chmod +x shadowsocksR.sh


./shadowsocksR.sh 2>&amp;1 | tee shadowsocksR.log
