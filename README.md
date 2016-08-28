# Install Silverjuke

Tested platform: `Ubuntu 14.04 LTS`


```
sudo apt-get update
sudo apt-get install -y --no-install-recommends ubuntu-restricted-extras gstreamer1.0 automake python-docutils zlib1g-dev libsqlite3-dev libgl1-mesa-dev libwxgtk3.0-dev
```


```
wget https://github.com/r10s/silverjuke/archive/master.zip
unzip master.zip
cd silverjuke-master
./autogen.sh
./configure
make -j4
sudo mkdir /usr/local/share/silverjuke
./silverjuke
```
