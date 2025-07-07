# DNS Port 53 Incident

This project simulates an incident investigation where clients were unable to access the website www.yummyrecipesforme.com, receiving the error "destination port unreachable."

## 📄 Files
- Cybersecurity-Incident-Report-Network-Traffic-Analysis.pdf – Final incident report analyzing traffic on port 53 (DNS)
- tcpdum-log.png – Screenshot of the captured network traffic

## 💻 Scenario
As a cybersecurity analyst working for an IT services company, I captured and analyzed network traffic to identify the cause of the issue. The analysis revealed that when sending UDP packets to the DNS server (port 53), ICMP error messages were returned, indicating that the DNS service was unreachable—possibly due to a DoS attack or server configuration issue.

## 🛠️ Tools & Methods
- tcpdump for capturing traffic
