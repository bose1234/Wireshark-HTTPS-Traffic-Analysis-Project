# Wireshark-HTTPS-Traffic-Analysis-Project
This project demonstrates hands-on network traffic analysis using Wireshark, with a focus on TCP and HTTPS (port 443) traffic. 
The capture analyzes encrypted web communication between a local host and a public IP address, highlighting TCP behaviors such as sequence numbers, 
acknowledgments, window sizes, and payload segmentation. The goal of this project is to showcase practical skills in network analysis, packet inspection, 
and understanding secure communications, making it suitable for entry-level cybersecurity and SOC analyst portfolios.
What Was Analyzed

Protocol: TCP (HTTPS over port 443)

Source IP: 192.168.0.51 (Local machine)

Destination IP: 2.23.210.34 (Public server)

Packet Length: ~1454 bytes

Flags Observed: PSH, ACK

Traffic Type: Encrypted HTTPS data exchange

 *Key Observations*

TCP three-way handshake successfully established

Encrypted payloads confirmed (HTTPS)

Proper acknowledgment and sequencing of packets

No packet loss observed in the selected frames

Normal window size advertisement, indicating stable communication

 *Tools Used*

Wireshark – Packet capture and inspection

Windows OS – Capture environment

TCP/IP Protocol Suite – Traffic analysis

 *Repository Contents*

screenshots/ – Wireshark capture screenshots

analysis-notes.md – Detailed packet-level explanations

README.md – Project documentation

 *How to Reproduce This Capture*

Install Wireshark

Start packet capture on your active network interface

Open a secure website (HTTPS)

Stop capturing after traffic is generated

Apply filter: tcp.port == 443

Analyze TCP flags, sequence numbers, and payload size

 *Skills Demonstrated*

Network traffic analysis

TCP/IP fundamentals

HTTPS traffic understanding

Packet-level troubleshooting

Cybersecurity documentation



👩🏽‍💻 Author

Abosede Ogunlade
Cybersecurity Analyst | Digital Marketer | Technical Content Creator

 Why This Project Matters

This project shows practical cybersecurity skills beyond theory, proving the ability to analyze real-world network traffic—an essential 
skill for SOC Analysts and Network Security roles.
