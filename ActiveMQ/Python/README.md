# How to install stomp lib for Python 3

## Debian

Following steps were done on My Debian

```bash
git clone https://github.com/jasonrbriggs/stomp.py.git
mv stomp.py/ stomp
cd stomp/
sudo apt install python3-pip
sudo pip3 install setuptools
sudo python3 setup.py build
sudo python3 setup.py install
```