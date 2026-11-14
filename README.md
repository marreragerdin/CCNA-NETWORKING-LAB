# Cisco CCNA (200-301) Networking Labs Portfolio

Welcome to my *CCNA 200-301* hands-on lab repository. I am documenting my networking journey through *Jeremy's IT Lab* by building, configuring, and troubleshooting enterprise network topologies in *Cisco Packet Tracer*.

Each completed lab folder includes the .pkt project file, network topology diagrams, exported Cisco IOS running-config files, and technical documentation detailing the configurations and verification steps.

---

## 🎯 Study Goals & Focus
* Master core routing, switching, security, and IP services through daily hands-on CLI practice.
* Build strong network troubleshooting habits using show commands, ping, traceroute, and packet inspection.
* Maintain production-grade network documentation (IP addressing tables, interface descriptions, and topology diagrams).

---

## 📂 Complete CCNA Lab Progress Index

*Status Legend:* ✅ Completed | 🔄 In Progress | ⏳ Upcoming

### Phase 1: Network Fundamentals & Basic CLI (Days 01–15)

| Day | Topic / Lab Title | Key Technologies & Commands | Status | Lab Folder |
| :--- | :--- | :--- | :---: | :--- |
| Day 01 | Network Devices | Routers, switches, firewalls, servers, clients | ✅ | Theory / Intro |
| Day 02 | Interfaces & Cables | RJ45, UTP straight-through/crossover, fiber optics (MMF/SMF) | ✅ | Theory / Intro |
| Day 03 | OSI Model & TCP/IP Suite | Encapsulation, PDUs, Layer 1–7 functions | ✅ | Packet Analysis |
| Day 04 | Intro to the CLI | Console access, User/Privileged EXEC, Global Config, enable, conf t | ✅ | CLI Basics |
| Day 05 | Ethernet LAN Switching (Part 1) | MAC addresses, Ethernet frames, unicast/broadcast | ✅ | Theory / Intro |
| Day 06 | Ethernet LAN Switching (Part 2) | MAC address table learning/aging, show mac address-table | ✅ | CLI Basics |
| Day 07 | IPv4 Addressing (Part 1) | Binary/decimal conversion, Class A/B/C, network/host portions | ✅ | Theory / Intro |
| Day 08 | IPv4 Addressing (Part 2) | Interface IP config, ip address, no shutdown, show ip int brief | ✅ | [View Lab](./Day-8-IPv4-Addresses) |
| Day 09 | Switch Interfaces | Speed, duplex, auto-MDIX, show interfaces status, error counters | 🔄 | In Progress |
| Day 10 | The IPv4 Header | Header fields, TTL, Protocol numbers, DSCP/ECN | ⏳ | Upcoming |
| Day 11 | Routing Fundamentals & Static Routing | Routing tables, connected/local/static routes, ip route | ⏳ | Upcoming |
| Day 12 | The Life of a Packet | End-to-end L2/L3 header rewrites, ARP, default gateway | ⏳ | Upcoming |
| Day 13 | Subnetting (Part 1) | Class C subnetting, CIDR notation, calculating hosts/subnets | ⏳ | Upcoming |
| Day 14 | Subnetting (Part 2) | Class B & Class A subnetting practice | ⏳ | Upcoming |
| Day 15 | Subnetting (Part 3) — VLSM | Variable Length Subnet Masks, efficient IP allocation | ⏳ | Upcoming |

---

### Phase 2: Switching, VLANs, STP & EtherChannel (Days 16–23)

