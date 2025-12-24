# Network Traffic Analysis with Wireshark

## Overview
This project demonstrates basic network traffic analysis using Wireshark.
The goal was to capture live traffic, establish a baseline, and analyze common protocols used in everyday network communication.

## Tools Used
- Wireshark
- Local network traffic

## Objectives
- Capture live network traffic
- Identify common protocols (DNS, TCP, TLS)
- Compare encrypted vs unencrypted traffic
- Analyze packet timing using delta time

## Observations

### Baseline Traffic
Captured mixed network traffic including ARP, DNS, TCP, and TLS, demonstrating normal background network activity.

### DNS Analysis
Observed DNS queries and responses over UDP port 53, including visible domain name resolution.

### Encrypted Traffic (TLS)
Analyzed TLS-encrypted traffic over HTTPS, noting that application payloads are not readable, but metadata remains visible.

### Delta Time Analysis
Identified packets with unusually high delta times, which may indicate latency, application-level delays, or timing irregularities in network communication.

## Screenshots
Screenshots of the captures and filtered traffic are included in the '/screenshots' directory.
