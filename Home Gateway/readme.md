# Setup
First clear the entire routerboard and then connect a ethernet cable to the last ethernetport.<br/>
Then either add the config via the terminal or upload the backup file and restore that.  

**Do not forget to set the admin password**

## WAN
The first interface is seen as the WAN Interface.<br/>
There is a bridge and the firewall rules are on the bridge.<br/>
There is also a source nat with a masquerade rule on the brige for internet access.

## LAN
The ethernet interfaces between the first and the last are in a bridge for the LAN.<br/>
A dhcp server for LAN clients runs on the LAN Bridge.

## Management
The last interface is seen as a management / configuration interface.<br/>
Management can be done on this interface and the various winbox services are also available.<br/>
Traffic between the LAN and Management networks is prohibit in the firewall.