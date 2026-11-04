# 4.Execution_of_NetworkCommands
## AIM :Use of Network commands in Real Time environment
## Software : Command Prompt And Network Protocol Analyzer
## Procedure: To do this EXPERIMENT- follows these steps:
<BR>
In this EXPERIMENT- students have to understand basic networking commands e.g cpdump, netstat, ifconfig, nslookup ,traceroute and also Capture ping and traceroute PDUs using a network protocol analyzer 
<BR>
All commands related to Network configuration which includes how to switch to privilege mode
<BR>
and normal mode and how to configure router interface and how to save this configuration to
<BR>
flash memory or permanent memory.
<BR>
This commands includes
<BR>
• Configuring the Router commands
<BR>
• General Commands to configure network
<BR>
• Privileged Mode commands of a router 
<BR>
• Router Processes & Statistics
<BR>
• IP Commands
<BR>
• Other IP Commands e.g. show ip route etc.
<BR>

## Output:
Microsoft Windows [Version 10.0.26200.9711]
(c) Microsoft Corporation. All rights reserved.

C:\Users\acer>ipconfig

Windows IP Configuration


Ethernet adapter Ethernet 2:

   Connection-specific DNS Suffix  . :
   Link-local IPv6 Address . . . . . : fe80::135b:9242:8df3:9b73%3
   IPv4 Address. . . . . . . . . . . : 192.168.56.1
   Subnet Mask . . . . . . . . . . . : 255.255.255.0
   Default Gateway . . . . . . . . . :

Wireless LAN adapter Local Area Connection* 1:

   Media State . . . . . . . . . . . : Media disconnected
   Connection-specific DNS Suffix  . :

Wireless LAN adapter Local Area Connection* 2:

   Media State . . . . . . . . . . . : Media disconnected
   Connection-specific DNS Suffix  . :

Wireless LAN adapter Wi-Fi:

   Connection-specific DNS Suffix  . :
   IPv6 Address. . . . . . . . . . . : 2401:4900:cac5:5705:2c28:62a6:af04:d2a9
   Temporary IPv6 Address. . . . . . : 2401:4900:cac5:5705:e4ca:d1d8:57de:4eb1
   Link-local IPv6 Address . . . . . : fe80::6aa7:5320:c2c9:49fa%9
   IPv4 Address. . . . . . . . . . . : 10.51.121.212
   Subnet Mask . . . . . . . . . . . : 255.255.255.0
   Default Gateway . . . . . . . . . : fe80::441f:9ff:fed0:aa14%9
                                       10.51.121.121

Ethernet adapter Bluetooth Network Connection:

   Media State . . . . . . . . . . . : Media disconnected
   Connection-specific DNS Suffix  . :

Ethernet adapter Ethernet:

   Media State . . . . . . . . . . . : Media disconnected
   Connection-specific DNS Suffix  . :

C:\Users\acer>ipconfig \all

Error: unrecognized or incomplete command line.

USAGE:
    ipconfig [/allcompartments] [/? | /all |
                                 /renew [adapter] | /release [adapter] |
                                 /renew6 [adapter] | /release6 [adapter] |
                                 /flushdns | /displaydns | /registerdns |
                                 /showclassid adapter |
                                 /setclassid adapter [classid] |
                                 /showclassid6 adapter |
                                 /setclassid6 adapter [classid] ]

where
    adapter             Connection name
                       (wildcard characters * and ? allowed, see examples)

    Options:
       /?               Display this help message
       /all             Display full configuration information.
       /release         Release the IPv4 address for the specified adapter.
       /release6        Release the IPv6 address for the specified adapter.
       /renew           Renew the IPv4 address for the specified adapter.
       /renew6          Renew the IPv6 address for the specified adapter.
       /flushdns        Purges the DNS Resolver cache.
       /registerdns     Refreshes all DHCP leases and re-registers DNS names
       /displaydns      Display the contents of the DNS Resolver Cache.
       /showclassid     Displays all the dhcp class IDs allowed for adapter.
       /setclassid      Modifies the dhcp class id.
       /showclassid6    Displays all the IPv6 DHCP class IDs allowed for adapter.
       /setclassid6     Modifies the IPv6 DHCP class id.


