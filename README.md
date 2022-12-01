# GoAccess-Linux-Build
Building GoAccess on Linux.

```
apt install libmaxminddb-dev libncurses5-dev libncursesw5-dev build-essential golang-go
git clone https://github.com/allinurl/goaccess.git
cd goaccess
./configure --enable-utf8 --enable-geoip=mmdb
make
make install
```
