# home-network-lab
About: 3 Devices (2 windows, 1 parrot os) used for Networking configuration (Cisco / Packet Tracer) and Cryptography / Cybersecurity projects

I've made a list of the projects I am doing listed from Beginner -> Intermediate -> Advanced

More projects will be added or changed while I do them.

Networking - Cisco / Packet Trainer

Beginner:
* Basic Home Networking Mapping
	* Document my current home network (router, devices, IP ranges) and store the diagram + notes.
* Packet Tracer: Build a small LAN
	* Two switches, a router, and 4-6 PCs; configure IP addressing, default gateways, and basic connectivity tests.
* VLANs and inter-VLAN routing
	* Create multiple VLANs in Packet Tracer, assign switch ports, configure router-on-a-stick, and test ping accross VLANs

Intermediate:
* DHCP, DNS, and NAT scenarios
	* Design networks with a central router doing DHCP and NAT, plus a simulated DNS server; test name resolution and internet access
* Router Security Basics
	* Configure local user accounts, SSH access, and basic ACLs to restrict management access in Packet Tracer.
* Redundant Links and STP
	* Build a multi-switch topology with redundant links; observe how spanning tree prevents loops and document behaviour

Advanced:
* Multi-site Network Design
	* Create a multi-router topology representing branch offices; implement static dynamic routing (e.g. OSPF) and verify convergence.
* QoS and Traffic Prioritisation
	* Classify and prioritise traffic scenarios, document impact on simulated voice vs data.
* Network Hardening Project
	* Combine VLANs, ACLs, Secure Management, logging, and segmentation into a "secure small business" Packet Tracer design.

Cyber-Security - Parrot OS / Penetration Testing

Beginner:
* Parrot OS Tool Familiarisation
	* Catalogue major tools (Nmap, Wireshark, Burp, Metasploit, etc) and create a Github repo with short cheat sheets and sample commands
* Local Lab Scanning
	* Use Nmap to scan my home devices; record findings (open ports, services) and how I secured them.
* Basic Traffic Analysis
	* Capture traffic with Wireshark from your own devices and practice identifying common protocols and simple misconfigurations

Intermediate:
* Vunlerabe VM Lab
	* Set up intentionally vulnerable VMs isolated from the main network; document setup and finding in Github
* Web Application Security Basics
	* Run a local, intentionally vulnerable webl app; use Parrot toosl to explore common issues with al testing kept to the lab.
* Password and Credential Hygiene Project
	* Evaluate and improve my own password policies, MFA, and secure storage; document a personal security baseline.

Advanced:
* Full "home network security assessment"
	* Plan, execute and document a structured assessment of my home lab: threat model, scanning, exploitation attempts in the controlled environment, mitigations and reassessment.
* Secure logging and monitoring
	* Set up a small olgging stack to monitor my lab, and write detection use-cases for suspicious activity
* Hardening + compliance mini-project
	* Pick a baseline and systematically apply relevant controls to your lab, documenting each control.
