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
Latest versions of Python can be found at https://www.python.org/ftp/python/. Replace the *wget* links with the desired version. Remember to chage the *tar* and *cd* codes with the updated version downloaded.
