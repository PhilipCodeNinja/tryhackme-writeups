# TryHackMe - Room Title

**Date:** 15 April 2025  
**Room:**  Networking Concepts
**Level:** *(Easy)*  
**Tags:** *ISO OSI model, TCP/IP protocol suite*

---

## 🧩 Room Overview

> Learn ISO OSI network model, IP addresses, subnets, routing, TCP, UDP, port numbers, how to connect and open TCP port from CL

---

## 🛠️ Tools Used

- Example: Nmap, Burp Suite, netstat, Wireshark, etc.

---

## 🚀 Step-by-Step Process

### Task 2: [OSI Model]
The layers of the Open Systems Interconnection (OSI) modell are the following
7 Application
6 Presentation
5 Session
4 Transport
3 Network
2 Data Link
1 Physical

"Please Do Not Throw Spinach Pizza Away"


1. Physical Layer 	- physical connections, medium, wire, definition of binary 1 and 0
2. Data Link Layer	- sending data within network		- protocol that enables data transfer between nodes of same network segment, eg. ethernet 802.3, Wifi 802.11
3. Network layer	- sending data between different networks
4. Transport layer 	- enables end-to-end communication between running applications on different hosts. - Transmission Controp Protocol TCP, User Datagram Protocol UDP
5. Session layer	- establishes, maintains, sychnronizes communiacation between applications running on different hosts.
6. Presentation layer	- ensures that data is delivered in a form the application layer can understand
7. Application layer 	- http, ftp, dns

### Task 2: [TCP/IP Model]
Comparison with ISO OSI model - overlap explained
Modell has 3,4,5 layers depending which one one is talking about

### Task 3: [IP Addresses and Subnets]
Private IP ranges as per RFC 1918
	10.0.0.0 - 10.255.255.255 (10/8)
	172.1.0.0 - 172.31.255.255 (172.16/12)
	192.168.0.0 - 192.168.255.255 (192.168/16)

- learned about subnet masks, broadcast address, host address

### Task 4: [UDP and TCP]
1. UDP - User Datagram Protocol - operates on layer 4 - transport
 - standard mail service - no guarantee package arrives

2. TCP - Transmission Control Protocol
 - requires establishment of connection before transmission

### Task 5 [Encapsulation]
- this is quite easy to understand:
sent packages will each have wrapper data around them,
usually a header, sometimes a trailer which makes it so that each layer can do its job.

Terms:
4 - segment/datagram
3 - packet
2 - frame


### Task 6 [Telnet]
telnet is a network protocol for remote terminal connection
- Echo server 		- port 7
- Daytime server 	- port 13
- Web (HTTP) server	- port 80 (listens on TCP)

---



## 💡 Key Takeaways

- nothing mindblowing - I expect these things to make more sense later in both theory and practice
---

## 🔗 Resources

- https://tryhackme.com/room/networkingconcepts