| Day | Topic / Lab Title | Key Technologies & Commands | Status | Lab Folder |
| :--- | :--- | :--- | :---: | :--- |
| Day 16 | VLANs (Part 1) | Broadcast domains, access ports, vlan, switchport mode access | ⏳ | Upcoming |
| Day 17 | VLANs (Part 2) — Trunking | 802.1Q tagging, native VLAN, switchport mode trunk | ⏳ | Upcoming |
| Day 18 | VLANs (Part 3) — Inter-VLAN Routing | Router-on-a-Stick (ROAS), subinterfaces, Layer 3 switches (SVIs) | ⏳ | Upcoming |
| Day 19 | DTP & VTP | Dynamic Trunking Protocol, VLAN Trunking Protocol modes | ⏳ | Upcoming |
| Day 20 | Spanning Tree Protocol (Part 1) | Root bridge election, root/designated/non-designated ports, BPDUs | ⏳ | Upcoming |
| Day 21 | Spanning Tree Protocol (Part 2) | PortFast, BPDU Guard, root bridge primary/secondary config | ⏳ | Upcoming |
| Day 22 | Rapid Spanning Tree Protocol (RSTP) | 802.1w port states/roles, rapid convergence | ⏳ | Upcoming |
| Day 23 | EtherChannel | LACP, PAgP, static port-channels, load balancing | ⏳ | Upcoming |

---

### Phase 3: Dynamic Routing, FHRP & IPv6 (Days 24–33)

| Day | Topic / Lab Title | Key Technologies & Commands | Status | Lab Folder |
| :--- | :--- | :--- | :---: | :--- |
| Day 24 | Dynamic Routing Protocols | Distance vector vs. link-state, AD, metrics, floating static routes | ⏳ | Upcoming |
| Day 25 | RIP & EIGRP | RIPv2, EIGRP feasibility condition, router eigrp | ⏳ | Upcoming |
| Day 26 | OSPF (Part 1) | Link-state databases, LSAs, areas, router ID, router ospf | ⏳ | Upcoming |
| Day 27 | OSPF (Part 2) | OSPF neighbor states, DR/BDR election, cost manipulation | ⏳ | Upcoming |
| Day 28 | OSPF (Part 3) | Network types (Broadcast, Point-to-Point), passive interfaces, MTU | ⏳ | Upcoming |
| Day 29 | First Hop Redundancy Protocols (FHRP) | HSRP active/standby routers, virtual IP/MAC, VRRP, GLBP | ⏳ | Upcoming |
| Day 30 | TCP & UDP | Three-way handshake, flow control, windowing, well-known ports | ⏳ | Upcoming |
| Day 31 | IPv6 (Part 1) | Hexadecimal format, address shortening, Global Unicast, Link-Local | ⏳ | Upcoming |
| Day 32 | IPv6 (Part 2) | EUI-64, SLAAC, NDP, ipv6 unicast-routing | ⏳ | Upcoming |
| Day 33 | IPv6 (Part 3) — Static Routing | IPv6 static routes (directly attached, recursive, fully specified) | ⏳ | Upcoming |

---

### Phase 4: Security, IP Services & QoS (Days 34–51)

| Day | Topic / Lab Title | Key Technologies & Commands | Status | Lab Folder |
| :--- | :--- | :--- | :---: | :--- |
| Day 34 | Standard ACLs | Numbered/named standard ACLs, wildcard masks, ip access-group | ⏳ | Upcoming |
| Day 35 | Extended ACLs | Filtering by source/destination IP, protocol, and port numbers | ⏳ | Upcoming |
| Day 36 | CDP & LLDP | Layer 2 neighbor discovery, show cdp neighbors detail | ⏳ | Upcoming |
| Day 37 | NTP | Network Time Protocol, stratum levels, ntp server | ⏳ | Upcoming |
| Day 38 | DNS | Domain Name System, A/AAAA/CNAME records, ip name-server | ⏳ | Upcoming |
| Day 39 | DHCP | DORA process, DHCP pools, ip helper-address (DHCP relay) | ⏳ | Upcoming |
| Day 40 | SNMP | Managers, agents, MIBs, OIDs, traps, SNMPv2c/v3 | ⏳ | Upcoming |
| Day 41 | Syslog | Severity levels (0–7), logging buffers, external syslog servers | ⏳ | Upcoming |
| Day 42 | SSH | Securing VTY lines, RSA keys, transport input ssh | ⏳ | Upcoming |
| Day 43 | FTP & TFTP | IOS image upgrades, backing up/restoring startup-config | ⏳ | Upcoming |
| Day 44 | NAT (Part 1) | Inside/outside local/global addresses, Static NAT | ⏳ | Upcoming |
| Day 45 | NAT (Part 2) | Dynamic NAT, PAT (NAT Overload), ip nat inside source list | ⏳ | Upcoming |
| Day 46 | QoS (Part 1) | Voice/video traffic needs, jitter, latency, classification & marking | ⏳ | Upcoming |
| Day 47 | QoS (Part 2) | Queuing, congestion management, policing, shaping, VoIP VLANs | ⏳ | Upcoming |
| Day 48 | Security Fundamentals | Threats, vulnerabilities, CIA triad, AAA, VPNs | ⏳ | Upcoming |
| Day 49 | Port Security | Sticky MAC addresses, violation modes (shutdown, restrict, protect) | ⏳ | Upcoming |
| Day 50 | DHCP Snooping | Trusted vs. untrusted ports, DHCP snooping binding table | ⏳ | Upcoming |
| Day 51 | Dynamic ARP Inspection (DAI) | Mitigating ARP spoofing/poisoning, ip arp inspection | ⏳ | Upcoming |

