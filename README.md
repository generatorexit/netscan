# netscan
This program scans your network and finds mac addresses,ip addresses and company names of the devices
![alt text](https://github.com/generatorexit/netscan/blob/main/img.png)

## Install

```
git clone https://github.com/generatorexit/netscan
cd netscan
bash install.sh
```
### Usage:

```
sudo python3 netscan.py [options]
example: sudo python3 netscan.py -l 192.168.108.1/24
```

```
Usage: netscan.py [options]

Options:
  -h, --help            show this help message and exit
  -r IP_RANGE, --range=IP_RANGE
                        This parameter shows you ip addresses,mac addresses
                        and company names in the network. Example:sudo python3
                        netscan.py -r 192.168.108.1/24
  -l LOOK_ALWAYS, --look_always=LOOK_ALWAYS
                        This Parameter shows you io addresses,mac addresses
                        and company names in the network every 5 sec.
                        Example:sudo python3 netscan.py -l 192.168.108.1/24
```
