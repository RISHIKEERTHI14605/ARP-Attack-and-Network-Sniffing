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
**In windows 7 give the command arp -a**

![image](https://github.com/Jayabharathi3/ARP-Attack-and-Network-Sniffing/assets/120367796/c1458d53-c411-4599-8f1b-6abd2ef6baa1)


### From kali linux issue the command :
**sudo arpspoof -i eth0 -t <target system> <gateway>**

![image](https://github.com/Jayabharathi3/ARP-Attack-and-Network-Sniffing/assets/120367796/9421aafb-07ff-46c6-b727-e5f83e04be7f)


### dsniff:
In Metasploit open the ftp console as below. Also you can try other ftp websites **ftp.vim.org**
![image](https://github.com/Jayabharathi3/ARP-Attack-and-Network-Sniffing/assets/120367796/9ff31c98-dfe6-45f9-b359-cccd099b4423)


## WIRESHARK :
Invoke the wireshark and examine the various menus  and controls of the tool:

![image](https://github.com/Jayabharathi3/ARP-Attack-and-Network-Sniffing/assets/120367796/f6aac873-e145-4496-ad99-b268f63433d6)

## ETTERCAP :

ettercap supports active and passive dissection of many protocols and includes many features for network and host analysis.

![image](https://github.com/Jayabharathi3/ARP-Attack-and-Network-Sniffing/assets/120367796/901cb1d8-044e-46d7-a323-3c12d6a9fa5f)

## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
