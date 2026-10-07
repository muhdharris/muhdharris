# Harris Razainuddin

Network & Security Engineer in Kuala Lumpur. Firewalls, switching, and the
troubleshooting in between.

## Career path

School, university, work, in order.

```
$ traceroute muhdharris

traceroute to muhdharris (Kuala Lumpur), 6 hops max

 1  sms-tengku-muhammad-faris-petra  2015-2019  SPM
 2  universiti-malaya                2020-2021  Foundation, Physical Sciences
 3  universiti-malaya                2021-2025  BSc Computer Systems & Networks
 4  wevo-system                      2025       intern, Mar-Aug
 5  innosphere-technologies          2026-      network & security engineer
 6  homelab                          always on  two Proxmox nodes, 16 containers

destination reached
```

## Skills: platforms and services

Each open port is something I run or work with.

```
$ nmap -sV muhdharris

PORT      STATE   SERVICE    VERSION
22/tcp    open    ssh        Linux administration (Debian, Ubuntu)
23/tcp    closed  telnet     no, thank you
53/tcp    open    domain     Pi-hole DNS
80/tcp    open    http       HTML, CSS, JavaScript
2049/tcp  open    nfs        NFS and SMB shares on an OMV NAS
3306/tcp  open    mysql      MySQL
8006/tcp  open    proxmox    Proxmox VE, two-node cluster
9443/tcp  open    portainer  Docker, 16 containers
```

## Skills: protocols and tools

The protocols, techniques and tools I use.

```
$ nmap -sO muhdharris

PROTOCOL  STATE  SERVICE
6         open   tcp
17        open   udp
88        open   eigrp
89        open   ospf

Also open: VLANs, NAT, ACLs, firewalls, VPN, IDS/IPS, subnetting
Cloud:     AWS (coursework)
Tools:     Wireshark, Nmap, GNS3, Packet Tracer
Code:      Python, Java, JavaScript
```

## Projects

Where each project lives and what it is built with.

```
$ show ip route
```

| Destination | Via | Note |
|---|---|---|
| [homelab](https://github.com/muhdharris/homelab) | Proxmox, Docker | a two-node cluster with a Docker media stack and an OMV NAS, run as a working testbed |
| [muhdharris.github.io](https://muhdharris.github.io) | HTML, CSS, JS | my portfolio, hand-written, no template, no framework |
| [networkscanner](https://github.com/muhdharris/networkscanner) | Python, Flask | a web interface over nmap: host scans, vulnerability scripts, scheduled scans |
| [cinemaProject](https://github.com/muhdharris/cinemaProject) | Java | **the first coding project I wrote during my degree**, a cinema booking application |
| [Website-in-Docker](https://github.com/muhdharris/Website-in-Docker) | JavaScript, Docker | a responsive frontend with a small backend API, served from containers |
| [PortScanner](https://github.com/muhdharris/PortScanner) | Ruby | a network port scanner |
| [WebScraper](https://github.com/muhdharris/WebScraper) | Python | a small web scraper |
| [WebRTCtest](https://github.com/muhdharris/WebRTCtest) | JavaScript | WebRTC peer connection and connectivity tests |

## Homelab diagram

How my home network is laid out.

```
$ show topology
```

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/topology-dark.svg">
  <img src="assets/topology-light.svg" alt="Homelab topology: two Proxmox nodes, a Docker VM with 16 containers and an OpenMediaVault NAS VM sharing storage over NFS and SMB. Small red dots travel along the links." width="640">
</picture>

## Certifications

What I have completed, with the month.

```
$ show certifications

Codes: C - CCNA, S - security

C   2022-06  Introduction to Networks
C   2023-07  Switching, Routing & Wireless Essentials
C   2023-07  Enterprise Networking, Security & Automation
S   2024-06  CyberOps Associate
```

## Contact

Where I am, languages, and how to reach me.

```
$ whois muhdharris

location:   Kuala Lumpur, Malaysia
languages:  Malay (native), English (fluent)
mail:       muhdharris40@gmail.com
```

[Email](mailto:muhdharris40@gmail.com) ·
[LinkedIn](https://linkedin.com/in/muhdharris) ·
[muhdharris.github.io](https://muhdharris.github.io)

```
Connection to muhdharris closed.
```
