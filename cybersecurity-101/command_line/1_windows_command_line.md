# TryHackMe - Room Title

**Date:** 9th April 2025
**Room:** /room/windowscommandline
**Level:** *Easy*  
**Tags:** *CLI, Linux, Windows, SSH*

---

## 🧩 Room Overview

> The purpose of the room is to learn how to use MS Windows Commamnd Prompt cmd.exe,
> the default CLI(Command-Line Interpreter) in the Windows environment.

---

## 🛠️ Tools Used

- Example: Nmap, Burp Suite, netstat, Wireshark, etc.

---

## 🚀 Step-by-Step Process

### Task 1: [Basic Information System]
1. used CLI commands: set, ver, systeminfo
2. commands serve to obtain certain info about machine/os etc.

### Task 2: [Network Troubleshooting]
1. command: ipconfig, ipconfig /all
2. used ping: pinged example.com - connection timed out
3. used: tracert - network route traversed to reach target
4. terminology: TTL - time-to-live
5. used: nslookup 
6. used: netstat -h; -a; b-; -o; -n

### Task 3: [File and Disk Management]
(Linux and windows commands are sometimes on one, sometimes on the other side)
1. Linux: ls -a, ls -R -- Windows: dir /a, dir /s
2. cd, .., ./, TAB - seem to be as in Linux
3. tree - similar in both Linux and Windows
4. mkdir - same
5. type, more - display files
6. copy = cp 
7. move = mv 

### Task 4: [Task and Process Management]
1. tasklist
2. tasklist /? - overview
3. tasklist /FI "imagename eq xxxxxxxx.exe" - finds tasks

---

## 💡 Key Takeaways

- genereal CLI skills.
- I was familiar Linux Terminal before, so no big surprises here


---

## 🔗 Resources

- Link: https://tryhackme.com/room/windowscommandline