The default is to display only the IP address, subnet mask and
default gateway for each adapter bound to TCP/IP.

For Release and Renew, if no adapter name is specified, then the IP address
leases for all adapters bound to TCP/IP will be released or renewed.

For Setclassid and Setclassid6, if no ClassId is specified, then the ClassId is removed.

Examples:
    > ipconfig                       ... Show information
    > ipconfig /all                  ... Show detailed information
    > ipconfig /renew                ... renew all adapters
    > ipconfig /renew EL*            ... renew any connection that has its
                                         name starting with EL
    > ipconfig /release *Con*        ... release all matching connections,
                                         eg. "Wired Ethernet Connection 1" or
                                             "Wired Ethernet Connection 2"
    > ipconfig /allcompartments      ... Show information about all
                                         compartments
    > ipconfig /allcompartments /all ... Show detailed information about all
                                         compartments

C:\Users\acer>ipconfig \flushdns

Error: unrecognized or incomplete command line.

USAGE:
    ipconfig [/allcompartments] [/? | /all |
                                 /renew [adapter] | /release [adapter] |
                                 /renew6 [adapter] | /release6 [adapter] |
                                 /flushdns | /displaydns | /registerdns |
                                 /showclassid adapter |
                                 /setclassid adapter [classid] |
                                 /showclassid6 adapter |
                                 /setclassid6 adapter [classid] ]

where
    adapter             Connection name
                       (wildcard characters * and ? allowed, see examples)

    Options:
       /?               Display this help message
       /all             Display full configuration information.
       /release         Release the IPv4 address for the specified adapter.
       /release6        Release the IPv6 address for the specified adapter.
       /renew           Renew the IPv4 address for the specified adapter.
       /renew6          Renew the IPv6 address for the specified adapter.
       /flushdns        Purges the DNS Resolver cache.
       /registerdns     Refreshes all DHCP leases and re-registers DNS names
       /displaydns      Display the contents of the DNS Resolver Cache.
       /showclassid     Displays all the dhcp class IDs allowed for adapter.
       /setclassid      Modifies the dhcp class id.
       /showclassid6    Displays all the IPv6 DHCP class IDs allowed for adapter.
       /setclassid6     Modifies the IPv6 DHCP class id.


The default is to display only the IP address, subnet mask and
default gateway for each adapter bound to TCP/IP.

For Release and Renew, if no adapter name is specified, then the IP address
leases for all adapters bound to TCP/IP will be released or renewed.

For Setclassid and Setclassid6, if no ClassId is specified, then the ClassId is removed.

Examples:
    > ipconfig                       ... Show information
    > ipconfig /all                  ... Show detailed information
    > ipconfig /renew                ... renew all adapters
    > ipconfig /renew EL*            ... renew any connection that has its
                                         name starting with EL
    > ipconfig /release *Con*        ... release all matching connections,
                                         eg. "Wired Ethernet Connection 1" or
                                             "Wired Ethernet Connection 2"
    > ipconfig /allcompartments      ... Show information about all
                                         compartments
    > ipconfig /allcompartments /all ... Show detailed information about all
                                         compartments

C:\Users\acer>ipconfig /flushdns
The requested operation requires elevation.

C:\Users\acer>ipconfig /flushdns
The requested operation requires elevation.

C:\Users\acer>ping google.com

Pinging google.com [2404:6800:4000:1025::65] with 32 bytes of data:
Reply from 2404:6800:4000:1025::65: time=119ms
Reply from 2404:6800:4000:1025::65: time=138ms
Reply from 2404:6800:4000:1025::65: time=87ms
Reply from 2404:6800:4000:1025::65: time=105ms

Ping statistics for 2404:6800:4000:1025::65:
    Packets: Sent = 4, Received = 4, Lost = 0 (0% loss),
