# Disclaimer
***I am not responsible for damage caused by the use of this script.***
***Only use this script if you fully understand what the script does.***

- - - -

# Setup
First clear the entire routerboard and then connect a ethernet cable to the last ethernetport.
Then add the config via the terminal.  

**Do not forget to set the admin password**

## WAN
The first interface is seen as the WAN Interface.

There is a bridge and the firewall rules are on the bridge.

There is also a source nat with a masquerade rule on the brige for internet access.

## LAN
The ethernet interfaces between the first and the last are in a bridge for the LAN.

A dhcp server for LAN clients runs on the LAN Bridge.

## Management
The last interface is seen as a management / configuration interface.

Management can be done on this interface and the various winbox services are also available. 

Traffic between the LAN and Management networks is prohibit in the firewall.