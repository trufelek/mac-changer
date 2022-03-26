# mac-changer
Python script that changes the MAC address of an interface to a given value.

## Prerequisites

- [Python installed](https://www.python.org/downloads/)

## Getting started
To use this script go to the root project folder and run following command:

```
python mac_changer.py -i INTERFACE_NAME -m NEW_MAC_ADDRESS
```

Where `INTERFACE_NAME` is a name of an interface, e.g. `eth0` and `NEW_MAC_ADDRESS` is a new MAC address in format of `XX:XX:XX:XX:XX:XX`. Example:

```
python mac_changer.py -i eth0 -m 1a:2b:3c:4d:5e:6f
```
