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
![image](https://github.com/user-attachments/assets/7a9e74c7-f4a4-480c-a785-76cce55672a3)

![windows](https://github.com/user-attachments/assets/4ccb96e5-0963-4706-8d02-e36ed099eefa)



 dsniff:






In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:

![ftp](https://github.com/user-attachments/assets/43d16496-02fd-417b-b325-63a9a614b29c)





In Kali issue the following commands:
sudo dsnifff
## OUTPUT:
![dsniff](https://github.com/user-attachments/assets/6d426938-eafa-414f-8a2d-52a94d777b6b)


![wireshark](https://github.com/user-attachments/assets/ab2998b0-3fcd-4af8-be70-276b9d937631)



Invoke the wireshark and examine the various menus  and controls of the tool:


## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
