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
