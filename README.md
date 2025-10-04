# Network-traffic-capture-and-analysis-with-Wireshark
## AIM:
To capture and analyze network traffic using Wireshark in order to observe protocols, packets, and potential anomalies.
## Requirements:
- **Hardware:**
    - Computer with internet access
    - Network adapter (Ethernet/Wi-Fi)
- **Software:**
    - Wireshark (latest stable version)
    - Sample PCAP files (optional for offline analysis)
## Architecture:
```mermaid
flowchart TD
    A[Network Interface Card] --> B[Wireshark Packet Capture Engine]
    B --> C[Packet Decoder & Protocol Analyzer]
    C --> D[Packet Display & Filtering Interface]
    D --> E[Investigator Analyzes Network Data]
    E --> F[Findings: IPs, Ports, Protocols, Anomalies]
```
## DESIGN STEPS:
### Step 1:
Install Wireshark on the system.

### Step 2:
Launch Wireshark and select the network interface (Ethernet/Wi-Fi).

### Step 3:
Start the capture, apply filters (like http, tcp, ip.addr == x.x.x.x) to analyze specific traffic, and stop the capture after observing relevant data.
### Step 4:
**Analyze traffic to identify:**
  - Source & Destination IP addresses
  - Protocols (HTTP, DNS, TCP, UDP, etc.)
  - Suspicious activities (e.g., unusual ports, repeated requests).
## PROGRAM:
Wireshark Packet Capture and Filter Usage
<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/35c0a806-9d1a-4852-bdae-32a63a639cf8" />

<img width="1918" height="1075" alt="image" src="https://github.com/user-attachments/assets/0ee16cfa-5a83-4a80-8bec-58aa8f12469d" />




## OUTPUT:
Captured Packets with Protocol Analysis and Detailed Packet Info

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/e2b99472-7f90-4234-8db3-ee49b4865a7a" />

<img width="1918" height="1079" alt="image" src="https://github.com/user-attachments/assets/cd74855e-8f38-4f27-9a8d-0999b7f087f2" />

<img width="1918" height="1076" alt="image" src="https://github.com/user-attachments/assets/3f5d9966-175d-4d52-a8de-67e91cc11eee" />

## RESULT:
Network traffic was successfully captured and analyzed using Wireshark.