---

### Phase 5: Architectures, Wireless & Automation (Days 52–63 + Mega Lab)

| Day | Topic / Lab Title | Key Technologies & Commands | Status | Lab Folder |
| :--- | :--- | :--- | :---: | :--- |
| Day 52 | LAN Architectures | Two-tier (collapsed core), three-tier, spine-leaf topologies | ⏳ | Upcoming |
| Day 53 | WAN Architectures | Leased lines, MPLS, Metro Ethernet, VPNs, SD-WAN | ⏳ | Upcoming |
| Day 54 | Cloud Computing | IaaS, PaaS, SaaS, public/private/hybrid cloud, virtualization | ⏳ | Upcoming |
| Day 55 | Wireless Fundamentals | RF bands (2.4/5 GHz), channels, SSIDs, AP modes | ⏳ | Upcoming |
| Day 56 | Wireless Architectures | Autonomous vs. lightweight APs, WLC, CAPWAP tunnels | ⏳ | Upcoming |
| Day 57 | Wireless Security | WPA2/WPA3, PSK vs. 802.1X (RADIUS), TKIP/AES | ⏳ | Upcoming |
| Day 58 | Wireless Configuration | Configuring WLC interfaces, WLANs, and security settings | ⏳ | Upcoming |
| Day 59 | Intro to Network Automation | Traditional vs. software-defined networking (SDN), controllers | ⏳ | Upcoming |
| Day 60 | JSON, XML & YAML | Data serialization formats, key-value pairs, arrays | ⏳ | Upcoming |
| Day 61 | REST APIs | HTTP verbs (GET, POST, PUT, DELETE), CRUD, authentication | ⏳ | Upcoming |
| Day 62 | Software-Defined Networking (SDN) | Control/data/management planes, Cisco DNA Center | ⏳ | Upcoming |
| Day 63 | Ansible, Puppet & Chef | Configuration management tools, agent vs. agentless, playbooks | ⏳ | Upcoming |
| Final | *CCNA 200-301 Mega Lab* | Full-scale enterprise network combining VLANs, STP, OSPF, NAT, ACLs, DHCP & SSH | ⏳ | Upcoming |

---

## 🛠️ Skills & Tools Demonstrated
* *Switching & Routing:* VLANs, 802.1Q Trunking, Inter-VLAN Routing, STP/RSTP, EtherChannel, Static Routing, OSPF, FHRP (HSRP), IPv6
* *Network Services & Security:* DHCP, DNS, NTP, SNMP, Syslog, NAT/PAT, Standard & Extended ACLs, SSH, Port Security, DHCP Snooping, DAI
* *Tools & Platforms:* Cisco Packet Tracer, Cisco IOS CLI, Wireshark, Git & GitHub

---

## 📫 Connect With Me
* *LinkedIn:* https://www.linkedin.com/in/gerdinmarrera
* *Certification Goal:* Cisco Certified Network Associate
