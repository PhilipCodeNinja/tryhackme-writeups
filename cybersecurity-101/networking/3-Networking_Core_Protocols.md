# TryHackMe - Room Title

**Date:** 15 April 2025
**Room:** Networking Core Protocols
**Level:** *(Easy)* 
**Tags:** *networking*

---

## 🧩 Room Overview

> This room will teach the following protocols:
> WHOIS
> DNS
> HTTP and FTP
> SMTP, POP3, and IMAP

---

## 🛠️ Tools Used

- Example: Nmap, Burp Suite, netstat, Wireshark, etc.

---

## 🚀 Step-by-Step Process

### Task 2: [DNS: Remembering Addresses]
1. DNS operates at Application Layer (7) and is responsible for ampping domain names to IP
	- A record: maps hosname to one ore more IPv4 addresses
	- AAAA Record: for IPv6 addresses
		note:  AA refers to Authentication, Authorization, and Accounting OR AAA battery - neither is DNS topic
	- CNAME Record (Canonical Name): maps a domain name to another domain name - itanimulli.com -> nsa.gov.us
	- MX Record (Mail eXchange): specifies the mail server responsible for handling emails for a domain
2. nslookup xxxxx.domain		- (cmd) gives IP address of domain


### Task 3: [WHOIS]
1. whois [....].com  - gives info about domain owner
 

### Task 4: [HTTPS(S): Accessing the Web]
1. HyperText Transfer Protocol (Secure) - relies on TCP
2. common browser commands
	GET - retrieves data from server, eg HTML file or image
	POST _ submit data to server
	PUT - create new resurce on server, update, overwrite
	DELETE - self explanatory
3. commonly using TCP ports 80 and 443

### Task 5 [FTP: Transferring Files]
- HTTP transfers web pages
- FTP  transters files
	File Transfer Protocol
1. common commands:
	USER to input user name
	PASS to enter password
	RETR to download a file from the FTP server to the client
	STOR to upload a file from the client


2. Listens to Port 21
3. when files are gotten (get ...) they are stored in directory of root machine where user was before.

### Task 6 [SMTP: Sending Email]
To send emails to SMTP server the following commands are used by mail client:
HELO or EHLO 	- initiates SMTP sesssion
MAIL FROM 	- specifies sender's email address
RCPT TO		- specifies recipient's address
DATA		- indicates that client will begin sending the content of the data
.		- is sent on a line by itself to indicate the end of the email message

### Task 7 [POP3: Receiving Email

---

## 💡 Key Takeaways

- I found out that my private information for my own domain was not publicly available - Noice!

---

## 🔗 Resources

- Link to relevant tools, articles, or THM room
