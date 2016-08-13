Wifi Kill
========

A python program that uses scapy to kick people off of wifi. The script must be run as sudo. The script also requires that scapy be installed. To install it, do

    sudo apt-get install python-scapy

The program lists the devices connected to the network then allows you to:
 - Prevent the desired ip from accessing the network
 - Prevent everyone from accessing the network

Requirements
============

OSX (tested working on El Capitan): 
```
brew install libdnet
sudo pip install pypcap
```

*#Don't forget the SUDO!#*
