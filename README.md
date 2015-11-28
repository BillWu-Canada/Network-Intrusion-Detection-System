# Network-Intrusion-Detection-System

This IDS is network-based, and it will monitor network traffic for known attacks based on provided signatures. The application will receive suspicious packet capture files from a network monitoring program and output any detected attacks, as well as some details about them.

The main functionalities of this application are: 
1. Count packets and sizes
2. Detect packets with clearly spoofed addresses
3. Detect LAN-based servers
4. Detect DNS queries for sinkholed domains
5. Detect ARP cache poisoning attacks
6. Detect the presence of famous worms
7. Detect amplified denial-of-service attacks



How to use the ids:

when you in the terminal, type "Python ids [your pcap file]" to run the script
