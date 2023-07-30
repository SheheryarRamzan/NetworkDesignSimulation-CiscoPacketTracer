# NetworkDesignSimulation-CiscoPacketTracer
Given the network design with minimal technical documentation this project demanded to simulate network topology on Cisco packet tracer instructor version.

1. Following are the steps you need to perform in the topology according to the given layout. Configure this scenario and find your given IP address in the file "IP addresses" attached with  this. Find out the Network Addresses and start working with them. And use them as required.
2. Please find the number of required hosts per subnet in the given file. Each student is given a different number of required hosts per subnet. Networks are labeled alphabetically in the given file of IP ADDRESSES. The networks with Router23 are not labeled so you can choose any number of hosts for those subnets. 
3. Use EIGRP in First Block for Routing, OSPF with area 1 in Second Block, Rip in Third Block, and OSPF with area 0 in the last block as mentioned on the top of each block. 
4. Use Redistribution on Router6 and Router13 for connecting EIGRP with OSPF and OSPF with RIP.
5. All hosts in EIGRP, OSPF area 1, and RIP will get IP addresses from the "DHCP Server" present in the first block.
6. All hosts in OSPF area 0 will get hosts from the “DHCP Server” present in its own  block. (named as web server in the picture)
7. You have to use VLSM in each network of the topology.
8. You have to IMPLEMENT NAT in Router7 with the Network G. Use the Private IP Address given to you in the attached file for Natting. 
