# Hi and welcome to my github repo

I am ![Julian](https://shields.io/badge/-julian-julian "julian") and love programming.

<img src="https://simpleicons.org/icons/cplusplus.svg" alt="cplusplus" width="50"/><img src="https://simpleicons.org/icons/angular.svg" alt="angular" width="50"/><img src="https://simpleicons.org/icons/php.svg" alt="php" width="50"/><img src="https://simpleicons.org/icons/java.svg" alt="java" width="50"/><img src="https://simpleicons.org/icons/python.svg" alt="python" width="50"/><img src="https://simpleicons.org/icons/javascript.svg" alt="javascript" width="50"/>
## Network

### SNMP

The dependancy is snmp 

>Snmpwalk -v 1 -c public 192.168.0.110
>
>Snmpget -v 1 -c private 192.168.0.110 iso.3.6.1.2.1.1.6.0 
>
>Snmpset -v 1 -c private 192.168.0.110 iso.3.6.1.2.1.1.6.0 s setvalue

### ProfiNET

In order to set the IP adress of a device with the MAC adress 00:19:31:3F:FF:37 run this command

>sudo tcpreplay -i eth0 profinet-setip-onepacket.pcap

The dependancy is tcpreplay

If you want to change the MAC adress you can edit the pcap file with a hex editor like hexedit.

In order to find lost devices with the MAC adress you can run a ARP request or send a packet to your subnet ending with .255

With the file profinet-setip-onepacket.pcap the IP adress is set to 192.168.0.3
