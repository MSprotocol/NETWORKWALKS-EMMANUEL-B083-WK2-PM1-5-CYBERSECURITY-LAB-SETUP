# NETWORKWALKS-EMMANUEL-B083-WK2-PM1-5-CYBERSECURITY-LAB-SETUP
## WEEK 2 | PROJECT 


## MODULE 1
## FOOTPRINTING & RECONNAISSANCE ATTACKS WITH MULTIPLE KALI TOOLS

## Background
Reconnaissance (also called as footprinting) is the first step in any real attack or security test. Before
touching a target, an attacker quietly collects as much public information about it as possible. This
includes who owns the domain, its real IP address, the hosting provider, the web technologies it
runs, its DNS and mail records, and whether a firewall is protecting it. All of this comes from
information the target has already made public, so the target never even knows it is being studied.
This is why recon is powerful and very hard to detect.
What we will do in this task?
In this lab you will footprint the live website networkwalks.com using six built-in Kali Linux tools:
whois, whatweb, nslookup, curl, wafw00f and dnsrecon. Each tool reveals a different piece of the
target, and together they build a full profile of it. The information you gather here is the foundation for
everything that follows. In the next projects/tasks you will use these same findings to plan your
scanning and your attacks, because you cannot attack what you have not first understood. Record
every output carefully, as you will need it for your final report.
## Tasks

Task 1. Run whois to find the domain registration details.

<img width="661" height="580" alt="WHOIS" src="https://github.com/user-attachments/assets/67d4cf39-527e-44f3-861e-ee0605474444" />

Task 2. Run whatweb to fingerprint the web technologies.

<img width="1283" height="268" alt="whatweb" src="https://github.com/user-attachments/assets/07ccef20-7a8f-4fe3-b951-db850c65dce3" />

Task 3. Run nslookup to resolve the domain to its IP address.

<img width="410" height="195" alt="nslookup" src="https://github.com/user-attachments/assets/180794b6-d34f-41f8-8c3c-7607ff112e27" />


Task 4. Run curl -I to read the HTTP response headers.

<img width="1270" height="382" alt="curl" src="https://github.com/user-attachments/assets/fa813dc9-30bb-42fc-8a46-6c6f6bbe05ce" />

Task 5. Run wafw00f to detect a Web Application Firewall.

<img width="674" height="412" alt="wafw00f" src="https://github.com/user-attachments/assets/33457eba-6724-42c9-bbaa-ede205a99f5b" />


Task 6. Run dnsrecon to enumerate all DNS records.

<img width="1055" height="451" alt="dnsrecon" src="https://github.com/user-attachments/assets/845c9fc6-e2d7-4dcb-b876-5ba11f9a12d2" />


## MODULE 5

## Background
Zenmap is the official GUI version of Nmap which can be used on Windows PC. It is a security scanner
software tool which is used by Cybersecurity professionals & Hackers. It is a multi-platform (Linux, Windows,
Mac OS X, BSD, etc.) free and open source application which aims to make Nmap easy for beginners to use
while providing advanced features for experienced Nmap users. Frequently used scans can be saved as
profiles to make them easy to run repeatedly.

## Tasks

## Task1 Download & install Zenmap from official website on your Windows PC
I downloaded Zenmap from the official website https://nmap.org and installed it on my pc 

## Task2 Find your local IP address & your LAN subnet
i find my local IP address on my windows CMD using ipconfig where it listed the my network configurations including ipv4 address, MAC address, subnetmask, and gateway address
<img width="587" height="511" alt="CMD" src="https://github.com/user-attachments/assets/74da5f5e-affc-4d63-8d3a-239d21056340" />

## Task3 Find the list of live hosts/PC's in your IP subnet
i find the list of ip addres on my subnet where i found 21 live host on the network
<img width="686" height="691" alt="15 09 2026_16 44 18_REC" src="https://github.com/user-attachments/assets/7744c410-45c4-48cc-89b3-f118face7c59" />


## Task4 How many hosts are live in your subnet?
There are 21 live host on my subnet

## Task5 What are the IP addresses of the live hosts?
There are 21 IP addresses of the live hosts some which are:
```
192.168.1.1
192.168.1.31
192.168.1.42
192.168.1.43
192.168.1.65
192.168.1.75
```

## Task6 What are the MAC addresses of the live hosts?
There are 21 MAC addresses of the live hosts some which are:
```
44:1C:A8:64:EC:3D
74:24:9F:4E:BD:7C
58:CE:2A:4D:47:39
38:C9:86:E9:AD:B8
A8:E2:91:36:35:42
DE:1C:DF:02:B4:E5
```

## Task7 Display & save the output topology in PDF Format on your desktop
After displying the topology i saved the output in a pdf format

