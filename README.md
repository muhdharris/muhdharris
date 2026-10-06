# Harris Razainuddin

Network & Security Engineer in Kuala Lumpur. Firewalls, switching, and the faults
that don't announce themselves.

```
$ traceroute muhdharris
traceroute to muhdharris (Kuala Lumpur), 5 hops max

 1  universiti-malaya         2020-2021   Foundation, Physical Sciences
 2  universiti-malaya         2021-2025   BSc Computer Systems & Networks
 3  wevo-system               2025        intern, Mar-Aug
 4  innosphere-technologies   2026-       network & security engineer
 5  homelab                   always on   two Proxmox nodes, 16 containers
```

## Fault log

**STP loop during a Huawei switch refresh.** A Layer 2 loop formed with STP already
running, and the traffic took the firewall down, so the whole network went offline, not
one segment. I found the switch by disconnecting switches one at a time; the loop was
gone within hours. Afterwards I added protections on my own initiative so one device
can't do this again: BPDU filtering and edge ports on access ports, DHCP snooping, and
link-flap auto-recovery. Root cause not established; there was no baseline
configuration to compare against. There's a playable version on the
[portfolio](https://muhdharris.github.io): "Find the loop".

**Two hardware faults in my homelab that looked identical from outside.** Both took the
cluster offline the same way. One needed a second diagnosis after the first fix didn't
hold. Both are written up in
[homelab/troubleshooting](https://github.com/muhdharris/homelab/tree/main/troubleshooting).

## Certifications

- CCNA: Introduction to Networks (Jun 2022)
- CCNA: Switching, Routing & Wireless Essentials (Jul 2023)
- CCNA: Enterprise Networking, Security & Automation (Jul 2023)
- CyberOps Associate (Jun 2024)

## Work

- [muhdharris.github.io](https://muhdharris.github.io): my portfolio. Hand-written HTML
  and CSS, no template, no framework.
- [homelab](https://github.com/muhdharris/homelab): a two-node Proxmox cluster with a
  Docker media stack and an OMV NAS, run as a working testbed.
- Smaller projects:
  [Website-in-Docker](https://github.com/muhdharris/Website-in-Docker) ·
  [cinemaProject](https://github.com/muhdharris/cinemaProject) ·
  [PortScanner](https://github.com/muhdharris/PortScanner) ·
  [WebScraper](https://github.com/muhdharris/WebScraper) ·
  [WebRTCtest](https://github.com/muhdharris/WebRTCtest)

## Stack

```
network    TCP/IP · OSPF · EIGRP · VLANs · NAT · subnetting
security   firewalls · ACLs · VPN · IDS/IPS · Wireshark · Nmap
platform   Proxmox VE · Docker · Linux · AWS (coursework)
code       Python · Java · JavaScript · MySQL
labs       GNS3 · Packet Tracer
```

## Contact

[muhdharris40@gmail.com](mailto:muhdharris40@gmail.com) ·
[LinkedIn](https://linkedin.com/in/muhdharris) ·
[muhdharris.github.io](https://muhdharris.github.io)

Malay (native) · English (fluent)
