# 100 Interview Questions for Computer Networks

## 🔹 Section 1: Fundamentals & Layered Architecture

1. What is the OSI model? Explain each layer with a real-world analogy.
2. How does the TCP/IP model differ from the OSI model?
3. Why is layering important in network design?
4. What are protocols? Name a few used at each OSI layer.
5. How does encapsulation work as data travels down the layers?
6. What is MTU and how is fragmentation handled?
7. What happens when you type a URL in the browser?
8. Explain the difference between circuit-switching and packet-switching.
9. Why are protocols like HTTP called stateless?
10. What is the difference between data, segment, packet, and frame?

## 🔹 Section 2: Application Layer

11. What is DNS and how does it work?
12. How does HTTP/1.1 differ from HTTP/2?
13. What is HTTPS and how does SSL/TLS work?
14. What is a CDN and how does it improve performance?
15. How does email transmission work (SMTP, IMAP, POP3)?
16. How does content negotiation work in REST APIs?
17. What are cookies, sessions, and JWTs?
18. How does a reverse proxy server work?
19. What’s the difference between a forward proxy and a reverse proxy?
20. How does load balancing work at the application layer?

## 🔹 Section 3: Transport Layer

21. What is TCP? How does it ensure reliable transmission?
22. How does TCP 3-way handshake work?
23. What is a SYN flood attack?
24. What are TCP flags (SYN, ACK, FIN, RST)?
25. Explain flow control and congestion control in TCP.
26. What is the sliding window protocol?
27. What is UDP and where is it used?
28. How do QUIC and SCTP compare to TCP?
29. How does port multiplexing work in transport protocols?
30. When would you prefer UDP over TCP?

## 🔹 Section 4: Network Layer

31. What is an IP address? What are IPv4 and IPv6?
32. How does subnetting work?
33. What is CIDR notation and why is it used?
34. How does ARP work?
35. What is ICMP and how is it used in ping and traceroute?
36. How does NAT (Network Address Translation) work?
37. What is the difference between private and public IPs?
38. How do routing protocols like OSPF and BGP work?
39. How does a router differ from a switch?
40. What’s the role of TTL in an IP packet?

## 🔹 Section 5: Data Link Layer

41. What is MAC addressing and how is it different from IP addressing?
42. How does a switch use MAC addresses to forward frames?
43. What is ARP poisoning and how can it be mitigated?
44. How does VLAN work?
45. What are STP and RSTP protocols?
46. Explain CSMA/CD and CSMA/CA.
47. What are the components of an Ethernet frame?
48. What is PPP and how is it used?
49. How does a DHCP server assign IP addresses?
50. What are broadcast, unicast, and multicast communications?

## 🔹 Section 6: Physical Layer

51. What are the different types of transmission media?
52. Explain the difference between baseband and broadband.
53. How does signal attenuation affect communication?
54. What is the Nyquist theorem?
55. What is modulation and why is it used?
56. What is bandwidth and how is it measured?
57. What are bit rate and baud rate?
58. How does Manchester encoding work?
59. What is multiplexing (TDM, FDM, WDM)?
60. What are the standard Ethernet cable types (Cat5e, Cat6)?

## 🔹 Section 7: Network Security

61. What is a firewall and how does it work?
62. What is a VPN and how does it ensure privacy?
63. How does SSL/TLS handshake work?
64. What are symmetric and asymmetric encryption?
65. What are common network attacks (DDoS, MITM, spoofing)?
66. How do intrusion detection and prevention systems work?
67. What is a DMZ in network architecture?
68. What is the difference between IPSec and TLS VPNs?
69. How do digital certificates and CAs work?
70. What is port scanning and how can it be detected?

## 🔹 Section 8: Wireless and Mobile Networks

71. How does Wi-Fi authentication (WPA2, WPA3) work?
72. What causes packet loss and jitter in wireless networks?
73. What are the differences between 4G, 5G, and Wi-Fi 6?
74. What is handoff in mobile networks?
75. How does roaming work in cellular networks?
76. How does TCP handle mobility?
77. How do mobile IP and tunneling protocols work?
78. What is the role of SSID and BSSID in Wi-Fi?
79. What are hidden node and exposed node problems?
80. How does beamforming improve wireless coverage?

