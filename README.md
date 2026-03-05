# DFIR Projects

This repository contains a selection of cybersecurity projects completed during my university studies. The work focuses on **digital forensics, malware analysis, cloud security, and network security**, demonstrating practical investigation and secure system configuration.

---

## Malware Analysis & Reverse Engineering

Analysed a malware infection using forensic disk images, memory data, and a live investigation environment. The malware sample was unpacked and reverse engineered using **Ghidra**, identifying WinINet API calls such as `InternetOpenA`, `InternetConnectA`, and `InternetCloseHandle` used to establish outbound network communication.

**Tools:** Ghidra, static malware analysis, DFIR investigation

---

## Digital Forensics Investigation

Conducted a forensic investigation of an **E01 disk image** using **X-Ways Forensics** to determine whether files stored on a Google Drive account were accessed and exfiltrated. Multiple artefacts including browser history, registry entries, USB metadata, and filesystem records were analysed to reconstruct the event timeline.

**Tools:** X-Ways Forensics, artefact analysis, timeline reconstruction

---

## Cloud Security & Containerised Home Lab

Built a secure **cloud-hosted home lab** using **Docker Compose** to deploy containerised services including a reverse proxy, identity management system, password manager, and monitoring dashboard.

Authentication was protected using **Authentik Single Sign-On (SSO) with Multi-Factor Authentication (MFA)**, while **Nginx Proxy Manager and Let’s Encrypt** provided encrypted HTTPS access to all services.

**Technologies:** Docker, Nginx Proxy Manager, Authentik, Vaultwarden, Portainer

---

## Network Security Configuration

Designed and secured a simulated enterprise network using **Cisco Packet Tracer**. Security controls included **AAA authentication using RADIUS, SSH for secure device management, 802.1X port authentication, access control lists (ACLs), and secure routing using OSPF with GRE tunnels**.

**Technologies:** Cisco networking, AAA, 802.1X, ACLs, OSPF, GRE
