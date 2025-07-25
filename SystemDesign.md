## Top 100 System Design Interview Questions

### Basics & Core Concepts

1. What is system design?
2. What is scalability?
3. What is high availability?
4. What is load balancing?
5. What is the difference between horizontal and vertical scaling?
6. What is latency vs throughput?
7. What is caching? Where is it used?
8. What is a CDN?
9. What is a reverse proxy?
10. What is a message queue?
11. What is a database index?
12. What is sharding?
13. What is replication in databases?
14. What is eventual consistency?
15. What is the CAP theorem?
16. What are strong and weak consistency models?
17. What is a distributed system?
18. What is a microservice architecture?
19. What is a monolithic architecture?
20. What are ACID properties?

### High-Level Design

21. How would you design a URL shortener like Bitly?
22. How would you design a web crawler like Google?
23. How would you design a news feed system?
24. How would you design an online code editor like Google Docs?
25. How would you design a ride-sharing system like Uber?
26. How would you design a scalable chat application?
27. How would you design a rate limiter?
28. How would you design a notification system?
29. How would you design a video streaming platform?
30. How would you design a file storage system like Google Drive?

### Databases

31. SQL vs NoSQL – when to use what?
32. How do you choose the right database for a system?
33. How do you scale a relational database?
34. What are the trade-offs of using NoSQL?
35. What is the difference between document and key-value stores?
36. How do you implement full-text search?
37. What is denormalization and when should you use it?
38. What are common database partitioning strategies?
39. How do you handle schema changes in production?
40. What is a write-ahead log?

### Caching

41. How does caching improve performance?
42. What is cache invalidation?
43. What is the difference between write-through and write-back cache?
44. Where would you implement caching in a web app?
45. How do you design a cache eviction policy?
46. What is a CDN and how does it help in caching?
47. What are some common tools for caching (e.g., Redis, Memcached)?
48. How do you avoid cache stampede?
49. What is a cache hit ratio?
50. How to keep cache in sync with the DB?

### Load Balancing & Failover

51. What is a load balancer?
52. How does DNS-based load balancing work?
53. What is sticky session and when is it used?
54. What are health checks in load balancers?
55. How do you implement graceful failover?
56. What are active-active and active-passive configurations?
57. How do you handle session management in distributed systems?
58. What are the pros and cons of stateless servers?
59. How do you do service discovery?
60. What is round-robin vs least connections?

### Messaging & Asynchronous Communication

61. What is a message queue?
62. What is the difference between push and pull-based queues?
63. What is publish-subscribe pattern?
64. How does Kafka work?
65. How do you design an email delivery system?
66. What is the difference between RabbitMQ and Kafka?
67. How do you ensure message reliability?
68. What is dead-letter queue?
69. What are idempotent operations?
70. How do you guarantee message ordering?

### Security & Reliability

71. How do you handle authentication and authorization?
72. What is OAuth and how does it work?
73. How do you store passwords securely?
74. What is rate limiting and how does it prevent abuse?
75. How do you implement data encryption in transit and at rest?
76. What is HTTPS and how does SSL/TLS work?
77. What is a JWT?
78. How do you design for GDPR compliance?
79. How do you implement audit logs?
80. How do you prevent DDoS attacks?

### Monitoring & DevOps

81. What is observability in system design?
82. How do you monitor a distributed system?
83. What is the difference between logs, metrics, and traces?
84. What are tools for monitoring (e.g., Prometheus, Grafana)?
85. How do you set up alerting and notifications?
86. What is a service-level agreement (SLA)?
87. What is a service-level objective (SLO)?
88. What is a service-level indicator (SLI)?
89. How do you handle zero-downtime deployments?
90. What is blue-green deployment?

### Scalability & Performance

91. How do you scale a system to millions of users?
92. How do you identify performance bottlenecks?
93. How do you handle hotkeys in distributed systems?
94. What is a CDN and how does it help with scalability?
95. How do you reduce database load in high-traffic systems?
96. What is connection pooling?
97. How do you rate-limit API usage?
98. What are circuit breakers and why are they useful?
99. What are retries with exponential backoff?
100. How do you handle data versioning in APIs?

## Top 100 Real-World System Design Questions

### Real Use Case & Architecture Planning

1. How would you design the architecture for a national-level vaccination booking system?
2. How would you design a payment gateway like Razorpay or Stripe?
3. How would you design a real-time bidding platform for ad tech?
4. How would you architect a system to detect and prevent credit card fraud in real time?
5. How would you handle millions of file uploads per day with high durability?
6. How do you design a global news delivery system with low latency?
7. How would you design an email delivery system for high volume (like Mailchimp)?
8. How would you ensure data synchronization across multiple data centers?
9. How would you design a tax filing system used by millions on deadline day?
10. How would you design a document collaboration system like Google Docs?

