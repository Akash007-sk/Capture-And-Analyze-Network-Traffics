*Capture-And-Analyze-Network-Traffics

Network Traffic Analysis using Wireshark (Linux)
Abstract
This report presents a detailed analysis of network traffic using Wireshark in a Linux environment. It involves capturing live packets, applying filters, and analyzing protocols such as DNS, TCP, ICMP, and TLS.

Introduction
Network traffic analysis is an essential concept in cybersecurity. Wireshark is a powerful open-source tool used to capture and inspect data packets in real time.

Objectives
- Capture live network traffic
- Analyze protocols
- Understand packet structure
- Perform real-time monitoring

Tools Used
- Wireshark
- Linux OS
- Npcap/libpcap
- Terminal utilities (ping, nslookup, curl)

System Requirements
- Linux (Ubuntu/Kali)
- 4GB RAM
- Internet connection

Methodology
The methodology involves launching Wireshark, capturing packets, generating traffic, applying filters, and analyzing results.

Step-by-Step Procedure
1. Launch Wireshark using sudo
2. Select wlan0 interface
3. Start packet capture
4. Generate traffic using ping, nslookup, curl
5. Stop capture after 60 seconds
6. Apply filters (dns, tcp, icmp, tls)
7. Analyze packets
8. Save capture file
9. Take screenshots

Detailed Explanation
Each step involves capturing and analyzing packet-level data. DNS resolves domains, TCP ensures reliable communication, ICMP checks connectivity, and TLS secures data.
Protocol Analysis
DNS: Domain resolution
TCP: Reliable communication
ICMP: Connectivity testing
TLS: Encrypted communication

Packet Structure
Packets contain multiple layers: Frame, Ethernet, IP, Transport, and Application.

Diagrams
TCP Handshake:
SYN -> SYN-ACK -> ACK

DNS Flow:
Query -> Response

Layer Model:
Application -> Transport -> Network -> Data Link -> Physical
Screenshots Description
Includes capture screen, DNS filter, ICMP packets, TCP handshake, TLS traffic.

Observations
- DNS queries observed
- TCP handshake observed
- ICMP replies received
- HTTPS encrypted traffic detected

Advantages
- Real-time monitoring
- Deep packet inspection
- Protocol analysis

Limitations
- Cannot decrypt HTTPS without keys
- Requires technical knowledge

- Intrusion detection
Conclusion
This project provided hands-on experience in network traffic analysis using Wireshark. It enhanced understanding of protocols.
