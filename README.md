# Wireshark SOC Analyst Labs: Network Traffic Analysis & Threat Detection

## Project Overview

As part of my cybersecurity learning journey and practical SOC Analyst training, I successfully completed six hands-on Security Operations Centre (SOC) labs provided by **NetworkWalks**.

Each lab consisted of 10 practical tasks, giving me the opportunity to develop and strengthen my skills in network traffic analysis, packet inspection, threat detection, and network forensics using Wireshark.

These exercises provided practical exposure to investigating suspicious network activities, identifying potential attackers, reconstructing network communications, detecting exposed credentials, and analysing malicious activities.

## Project Objectives

- Develop practical skills in network traffic analysis using Wireshark.
- Identify suspicious IP addresses and potential attackers.
- Reconstruct TCP communication sessions.
- Investigate HTTP traffic and identify exposed credentials.
- Detect brute-force attacks through repeated authentication attempts.
- Analyse suspicious network communications.
- Understand how network evidence supports security investigations.

## Tools and Technologies

| Tool/Technology | Purpose |
|---|---|
| Wireshark | Network packet analysis and traffic inspection |
| PCAP Files | Captured network traffic for investigation |
| TCP Stream Analysis | Reconstructing network conversations |
| HTTP Analysis | Examining web traffic and exposed information |
| Display Filters | Isolating relevant network packets |
| Network Forensics | Investigating suspicious network activities |

## SOC Labs Completed

### Lab 1: Identify the Attacker's IP

**Lab Link:** https://networkwalks.com/wireshark-lab3/

**Objective:** Identify the attacker's IP address by examining captured network traffic.

**Investigation Activities:**
- Opened and examined the provided PCAP file.
- Analysed source and destination IP addresses.
- Inspected network communication patterns.
- Investigated suspicious traffic.
- Identified the suspected attacker's IP address.

**Skills Developed:** IP address identification, packet inspection, and network traffic investigation.

### Lab 2: Follow TCP Stream 1

**Lab Link:** https://networkwalks.com/wireshark-lab4/

**Objective:** Reconstruct network conversations and examine transmitted information.

**Investigation Activities:**
- Examined the provided packet capture.
- Identified relevant TCP packets.
- Used Wireshark's Follow TCP Stream feature.
- Reconstructed communication sessions.
- Examined the transmitted data.

**Skills Developed:** TCP stream analysis, session reconstruction, and network communication investigation.

### Lab 3: Follow TCP Stream – Part 2

**Lab Link:** https://networkwalks.com/wireshark-lab5/

**Objective:** Practise TCP stream analysis using another packet capture and uncover hidden information within network communications.

**Investigation Activities:**
- Analysed the provided PCAP file.
- Identified relevant TCP conversations.
- Applied the Follow TCP Stream feature.
- Reconstructed network communication.
- Examined recovered information.

Skills Developed: TCP stream analysis, packet reconstruction, and network forensic investigation.

Lab 4: HTTP Plain Text Credentials

Lab Link: https://networkwalks.com/wireshark-lab6/

Objective: Identify usernames and passwords transmitted in clear text over HTTP.

Investigation Activities:
- Applied HTTP display filters.
- Examined HTTP requests and responses.
- Inspected relevant packet details.
- Identified exposed credentials.
- Investigated the security implications of transmitting sensitive information without encryption.

**Skills Developed:** HTTP traffic analysis, credential exposure detection, and security risk identification.

### Lab 5: Catch the Brute Force Attacker

**Lab Link:** https://networkwalks.com/wireshark-lab7/

**Objective:** Detect repeated login attempts and identify the source of a potential brute-force attack.

**Investigation Activities:**
- Examined FTP authentication traffic.
- Applied relevant Wireshark display filters.
- Identified repeated username requests.
- Analysed source and destination IP addresses.
- Used Follow TCP Stream to reconstruct the FTP communication.
- Examined authentication attempts and server responses.
- Identified the successful login attempt.

**Investigation Findings:**

| Parameter | Finding |
|---|---|
| Source IP | 192.168.10.66 |
| Destination IP | 192.168.10.20 |
| Protocol | FTP |
| Target Username | admin |
| Successful Authentication Response | 230 Login successful |

Security Observation:

The investigation demonstrated how repeated authentication attempts can reveal brute-force activity. It also highlighted the risks of using unencrypted FTP, where credentials may be exposed during network transmission.

**Skills Developed:** FTP traffic analysis, brute-force detection, TCP stream reconstruction, and network forensics.

### Lab 6: Catch the Call Scammer

**Lab Link:** https://networkwalks.com/wireshark-lab8/

**Objective:** Investigate captured network traffic, analyse the recorded call, and identify the suspected scammer.

**Investigation Activities:**
- Examined the provided packet capture.
- Investigated relevant communication traffic.
- Analysed the recorded call.
- Examined available evidence.
- Used the investigation findings to identify the suspected scammer.

**Skills Developed:** Network forensics, communication analysis, audio investigation, and evidence-based threat investigation.

## Key Skills Developed

Through these six practical SOC labs, I strengthened my understanding of:

- Network Traffic Analysis
- Wireshark Packet Inspection
- Network Protocol Analysis
- TCP Stream Reconstruction
- HTTP Traffic Analysis
- Credential Exposure Detection
- Brute-Force Attack Investigation
- IP Address Identification
- Network Forensics
- Threat Detection and Investigation

## Screenshots and Investigation Evidence

This repository contains screenshots documenting my practical investigations across the six SOC labs.

The screenshots provide visual evidence of the packet analysis, network traffic inspection, communication reconstruction, and investigation activities performed during the exercises.

Each lab has a dedicated folder containing its corresponding investigation screenshots.
Key Learning Outcomes

Completing these exercises improved my understanding of how SOC Analysts investigate network-based security incidents.

I gained practical experience in:

- Examining captured network traffic to identify suspicious activities.
- Analysing communication between different network hosts.
- Identifying potential brute-force attacks.
- Detecting credentials exposed through unencrypted protocols.
- Reconstructing network conversations to understand transmitted information.
- Using packet-level evidence to support security investigations.

These experiences have further strengthened my interest in Blue Team operations, SOC analysis, network security, and incident response.

## Acknowledgement

Special appreciation to **NetworkWalks** for providing these practical cybersecurity lab exercises and supporting my continuous learning journey.

Conclusion

Successfully completing these six Wireshark SOC labs is another important milestone in my cybersecurity journey.

I look forward to applying these practical skills to more advanced security investigations, improving my analytical capabilities, and developing towards a career as a **SOC Analyst and Incident Response Specialist.

Learning by doing. Investigating with evidence. Building a career in cybersecurity.

Author: Sani Suleiman  
Focus Areas: SOC Analysis | Blue Team | Network Security | Incident Response

Training Provider: NetworkWalks

#Cybersecurity #SOCAnalyst #Wireshark #NetworkForensics #BlueTeam #ThreatDetection #IncidentResponse
