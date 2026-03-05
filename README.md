# DFIR-projects

## Digital Forensics Investigation
Conducted a forensic investigation of an E01 disk image using X-Ways Forensics to determine whether unauthorized access had occurred to files stored on a Google Drive account.

The investigation analysed multiple digital artefacts including browser history, web cache, Windows Registry entries, USB device metadata, Recycle Bin artefacts, and filesystem data such as the Master File Table ($MFT).

Evidence showed that files were accessed, downloaded, and transferred to an external USB device. A professional forensic timeline was constructed by correlating timestamps from multiple artefact sources to reconstruct the sequence of events in a format suitable for investigative or legal reporting.

## Malware Analysis & Reverse Engineering
Investigated a suspected malware infection using a forensic disk image, memory data, and a live assessment VM. The analysis examined key indicators including processes, network ports, filesystem artefacts, Prefetch data, and PowerShell command history to determine how the system was compromised.

The malware sample was unpacked and analysed using static analysis techniques in Ghidra. Reverse engineering identified network-related API calls such as InternetOpenA, InternetConnectA, and InternetCloseHandle from the WinINet library, confirming the malware’s ability to establish outbound network communication consistent with Trojan-style behaviour.

Evidence from disk artefacts, PowerShell activity, and reverse engineering findings was correlated to reconstruct the infection timeline and demonstrate how the malware was deployed and executed on the system.

## Network Security
Configured and secured network devices using Cisco Packet Tracer. This included implementing device and administrator passwords, configuring AAA server authentication, and setting up GRE tunnelling between network devices to simulate secure communication across networks.

## Docker
Used Docker to build and run containerised environments as part of coursework. This involved creating and managing containers, running applications inside isolated environments, and understanding how containerisation can be used to deploy and manage services efficiently.
