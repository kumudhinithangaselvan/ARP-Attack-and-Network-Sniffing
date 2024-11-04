# ARP-Attack-and-Network-Sniffing
# Explore Network Sniffing and ARP Attacks

# AIM:

To explore network sniffing and ARP Attacks

## STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various categories of tools as follows:


### Step 3:
Open terminal and try execute some kali linux commands

## ARP Attacks:  
ARP spoofing: A hacker sends fake ARP packets that link an attacker's MAC address with an IP of a computer already on the LAN. 
Boot kali and Windows7 virtual machines.
In windows 7 give the command arp -a
## OUTPUT:

![windows (1)](https://github.com/user-attachments/assets/731a5df1-bc11-4f06-9d41-db71b99203db)


From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:
![arpspoof](https://github.com/user-attachments/assets/91aa35f6-8a4b-4037-9e12-f48b27a04ab6)

 ### dsniff:

In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:
![ftp](https://github.com/user-attachments/assets/1cb10108-fcb7-4810-96f5-eaac8e3e0a7e)




In Kali issue the following commands:
sudo dsnifff
## OUTPUT:

![dsniff](https://github.com/user-attachments/assets/f38b2fd9-c61a-417f-a787-6e688e3ec0a3)


Invoke the wireshark and examine the various menus  and controls of the tool:
![wireshark](https://github.com/user-attachments/assets/753fe82a-bf8d-4354-b31c-e2a1895c0044)


## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
