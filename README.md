# Balluff

## SNMP

Snmpwalk -v 1 -c public 192.168.0.100

## ProfiNET

In order to set the IP adress of a device with the MAC adress 00:19:31:3F:FF:37 run these commands

>sudo apt get install tcpreplay
>
>sudo tcpreplay -i eth0 profinet-setip-onepacket.pcap

If you want to change the MAC adress you can edit the pcap file with a hex editor like hexedit.

In order to find lost devices with the MAC adress you can run a ARP request or send a packet to your subnet ending with .255
