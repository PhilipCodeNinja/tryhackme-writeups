# TryHackMe - Room Title

**Date:** 15 April 2025
**Room:** Networking Essentials
**Level:** *(Easy)*  
**Tags:** *networking*

---

## 🧩 Room Overview

> Dynamic Host Conficuration Protocol (DHCP), Address Resolution Protocol (ARP), Network Address Translation (NAT), Internet Control Message Protocol (ICMP) - Ping, Traceroute.

---

## 🛠️ Tools Used

- Example: Nmap, Burp Suite, netstat, Wireshark, etc.

---

## 🚀 Step-by-Step Process

### Task 2: [DHCP: Give Me My Network Settings]
1. Dynamic Host Configuration Protocol (DHCP
	1 DHCP Discover - client broadcasts message seeking local DHCP server
	2 DHCP Offer - server responds with a DHCPOFFER message with IP for client
	3 DHCP Request - client sends messageing accepting IP
	4 DHCP Achknowledge - server responds, confirming IP

DHCPDISCOVER 	- client uses 255.255.255.255 as destination
		- client uses 0.0.0.0 as source IP


### Task 3: [ARP: Bridging Layer 3 Addressing to Layer 2 Addressing]
1. could not process - will be understood later

### Task 4: [ICMP: Troubleshooting Networks]
	- Ping: 	ping : measures RTT (round-trip time)
	- Traceroute: 	traceroute (linux) tracert (MS Windows systems) - uses ICMP to discover route
		has TTL (time to live); time := number of routers

### Task 5: [Routing]
Routing protocols
	- OSPF (Open Shortest Path First: Is a routing protocol that allows routers to share information about the network topology
	- EIGRP (Enhanced Interior Gateway Routing Protocol)
	- BGP (Broader Gateway Protocol)
	- RIP (Routing Information Protocol)

### Task 6: [NAT]
- devices have internal address and external address given by router

---

## 💡 Key Takeaways

- 1–3 main things you learned from this room
- Tips or gotchas you didn’t expect

---

## 🔗 Resources

- Link to relevant tools, articles, or THM room
