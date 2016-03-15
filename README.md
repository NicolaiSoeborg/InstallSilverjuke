# Install Silverjuke

Ubuntu 14.04 LTS


```
sudo apt-get install ubuntu-restricted-extras
sudo apt-get update
sudo apt-get install gstreamer1.0 automake python-docutils zlib1g-dev libsqlite3-dev libgl1-mesa-dev libwxgtk3.0-dev
```


```
wget https://github.com/r10s/silverjuke/archive/master.zip
unzip master.zip
cd silverjuke-master
./autogen.sh
./configure
make
sudo mkdir /usr/local/share/silverjuke
./silverjuke
```
