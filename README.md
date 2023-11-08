## EX.NO : 04
## DATE : 14.9.2023
# <p align="center"> ARP-Attack-and-Network-Sniffing</p>


## AIM:
To explore network sniffing and ARP Attacks

## STEPS:
### Step 1:
Install kali linux either in partition or virtual box or in live mode

### Step 2:
Investigate on the various categories of tools as follows:

### Step 3:
Open terminal and try execute some kali linux commands

## ARP Attacks:
ARP spoofing: A hacker sends fake ARP packets that link an attacker's MAC address with an IP of a computer already on the LAN. Boot kali and Windows7 virtual machines. In windows 7 give the command arp -a

## OUTPUT:

![268926942-2126c09a-4a85-41e0-826a-cbb3b87964b9](https://github.com/durga46/ARP-Attack-and-Network-Sniffing/assets/75235704/bf05b662-3ca1-4ca4-9106-60d4cc197409)

### From kali linux issue the command : sudo arpspoof -i eth0 -t

## OUTPUT:

![268926901-61253e4a-2dd8-41a2-a8a1-caeea1b3b1c7](https://github.com/durga46/ARP-Attack-and-Network-Sniffing/assets/75235704/8008426e-c98f-4b44-bfcc-487312cf8111)

### dsniff:
In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:

![268926810-79ab5047-07f1-4d6a-a5f4-d5b4f503a54b](https://github.com/durga46/ARP-Attack-and-Network-Sniffing/assets/75235704/b32809c7-a918-4ce1-b3b4-5bcd5980eb38)

### In Kali issue the following commands: sudo dsnifff
## OUTPUT:

![268926733-3472bd7e-2fc7-4e86-a6ef-d341c0476926](https://github.com/durga46/ARP-Attack-and-Network-Sniffing/assets/75235704/c49c7a15-1388-436d-ad7d-89b26f38dbbf)

## Invoke the wireshark and examine the various menus and controls of the tool:

![268926680-fd045287-3301-40e7-a939-39ea37d0d0c4](https://github.com/durga46/ARP-Attack-and-Network-Sniffing/assets/75235704/fb118711-31cd-4620-b08e-fbb23dfad6e1)

## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully.