## 🔹 Section 9: Cloud, SDN & Modern Networks

81. What is a VPC in AWS or other cloud environments?
82. What is Software Defined Networking (SDN)?
83. What is Network Function Virtualization (NFV)?
84. How do containers and Kubernetes handle networking?
85. What is a service mesh (Istio, Linkerd)?
86. How does DNS work in Kubernetes?
87. What are overlay networks (VXLAN, GRE)?
88. How does NAT Gateway differ from Internet Gateway in cloud?
89. How is Zero Trust Networking different from perimeter-based security?
90. What is network slicing in 5G?

## 🔹 Section 10: Troubleshooting, Tools & Real-World Scenarios

91. How do you troubleshoot high latency in a web application?
92. What tools do you use to diagnose network issues (ping, traceroute, tcpdump)?
93. How would you debug a DNS resolution failure?
94. How do you determine whether a problem is in your network or the server?
95. What is the role of Wireshark in packet analysis?
96. How do you check for a port conflict on a host?
97. What’s the difference between netstat and ss commands?
98. How would you debug a TCP connection timeout?
99. How do CDNs impact latency troubleshooting?
100. How would you design a high-availability network for a SaaS application?


# 🌐 100 Real-World Interview Questions for Computer Networks

---

## 📂 `computer_networks_real_world_questions.md`

