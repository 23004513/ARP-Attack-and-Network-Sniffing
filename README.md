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

![Screenshot 2024-10-16 112046](https://github.com/user-attachments/assets/cb3f063d-2367-4661-8c20-3705e7b9aa22)


From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:

![Screenshot 2024-10-16 104606](https://github.com/user-attachments/assets/d56dec51-45ec-48dc-a9a2-d6839b24a51b)

 dsniff:

In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:

![image](https://github.com/user-attachments/assets/64bea175-1024-4a22-b0ec-c2b59750d21d)



In Kali issue the following commands:
sudo dsnifff
## OUTPUT:

![Screenshot 2024-10-23 093446](https://github.com/user-attachments/assets/ffd67583-d87b-4947-97ed-f33b3363c51c)



Invoke the wireshark and examine the various menus  and controls of the tool:

![image](https://github.com/user-attachments/assets/c0420916-ad89-4183-b287-079e2e23e430)


## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
