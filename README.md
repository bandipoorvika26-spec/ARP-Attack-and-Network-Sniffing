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

<img width="1660" height="922" alt="1" src="https://github.com/user-attachments/assets/7b9ee3c3-71ab-4fb7-85c8-b04c85a3f219" />
## OUTPUT:

<img width="1581" height="871" alt="2" src="https://github.com/user-attachments/assets/60009434-fd22-446b-b814-fa759d8a4555" />

From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:
<img width="1363" height="837" alt="3" src="https://github.com/user-attachments/assets/40cd64d1-7c18-4792-a795-a1adcd887d5c" />
<img width="1354" height="873" alt="Screenshot 2026-08-19 035217" src="https://github.com/user-attachments/assets/508c8e02-5692-4ca9-be0f-f2ddeee8a515" />

 dsniff:






In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:
<img width="1386" height="851" alt="5" src="https://github.com/user-attachments/assets/5f1122b0-b306-4001-b72b-36290e44a1da" />

<img width="1380" height="855" alt="Screenshot 2026-08-19 035347" src="https://github.com/user-attachments/assets/aa40b36a-6577-4faa-8e24-b3029e8b6ab6" />




In Kali issue the following commands:
sudo dsnifff
## OUTPUT:

<img width="1421" height="883" alt="Screenshot 2026-08-19 040848" src="https://github.com/user-attachments/assets/ebfaf985-a5aa-46ca-8ab1-93e0ccfbcf50" />

Invoke the wireshark and examine the various menus  and controls of the tool:


## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
