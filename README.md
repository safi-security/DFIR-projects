# DFIR-projects

## Digital Forensics Investigation
Conducted a forensic investigation of an E01 disk image using X-Ways Forensics to determine whether unauthorized access had occurred to files stored on a Google Drive account.

The investigation analysed multiple digital artefacts including browser history, web cache, Windows Registry entries, USB device metadata, Recycle Bin artefacts, and filesystem data such as the Master File Table ($MFT).

Evidence showed that files were accessed, downloaded, and transferred to an external USB device. A professional forensic timeline was constructed by correlating timestamps from multiple artefact sources to reconstruct the sequence of events in a format suitable for investigative or legal reporting.

## Malware Analysis & Reverse Engineering
Investigated a suspected malware infection using a forensic disk image, memory data, and a live assessment VM. The analysis examined key indicators including processes, network ports, filesystem artefacts, Prefetch data, and PowerShell command history to determine how the system was compromised.

The malware sample was unpacked and analysed using static analysis techniques in Ghidra. Reverse engineering identified network-related API calls such as InternetOpenA, InternetConnectA, and InternetCloseHandle from the WinINet library, confirming the malware’s ability to establish outbound network communication consistent with Trojan-style behaviour.

Evidence from disk artefacts, PowerShell activity, and reverse engineering findings was correlated to reconstruct the infection timeline and demonstrate how the malware was deployed and executed on the system.

## Network Security Configuration
Designed and secured a simulated enterprise network using Cisco Packet Tracer based on a real-world brief for the GÉANT research network. The project involved configuring secure communication between multiple network segments including a DMZ, internal headquarters network, and a remote site.

Security controls implemented included AAA authentication using a RADIUS server with local fallback accounts, SSH for secure device management, and 802.1X port-based authentication to restrict network access to authorised devices. Additional protections included disabling unused ports, applying port security, and configuring access control lists (ACLs) to restrict network traffic.

Secure routing between networks was achieved using OSPF combined with a GRE tunnel and VPN-style encryption to protect data travelling across the internet. The network was tested using connectivity and security validation checks to confirm that authentication, routing, and security controls were functioning correctly.

## Cloud Security & Containerised Home Lab

Built a secure cloud-based home lab environment using Docker Compose to deploy and manage multiple containerised services. The environment included a reverse proxy, identity management system, password manager, and security testing environment.

A reverse proxy was implemented using Nginx Proxy Manager with automated SSL certificates from Let’s Encrypt to provide encrypted HTTPS access to internal services. Authentication was centralised using Authentik to provide single sign-on (SSO) with multi-factor authentication (MFA) for protected applications.

Additional services included Vaultwarden for secure password management, Portainer for container administration, and a custom homepage dashboard to monitor running services. A containerised Kali Linux environment was also deployed to provide a browser-accessible penetration testing platform within the isolated lab infrastructure.
