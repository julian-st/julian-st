### julianst | Julian

- Hello! I'm Julian. I'm a software developer.
- :man_student: I'm in search for code challenges
- :man_technologist: Contact me [@LinkedIn](https://www.linkedin.com/in/juliansteinbock/)
- 🗣️ I speak German<img src="https://raw.githubusercontent.com/csmoore/country-flag-icons/master/country-flags-4x3-svg/de.svg" alt="de" width="20"/>, English<img src="https://raw.githubusercontent.com/csmoore/country-flag-icons/master/country-flags-4x3-svg/gb.svg" alt="english" width="20"/> and a little bit of Spanish<img src="https://raw.githubusercontent.com/csmoore/country-flag-icons/master/country-flags-4x3-svg/es.svg" alt="esp" width="20"/> and French<img src="https://raw.githubusercontent.com/csmoore/country-flag-icons/master/country-flags-4x3-svg/fr.svg" alt="fr" width="20"/>
- :globe_with_meridians: You should also definitely check my [dev.to profile](https://dev.to/julianst)

### Preferred tech

<img src="https://simpleicons.org/icons/cplusplus.svg" alt="cplusplus" width="50"/><img src="https://simpleicons.org/icons/apachemaven.svg" alt="maven" width="50"/><img src="https://simpleicons.org/icons/springboot.svg" alt="springboot" width="50"/><img src="https://simpleicons.org/icons/angular.svg" alt="angular" width="50"/><img src="https://simpleicons.org/icons/php.svg" alt="php" width="50"/><img src="https://simpleicons.org/icons/python.svg" alt="python" width="50"/><img src="https://simpleicons.org/icons/javascript.svg" alt="javascript" width="50"/><img src="https://simpleicons.org/icons/mysql.svg" alt="mysql" width="50"/><img src="https://simpleicons.org/icons/selenium.svg" alt="selenium" width="50"/>
![Solidity](https://img.shields.io/badge/Solidity-%23363636.svg?style=for-the-badge&logo=solidity&logoColor=white)
![Java](https://img.shields.io/badge/java-000000?style=for-the-badge&logo=java&logoColor=white)
![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

## Network

### SNMP

The dependancy is snmp 

>snmpwalk -v 1 -c public 192.168.0.1
>
>snmpget -v 1 -c private 192.168.0.1 iso.3.6.1.2.1.1.6.0 
>
>snmpset -v 1 -c private 192.168.0.1 iso.3.6.1.2.1.1.6.0 s setvalue

### ProfiNET

In order to set the IP adress of a device with the MAC adress 00:19:31:3F:FF:37 run this command

>sudo tcpreplay -i eth0 profinet-setip-onepacket.pcap

The dependancy is tcpreplay

If you want to change the MAC adress you can edit the pcap file with a hex editor like hexedit.

In order to find lost devices with the MAC adress you can run a ARP request or send a packet to your subnet ending with .255

With the file profinet-setip-onepacket.pcap the IP adress is set to 192.168.0.3
