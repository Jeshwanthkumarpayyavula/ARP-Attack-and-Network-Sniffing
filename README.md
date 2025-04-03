# ARP-Attack-and-Network-Sniffing
# Explore Network Sniffing and ARP Attacks

### Name : Jeshwanth Kumar 
### Reg.No : 212223240114

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


From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:
![arspoof](https://github.com/user-attachments/assets/5f77a3a0-b3e5-45e1-a4d8-496c77d3d565)

![windows](https://github.com/user-attachments/assets/2dd90b1a-7938-49d2-b1d1-b548a7082fa4)


 dsniff:






In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:

![meta](https://github.com/user-attachments/assets/1b1f0550-8686-403e-9291-90334a7c49eb)





In Kali issue the following commands:
sudo dsnifff
## OUTPUT:
![dsniff](https://github.com/user-attachments/assets/5917a015-c412-461c-9dd7-d7b4e3aa61e8)

![wireshark](https://github.com/user-attachments/assets/4f0b10c8-7b13-4b75-b21a-96552d5600b1)


Invoke the wireshark and examine the various menus  and controls of the tool:


## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
