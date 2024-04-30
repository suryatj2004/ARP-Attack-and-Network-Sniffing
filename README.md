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

![image](https://github.com/Catty12384/ARP-Attack-and-Network-Sniffing/assets/120629225/fd399296-ecd5-4c07-8438-29bc64c81f49)

From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:

![image](https://github.com/Catty12384/ARP-Attack-and-Network-Sniffing/assets/120629225/9af55c34-5a83-41e5-a0d6-d469fe5d5554)

dsniff:

In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:

![image](https://github.com/Catty12384/ARP-Attack-and-Network-Sniffing/assets/120629225/54fcd892-4143-4dbb-9a47-72df68742db5)

In Kali issue the following commands:
sudo dsnifff
## OUTPUT:

![image](https://github.com/Catty12384/ARP-Attack-and-Network-Sniffing/assets/120629225/c008fea6-6d53-4025-a2b8-158d762c73c0)

Invoke the wireshark and examine the various menus  and controls of the tool:

###WIRESHARK:

![image](https://github.com/Catty12384/ARP-Attack-and-Network-Sniffing/assets/120629225/7d15db9a-6cae-4f2f-a835-aba88a761deb)

###ETTER CAP:

![image](https://github.com/Catty12384/ARP-Attack-and-Network-Sniffing/assets/120629225/a67a13a9-0ec9-435c-a16e-45b6bd97a9b2)

## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
