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
![436816261-4965731d-5807-401e-9a05-2a2123b9e906](https://github.com/user-attachments/assets/fb476945-95b5-4098-8bf7-836e820a695e)


From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:

![435374363-96ceffe8-51d7-440b-ba73-07fb9b451140](https://github.com/user-attachments/assets/f0e79e37-88b0-4280-9d40-f49669f6a64d)

## dsniff:
![435376523-cae623b8-5cea-46ea-8ce2-4ca2966806d1](https://github.com/user-attachments/assets/7e0eff47-93a5-4c45-9f48-19453f8c6389)


In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org


## OUTPUT:

![435376523-cae623b8-5cea-46ea-8ce2-4ca2966806d1](https://github.com/user-attachments/assets/7e0eff47-93a5-4c45-9f48-19453f8c6389)



In Kali issue the following commands:
sudo dsnifff
## OUTPUT:
![435377329-cc675d18-debe-42a3-8b3c-58fecac61d5f](https://github.com/user-attachments/assets/fad7e992-45fa-46e6-8db4-d8d5b11c6484)



Invoke the wireshark and examine the various menus  and controls of the tool:


## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
