# 📡 Network Engineering Cheat Sheet

## 🏗 OSI vs. TCP Model: Pros, Cons, and Why It Matters  

| Feature | OSI Model | TCP/IP Model | Why It Matters |
|---------|----------|-------------|---------------|
| **Structure** | 7 layers | 4 layers | OSI provides a detailed conceptual framework, while TCP/IP is more practical. |
| **Usage** | Theoretical reference model | Widely used in real networks | Understanding OSI helps in troubleshooting; TCP/IP is used in real-world networking. |
| **Flexibility** | Highly modular | Less modular | OSI is better for learning; TCP/IP is easier to implement. |
| **Protocol Dependency** | Protocol-independent | Tightly bound to TCP/IP suite | OSI supports different network technologies, whereas TCP/IP dominates the internet. |
| **Popularity** | Academic and training-focused | Standard model for internet communications | Knowing both ensures deeper networking knowledge. |

---

## 🔌 Common Network Ports: Pros, Cons, and Why It Matters  

| Port | Protocol | Pros | Cons | Why It Matters |
|------|----------|------|------|---------------|
| 20, 21 | FTP | Reliable file transfer | Unencrypted, insecure | Use SFTP (Port 22) for secure transfers. |
| 22 | SSH | Secure remote access | Requires configuration | Essential for secure device management. |
| 25 | SMTP | Email sending | Often blocked due to spam | Use SMTP over TLS for security. |
| 53 | DNS | Resolves domain names | Vulnerable to spoofing | Use DNSSEC for security. |
| 80 | HTTP | Universal web access | Unencrypted | Use HTTPS (Port 443) for security. |
| 443 | HTTPS | Secure web traffic | Slightly higher overhead | Essential for modern web security. |

---

## 📌 Useful Nuggets for Network Engineers  

| Concept | Key Takeaways |
|---------|--------------|
| **Subnetting** | Understand CIDR notation, subnet masks, and IP ranges for efficient network design. |
| **VLANs** | Segment networks logically to improve security and efficiency. |
| **Routing Protocols** | Know the difference between OSPF, BGP, and EIGRP for scalable networking. |
| **Firewalls & ACLs** | Control inbound/outbound traffic to enhance security. |
| **NAT & PAT** | Understand address translation for public/private IP management. |
| **Wireshark & Packet Analysis** | Essential for troubleshooting and network forensics. |
| **Cloud Networking** | Learn AWS, Azure, and hybrid networking concepts. |
| **Zero Trust Security** | Assume breaches and verify all connections. |

---

## ☁️ Cloud Networking: AWS vs. GCP vs. Azure – Pros, Cons, and Why It Matters  

| Feature | AWS | Google Cloud (GCP) | Microsoft Azure | Why It Matters |
|---------|-----|----------------|---------------|---------------|
| **Market Share** | Largest (dominant leader) | Smaller but growing | Strong enterprise adoption | AWS has the widest adoption, but Azure is popular with Microsoft-based businesses. |
| **Networking Strength** | Scalable global infrastructure, strong VPC | High-speed private fiber network | Integrated with Microsoft tools, hybrid cloud | Choosing the right provider depends on business needs. |
| **Pricing** | Pay-as-you-go, flexible savings plans | Competitive pricing with sustained use discounts | Enterprise agreements, pay-as-you-go | Cost efficiency varies based on workload. |
| **Ease of Use** | Extensive documentation, complex UI | Developer-friendly, AI/ML integration | Best for hybrid cloud with on-prem integration | GCP is ideal for data-heavy applications, Azure for enterprises. |
| **Security** | Strong IAM, security groups, compliance | Default encryption, strong AI-driven security | Enterprise-grade security, integrated with Microsoft Defender | Security features impact cloud compliance. |
| **Multi-Cloud & Hybrid Support** | AWS Outposts for hybrid, limited multi-cloud | Anthos for strong multi-cloud | Azure Arc for hybrid and multi-cloud | Hybrid and multi-cloud strategies improve flexibility. |
| **Best For** | Large enterprises, startups, general cloud workloads | AI, big data, analytics, high-speed networking | Enterprises using Microsoft products, hybrid environments | Choosing a provider depends on specific project requirements. |

---

### 🚀 Want to Learn More?
Check out additional resources:
- [Cisco Networking Academy](https://www.netacad.com/)
- [AWS Certified Advanced Networking](https://aws.amazon.com/certification/certified-advanced-networking-specialty/)
- [Microsoft Azure Networking](https://learn.microsoft.com/en-us/azure/networking/)
- [Google Cloud Networking](https://cloud.google.com/networking)

👨‍💻 **Contributed by:** [Maurice McDonald]

📌 **GitHub Repository:** [https://github.com/emcdo411/network-engineer-nugget]  
🔥 Star this repo if you found it helpful!
