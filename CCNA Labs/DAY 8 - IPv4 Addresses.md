
# Day 08: Configuring IPv4 Addresses

<img width="782" height="325" alt="Screenshot 2026-11-14 131533" src="https://github.com/user-attachments/assets/6a8e8bc5-4ba3-4832-b444-439a3e2b3978" />

## Lab Overview
In this lab from *Jeremy's IT Lab (CCNA 200-301)*, I configured IPv4 addresses, subnet masks, and interface descriptions on a Cisco router (R1) and three end hosts (PC1, PC2, and PC3), enabled the router interfaces, and verified end-to-end network reachability across three different IPv4 address classes.

---

## Addressing Table

| Device | Interface | IPv4 Address | Subnet Mask | Default Gateway | Network Class |
| :--- | :--- | :--- | :--- | :--- | :--- |
| *R1* | GigabitEthernet0/0 | 15.255.255.254 | 255.0.0.0 (/8) | N/A | Class A |
| *R1* | GigabitEthernet0/1 | 182.98.255.254 | 255.255.0.0 (/16) | N/A | Class B |
| *R1* | GigabitEthernet0/2 | 201.191.20.254 | 255.255.255.0 (/24) | N/A | Class C |
| *PC1* | FastEthernet0 | 15.0.0.1 | 255.0.0.0 | 15.255.255.254 | Class A |
| *PC2* | FastEthernet0 | 182.98.0.1 | 255.255.0.0 | 182.98.255.254 | Class B |
| *PC3* | FastEthernet0 | 201.191.20.1 | 255.255.255.0 | 201.191.20.254 | Class C |

---

## Key CLI Configurations (R1)

ios
enable
configure terminal

interface GigabitEthernet0/0
 description ##FOR SWITCH 1##
 ip address 15.255.255.254 255.0.0.0
 no shutdown
 exit

interface GigabitEthernet0/1
 description ##FOR SWITCH 2##
 ip address 182.98.255.254 255.255.0.0
 no shutdown
 exit

interface GigabitEthernet0/2
 description ##FOR SWITCH 3##
 ip address 201.191.20.254 255.255.255.0
 no shutdown
 end

copy running-config startup-config



---

## Verification & Troubleshooting
* *Interface Status:* Verified that G0/0, G0/1, and G0/2 all transitioned from administratively down to up/up using show ip interface brief.
* *Descriptions Check:* Confirmed interface descriptions were properly applied using show running-config.
* *Connectivity Testing:* Tested inter-network routing by running ping 182.98.0.1 and ping 201.191.20.1 from PC1's Command Prompt. All ICMP echo replies succeeded after initial ARP resolution.

---

## Key Takeaways
1. *Router Interfaces Default to Down:* Unlike switch ports, Cisco router interfaces are administratively shut down by default and require the no shutdown command to forward traffic.
2. *Default Gateway Requirement:* End hosts require a properly configured default gateway matching their local router interface IP to communicate with devices outside their own subnet.
3. *Configuration Persistence:* Running copy running-config startup-config saves the active configuration from volatile RAM to NVRAM so settings survive a reload.