Approximate round trip times in milli-seconds:
    Minimum = 87ms, Maximum = 138ms, Average = 112ms

C:\Users\acer>tracert google.com

Tracing route to google.com [2404:6800:4000:1025::65]
over a maximum of 30 hops:

  1     9 ms     4 ms     2 ms  2401:4900:cac5:5705::2d
  2    49 ms    57 ms    88 ms  2401:4900:1:a819::2
  3    75 ms    29 ms    72 ms  2401:4900:1:a88b::4
  4    52 ms    41 ms    34 ms  2401:4900:1:a88b::1
  5     *        *        *     Request timed out.
  6    96 ms    30 ms    79 ms  2404:a800:3a00:300::95
  7     *      105 ms    98 ms  2404:a800::92
  8    58 ms    72 ms   117 ms  lcbomp-in-f101.1e100.net [2404:6800:4000:1025::65]

Trace complete.

C:\Users\acer>arp -a

Interface: 192.168.56.1 --- 0x3
  Internet Address      Physical Address      Type
  192.168.56.255        ff-ff-ff-ff-ff-ff     static
  224.0.0.2             01-00-5e-00-00-02     static
  224.0.0.22            01-00-5e-00-00-16     static
  224.0.0.251           01-00-5e-00-00-fb     static
  224.0.0.252           01-00-5e-00-00-fc     static
  230.0.0.1             01-00-5e-00-00-01     static
  239.255.255.250       01-00-5e-7f-ff-fa     static

Interface: 10.51.121.212 --- 0x9
  Internet Address      Physical Address      Type
  10.51.121.121         46-1f-09-d0-aa-14     dynamic
  10.51.121.255         ff-ff-ff-ff-ff-ff     static
  224.0.0.22            01-00-5e-00-00-16     static
  224.0.0.251           01-00-5e-00-00-fb     static
  224.0.0.252           01-00-5e-00-00-fc     static
  239.255.255.250       01-00-5e-7f-ff-fa     static
  255.255.255.255       ff-ff-ff-ff-ff-ff     static

C:\Users\acer>netstat

Active Connections

  Proto  Local Address          Foreign Address        State
  TCP    10.51.121.212:49672    10.51.121.121:domain   TIME_WAIT
  TCP    10.51.121.212:49717    172.64.148.235:https   ESTABLISHED
  TCP    10.51.121.212:50912    lb-140-82-112-25-iad:https  ESTABLISHED
  TCP    10.51.121.212:52439    10.51.121.121:domain   TIME_WAIT
  TCP    10.51.121.212:53857    10.51.121.121:domain   TIME_WAIT
  TCP    10.51.121.212:55041    104.18.124.108:https   TIME_WAIT
  TCP    10.51.121.212:56306    whatsapp-cdn-shv-02-maa5:5222  ESTABLISHED
  TCP    10.51.121.212:56393    sc-in-f188:https       ESTABLISHED
  TCP    10.51.121.212:60411    10.51.121.121:domain   TIME_WAIT
  TCP    10.51.121.212:61483    104.46.162.224:https   ESTABLISHED
  TCP    10.51.121.212:61811    10.51.121.121:domain   TIME_WAIT
^C
C:\Users\acer>getmac

Physical Address    Transport Name
=================== ==========================================================
FC-6D-77-6F-A9-E0   Media disconnected
FC-6D-77-6F-A9-DC   \Device\Tcpip_{4B2633DD-E32D-4A78-87AA-C56D8DE8704C}
74-D4-DD-CF-7E-A8   Media disconnected
0A-00-27-00-00-03   \Device\Tcpip_{06E31D9C-1031-4DF2-8C1D-E778ABD13DD6}

C:\Users\acer>hostname
TMP215-75-G2

C:\Users\acer>nslookup google.com
Server:  UnKnown
Address:  10.51.121.121

Non-authoritative answer:
Name:    google.com
Addresses:  2404:6800:4007:834::200e
          142.251.43.46

## Result
Thus Execution of Network commands Performed 
