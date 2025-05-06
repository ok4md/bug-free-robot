mmdvm_connect - ARM Raspberry Pi
--------------------------------------
You can use MMDVM hotspot (or repeater) with this mmdvm-connect app to directly connect to another MMDVM hotspot (or repeater).
(DMR mode only)


Device A, MMDVM.ini:

Address=127.0.0.1

Port=62931

Password=passw0rd



Device B, MMDVM.ini:

Address="Device A IP"  

Port=62931

Password=passw0rd


If the MMDVM devices are not on the same LAN network, it is necessary to use a VPN.
