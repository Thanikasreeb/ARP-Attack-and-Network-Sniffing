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
![image](https://github.com/Thanikasreeb/ARP-Attack-and-Network-Sniffing/assets/119557910/35ec324c-8461-4ade-8f01-ee8512c1c533)

From kali linux issue the command : sudo arpspoof -i eth0 -t

## OUTPUT:
![image](https://github.com/Thanikasreeb/ARP-Attack-and-Network-Sniffing/assets/119557910/e26fa7d8-0032-4df0-af20-4500e921dcc2)

dsniff:

In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org

## OUTPUT:
![image](https://github.com/Thanikasreeb/ARP-Attack-and-Network-Sniffing/assets/119557910/809e75d9-0105-4e7c-891c-ba6caa9394f3)

In Kali issue the following commands: sudo dsnifff

## OUTPUT:
![image](https://github.com/Thanikasreeb/ARP-Attack-and-Network-Sniffing/assets/119557910/fc5ddb2a-418a-4602-a08f-dc14c31ed2c5)

Invoke the wireshark and examine the various menus and controls of the tool:

![image](https://github.com/Thanikasreeb/ARP-Attack-and-Network-Sniffing/assets/119557910/0b690dc3-383b-4931-be13-ec85c01325fa)

## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
