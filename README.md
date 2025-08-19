# SHIELD-i46
Dataset collected by i46 as part of the CyberSecDome project(SHIELD) for cybersecurity research and testing.

# CyberSecDome Network Traffic Dataset
This repository contains network traffic datasets collected by **i46** as part of the **CyberSecDome** project.  
The dataset supports research and development of advanced Intrusion Prevention System (IPS) models by providing representative samples of both **malicious** and **benign** network traffic.

## Dataset Overview
The dataset includes various attack scenarios and normal network operations captured in **PCAP format**:

| File Name                  | Description |
|----------------------------|-------------|
| `5G_DDOS.pcap`             | 5G network traffic during DDoS attacks. |
| `5G_normal.pcap`           | Normal 5G network traffic for baseline comparison. |
| `ddos-from-inside.pcap`    | DDoS attacks originating from internal hosts. |
| `ddos-from-outside.pcap`   | DDoS attacks originating from external sources. |
| `port-scanning.pcap`       | Network reconnaissance traffic where attackers probe ports/services. |
| `email.pcap`               | Suspicious email activity simulating phishing/spam. |
| `os.pcap`                  | Benign operating system update traffic. |
| `normal.pcap`              | Normal network traffic without attacks. |

## Usage
These PCAP files can be used for:  
- Replay and analysis of network traffic.  
- Training and validation of intrusion detection and prevention systems (IDS/IPS).  
- Research on attack detection patterns and traffic characterization.

## Credit
Data collected by **i46** as part of the **CyberSecDome** project.  
Please acknowledge the source if you use this dataset in your work.
