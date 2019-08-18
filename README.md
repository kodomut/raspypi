# Raspypi.kdmt
Data dump for Raspberry Pi projects

## Updating to Python 3.7.3 on a Raspberry Pi
Open Terminal and input each line of code below individually
```
sudo apt-get install python3-dev libffi-dev libssl-dev -y
wget https://www.python.org/ftp/python/3.7.3/Python-3.7.3.tar.xz
tar -xvf Python-3.7.3.tar.xz
cd Python-3.7.3
./configure
make
sudo make install
sudo pip3 install --upgrade pip
```