### Trade-offs & Bottlenecks

11. When should you use an eventual consistency model instead of strong consistency?
12. How do you deal with database write bottlenecks in high-write systems?
13. How do you balance read-heavy vs write-heavy workloads?
14. How do you choose between scaling vertically and horizontally?
15. How do you avoid single points of failure in distributed systems?
16. How would you resolve data consistency across microservices?
17. How do you choose between gRPC, REST, or GraphQL for internal APIs?
18. How do you avoid thundering herd problems?
19. When do you use SQL over NoSQL in modern architectures?
20. How do you handle hot partitioning issues in sharded systems?

### Systems at Scale

21. How do you design a video conferencing system (like Zoom)?
22. How would you architect a Netflix-like content delivery system?
23. How would you design a multi-region failover system?
24. How would you design a real-time ride allocation system like Uber?
25. How do you architect a calendar application with shared team scheduling?
26. How would you implement a scalable leaderboard (e.g., for gaming)?
27. How do you manage eventual consistency in distributed financial systems?
28. How do you build a secure identity verification system for a fintech product?
29. How would you design a multi-tenant SaaS architecture?
30. How do you handle concurrent transactions in high-volume e-commerce systems?

### Storage & Data Engineering

31. How would you design a data lake ingestion pipeline for IoT data?
32. How do you design a searchable image storage system?
33. How do you architect GDPR-compliant data retention and deletion?
34. How would you design a system to process terabytes of logs daily?
35. How would you build a scalable recommendation engine?
36. How do you deal with schema evolution in data pipelines?
37. How do you build an audit-compliant, tamper-evident logging system?
38. How do you design a version control system (like Git)?
39. How do you design a serverless ETL pipeline?
40. How do you manage data lineage and observability?

### Security & Privacy

41. How would you design secure password storage for millions of users?
42. How would you implement secure API access for third-party developers?
43. How do you protect user data in transit and at rest?
44. How would you design for SOC2 or ISO 27001 compliance?
45. How do you prevent replay attacks in an authentication system?
46. How do you implement secure data sharing between services?
47. How would you implement rate limiting to prevent abuse?
48. How would you monitor and respond to security breaches?
49. How do you build a system that supports user data anonymization?
50. How do you implement 2FA with backup recovery support?

### DevOps, Monitoring, and Observability

51. How would you design a logging system for distributed microservices?
52. How do you handle zero-downtime deployments for stateful services?
53. How do you create a CI/CD system with rollback support?
54. How would you build a system health dashboard for executives?
55. How would you implement distributed tracing across services?
56. How do you structure log collection and correlation at scale?
57. How do you alert on anomalies in system metrics?
58. How would you design a deployment platform like Heroku?
59. How would you implement a global feature flagging system?
60. How do you run canary and blue/green deployments?

### Reliability Engineering

61. How do you implement auto-healing for failing components?
62. How do you design a queue-based retry mechanism?
63. How would you build a rate limiter that works across distributed servers?
64. How would you simulate failure to test reliability (chaos engineering)?
65. How do you implement retry policies with exponential backoff?
66. How do you architect fault-tolerant systems?
67. How do you monitor system availability SLAs?
68. How would you design a global uptime monitoring system?
69. How would you build a fail-fast circuit breaker architecture?
70. How do you recover corrupted data at scale?

### Team Collaboration & API Design

71. How would you structure an internal API for a design system?
72. How do you document large-scale APIs and manage breaking changes?
73. How do you manage cross-team service boundaries in a microservice ecosystem?
74. How would you design a shared authentication service?
75. How do you handle dependency hell across services?
76. How would you build an internal developer portal?
77. How do you version APIs for backwards compatibility?
78. How would you enforce contract testing between services?
79. How do you allow clients to safely call APIs during downtime?
80. How do you implement service mesh for microservices?

### Performance & Optimization

81. How do you design a high-performance search engine?
82. How do you optimize mobile API responses?
83. How do you batch database writes without losing performance?
84. How do you reduce tail latency in large-scale services?
85. How would you cache user sessions securely?
86. How do you handle memory leaks in long-running services?
87. How would you implement pagination for a billion-row dataset?
88. How do you compress data for high-speed transfer?
89. How do you reduce startup time in containerized systems?
90. How do you identify performance bottlenecks across a stack?

### Edge Cases & Growth

91. What would you do if your system suddenly saw 10x traffic?
92. How would you scale user search suggestions globally?
93. How do you plan for exponential data growth?
94. How do you architect for low-bandwidth users?
95. How would you handle user data migration at scale?
96. How would you simulate real-world load in staging?
97. How do you monitor capacity planning for databases?
98. How would you redesign a legacy system without downtime?
99. How do you ensure backwards compatibility during re-architecture?
100. How do you know when to rewrite vs refactor a system?
