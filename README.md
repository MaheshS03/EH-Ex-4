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
![VirtualBox_Windows 7_15_04_2024_08_01_11](https://github.com/MaheshS03/EH-Ex-4/assets/128498431/5a2866ad-6897-4cb4-90b4-8273c9f28033)


From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:
![VirtualBox_kali-linux-2023 4-virtualbox-amd64_16_04_2024_08_10_12](https://github.com/MaheshS03/EH-Ex-4/assets/128498431/ed0a1504-82df-4ec5-ba55-90255ca3caa6)

 dsniff:

In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:
![VirtualBox_kali-linux-2023 4-virtualbox-amd64_16_04_2024_09_41_50](https://github.com/MaheshS03/EH-Ex-4/assets/128498431/9c506d90-e502-4e07-9768-33d7cd052d8c)




In Kali issue the following commands:
sudo dsnifff
## OUTPUT:
![VirtualBox_kali-linux-2023 4-virtualbox-amd64_16_04_2024_09_41_25](https://github.com/MaheshS03/EH-Ex-4/assets/128498431/465b4ee6-2949-423b-963d-507602e97c74)



Invoke the wireshark and examine the various menus  and controls of the tool:

![VirtualBox_kali-linux-2023 4-virtualbox-amd64_16_04_2024_10_00_43](https://github.com/MaheshS03/EH-Ex-4/assets/128498431/882b7bca-f1be-4192-95d7-c46451dd2fa7)

### Ettercap:
Ettercap supports active and passive dissection of many protocols (even encrypted ones) and includes many feature for network and host analysis.
Ettercap can be used as sniffing tool as illustrated below:

![VirtualBox_kali-linux-2023 4-virtualbox-amd64_16_04_2024_09_58_46](https://github.com/MaheshS03/EH-Ex-4/assets/128498431/7499c37c-80d4-46f8-9f24-18b6cce5b829)







## RESULT:


The kali linux tools for ARP Attack and Network Sniffing were identified successfully







