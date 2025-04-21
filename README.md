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

![image](https://github.com/user-attachments/assets/797d3791-bbcf-4857-8ee1-2020e753e3cd)

![image](https://github.com/user-attachments/assets/08b39d38-07dc-468d-86bd-59b22de56e33)


From kali linux issue the command :
sudo arpspoof -i enp0s3 -t <target system> <gateway>
## OUTPUT:

![image](https://github.com/user-attachments/assets/332c0d52-39f7-428b-beb1-b2a8081e5cfe)



 dsniff:






In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:

![image](https://github.com/user-attachments/assets/40512876-fe63-45dc-a115-085b71a0de9c)


In Kali issue the following commands:
sudo dsnifff
## OUTPUT:



Invoke the wireshark and examine the various menus  and controls of the tool:
![image](https://github.com/user-attachments/assets/0f80b357-4f8c-4c69-96af-31f0d81e0b13)



![image](https://github.com/user-attachments/assets/a74dce19-5aff-4230-9553-9e01617e8a37)

## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
