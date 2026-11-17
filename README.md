SOC Project 01 — Network Traffic Investigation
Status: In Progress
Difficulty: Beginner
Focus: Networking Fundamentals | DNS Analysis | Network Traffic Investigation
Overview
This project documents my hands-on learning and analysis of network communication from a Security Operations Center (SOC) perspective.
The goal is to develop foundational skills in IP addressing, DNS, TCP/UDP, and network traffic analysis before progressing into more advanced security investigations.
Objectives
•	Understand how computers communicate across networks.
•	Identify IPv4 and IPv6 addressing.
•	Analyze DNS queries and responses.
•	Learn TCP/UDP behavior and common network ports.
•	Capture and inspect network traffic using Wireshark.
•	Practice evidence-based security investigation and documentation.
Lab Environment
Component	Details
Operating System	Windows
Environment	Personal authorized lab
Initial Tools	Command Prompt, ipconfig, nslookup
Planned Analysis Tool	Wireshark
Progress
•	Lesson 1 — IP Addressing and Network Fundamentals
•	Lesson 2 — DNS Fundamentals and Lookup Analysis
•	Lesson 3 — TCP vs. UDP
•	Lesson 4 — Ports and Protocols
•	Practical Network Traffic Capture
•	Final Investigation Report
Initial Findings
Network Configuration
Using ipconfig, I identified a private IPv4 address and an IPv6 link-local default gateway.
This helped me understand the role of network interfaces, private addressing, and routing.
DNS Investigation
Using Windows networking tools, I identified configured IPv4 and IPv6 DNS servers and performed a lookup for example.com.
The lookup returned multiple A (IPv4) and AAAA (IPv6) addresses.
I learned how DNS resolution works and how DNS telemetry can help analysts identify potentially suspicious domain activity.
Security Analysis
During a simulated investigation involving repeated DNS queries to an unfamiliar domain, I identified several useful investigative steps:
1.	Examine the frequency and timing of the requests.
2.	Review related network protocols and connection evidence.
3.	Determine whether other workstations exhibit similar behavior.
4.	Correlate DNS activity with endpoint and threat intelligence data.
Repeated DNS activity alone does not prove a compromise; additional evidence is necessary.
Next Steps
•	Complete TCP/UDP fundamentals.
•	Investigate common network protocols.
•	Begin packet analysis with Wireshark.
•	Document observed traffic and supporting evidence.
Disclaimer
All activities are performed in an authorized personal lab or use synthetic/public training data. No unauthorized scanning or investigation is conducted.