```markdown
# 100 Real-World Interview Questions for Computer Networks

## 🔹 Section 1: Network Architecture & Protocols
1. You're designing a messaging app. What protocol would you use for message delivery?
2. How would you implement secure communication over an insecure channel?
3. Your web application needs to support video streaming. Which protocols do you use and why?
4. Explain how DNS resolution works when a user types a URL in a browser.
5. How would you troubleshoot DNS latency for users in a specific region?
6. You need to set up a REST API over HTTPS. What handshake process happens under the hood?
7. What protocol would you use for a stock trading system that requires minimal delay?
8. What are the pros and cons of TCP vs UDP in a real-time multiplayer game?
9. What protocol does WhatsApp use for calling, and why?
10. Your application requires file uploads. Would you use FTP, SFTP, or HTTP?

## 🔹 Section 2: OSI & TCP/IP Models
11. Map each layer of the OSI model to real-world network operations in a web browser.
12. In which layer does SSL/TLS operate, and why?
13. At which layer would you debug a packet fragmentation issue?
14. Give a real-world example where the transport layer impacts application behavior.
15. What kind of issue would you face at the data link layer in a Wi-Fi network?
16. Your packets are arriving out of order. Which OSI layer is responsible?
17. An error occurs due to incorrect routing. Which OSI layer is involved?
18. At which layer would ARP operate and when is it used?
19. You're implementing VPN tunneling. Which OSI layers are affected?
20. Why is TCP/IP a more practical model in system design than OSI?

## 🔹 Section 3: IP Addressing & Subnetting
21. Your office network needs 20 subnets, each with 30 hosts. How would you allocate IPs?
22. Explain CIDR notation in the context of a firewall configuration.
23. You're configuring NAT for a home router. How does it manage multiple devices with one IP?
24. How would you assign IPs to 500 machines with minimal wastage?
25. How would you troubleshoot an IP conflict in a LAN?
26. What's the difference between public and private IPs in cloud deployment?
27. You are asked to separate production and staging environments using subnets. How?
28. A server reports unreachable even though it has a valid IP. What would you check?
29. Why would an enterprise use IPv6 and what challenges might arise?
30. Explain a real-world case where subnetting reduced network congestion.

## 🔹 Section 4: Routing & Switching
31. Your app must be accessible globally with low latency. How would routing help?
32. How does BGP help in building redundant internet paths?
33. What happens if a routing table gets too large? How can you optimize it?
34. A packet isn't reaching its destination. How do you trace the routing path?
35. How would you use traceroute to debug a multi-hop network issue?
36. Explain the role of default gateways in home and enterprise networks.
37. What’s the real-world use of static vs dynamic routing?
38. How would VLANs help separate guest and employee traffic in a network?
39. What’s the function of ARP in switching?
40. Your switch causes a broadcast storm. How do you mitigate it?

## 🔹 Section 5: Firewalls, NAT, and Load Balancing
41. How would you set up a firewall to allow only HTTPS traffic?
42. You're designing a reverse proxy with load balancing. What parameters would you consider?
43. How does NAT traversal affect VoIP or video calls?
44. How does a firewall distinguish between malicious and legitimate traffic?
45. Your app is behind a load balancer. How does it maintain session state?
46. What’s the difference between Layer 4 and Layer 7 load balancers?
47. What is port forwarding and when would you use it?
48. A client can’t reach your web server through the firewall. What checks would you do?
49. Explain how sticky sessions work and when they’re necessary.
50. How would you configure failover for a two-node load-balanced cluster?

## 🔹 Section 6: TCP/UDP and Ports
51. Your application sends duplicate packets over UDP. Why?
52. What causes TCP retransmissions and how do you identify them?
53. Why might you choose TCP for file transfer but UDP for video conferencing?
54. What’s the role of a TCP three-way handshake?
55. How does TCP congestion control work in real life?
56. How do ephemeral ports work in client-server communication?
57. You experience slow file downloads. Is it a TCP window size issue?
58. How does QUIC improve over TCP in web applications?
59. What happens during a TCP connection reset?
60. You run multiple services on a server. How do ports avoid conflict?

## 🔹 Section 7: HTTP, HTTPS, and Web Protocols
61. What’s the difference between HTTP 1.1, 2, and 3?
62. How does TLS work behind HTTPS?
63. Why might HTTP keep-alive improve performance in a REST API?
64. Your server is returning 503 errors intermittently. What’s happening?
65. How do you debug a slow HTTPS handshake?
66. Why is HTTPS essential even for non-login pages?
67. What is HSTS and when should it be used?
68. How do HTTP status codes help in debugging APIs?
69. A frontend app isn't receiving CORS headers. What happens?
70. How do you optimize headers and caching for faster content delivery?

## 🔹 Section 8: Wireless & Mobile Networking
71. What are the causes of Wi-Fi signal interference in home networks?
72. How would you secure a public Wi-Fi access point?
73. Why do mobile networks switch between 4G and Wi-Fi frequently?
74. How does roaming work in mobile data networks?
75. What causes signal handover lag in fast-moving vehicles?
76. How would you debug intermittent packet loss in a corporate Wi-Fi setup?
77. What is the role of SSID and MAC filtering in Wi-Fi security?
78. What’s the difference between WPA2 and WPA3 in practical terms?
79. How does carrier aggregation improve mobile data speeds?
80. Your IoT device loses network often. How do you ensure stable wireless connections?

## 🔹 Section 9: Network Security & Attacks
81. How does a MITM (man-in-the-middle) attack work on public networks?
82. What tools do you use to monitor unauthorized traffic?
83. A customer complains their network is being flooded. How do you detect a DDoS attack?
84. How do VPNs secure traffic on untrusted networks?
85. Explain ARP spoofing and how to prevent it.
86. What is MAC flooding and how is it mitigated?
87. Your HTTPS connection is intercepted. How could this happen?
88. How do firewalls block SQL injection or XSS payloads?
89. Explain DNS poisoning in a real-world example.
90. What is TLS pinning and why is it important in mobile apps?

## 🔹 Section 10: Network Monitoring, Debugging & System Design
91. Your app runs fine locally but fails over a network. What do you check first?
92. How do you use Wireshark to analyze a failed HTTP request?
93. What metrics would you collect to ensure network health in a cloud system?
94. What is the difference between latency, throughput, and jitter? How do you measure them?
95. How would you debug a network bottleneck in a Kubernetes cluster?
96. What are common causes of high network latency in cloud applications?
97. You need to design a CDN-backed global website. How would you minimize latency?
98. What is your approach to designing a scalable chat app with real-time updates?
99. A remote database connection is timing out. What layers do you check?
100. Design a high-availability DNS system. How would you ensure failover?

```
