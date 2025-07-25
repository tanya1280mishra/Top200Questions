## 📘 Top 100 DBMS Interview Questions

### 🔹 1. DBMS Basics

1. What is a DBMS?
2. What is the difference between DBMS and RDBMS?
3. What are the advantages of DBMS?
4. Define primary key and foreign key.
5. What is a candidate key?
6. What is a super key?
7. What is a composite key?
8. What is the difference between primary key and unique key?
9. What is data abstraction?
10. Explain different levels of data abstraction.

---

### 🔹 2. SQL Queries

11. What is the difference between WHERE and HAVING?
12. What is the difference between INNER JOIN, LEFT JOIN, RIGHT JOIN, and FULL JOIN?
13. What is a subquery?
14. What is a correlated subquery?
15. What are aggregate functions in SQL?
16. What is the difference between COUNT(\*) and COUNT(column)?
17. How does GROUP BY work?
18. What is the difference between UNION and UNION ALL?
19. How do you retrieve duplicate rows in SQL?
20. How to delete duplicate rows?

---

### 🔹 3. Normalization & Schema Design

21. What is normalization?
22. What are anomalies in databases?
23. Explain 1NF, 2NF, 3NF, BCNF.
24. What is denormalization?
25. What is a functional dependency?
26. What is the difference between star schema and snowflake schema?
27. What is ER model?
28. What are generalization and specialization?
29. What is cardinality in ER diagrams?
30. What is the difference between strong and weak entity?

---

### 🔹 4. Indexing & Optimization

31. What is an index in DBMS?
32. What are clustered vs non-clustered indexes?
33. What is B+ Tree?
34. What is hashing in DBMS?
35. What is a covering index?
36. What is a bitmap index?
37. When not to use an index?
38. What is query optimization?
39. What are materialized views?
40. What is the cost of using indexes?

---

### 🔹 5. Transactions & Concurrency

41. What is a transaction?
42. Explain the ACID properties.
43. What is dirty read?
44. What is phantom read?
45. What is non-repeatable read?
46. What are isolation levels in SQL?
47. What is locking? Types?
48. What is optimistic vs pessimistic concurrency control?
49. What is deadlock? How to prevent it?
50. What is the two-phase locking protocol?

---

### 🔹 6. Recovery & Logging

51. What is log-based recovery?
52. What is write-ahead logging?
53. What are checkpoints?
54. What is shadow paging?
55. What is cascading rollback?
56. What is meant by atomicity?
57. How does DBMS handle failures?
58. What are deferred and immediate update methods?
59. What is ARIES?
60. How are logs stored and used?

---

### 🔹 7. NoSQL & Modern Databases

61. What is NoSQL?
62. Types of NoSQL databases?
63. What are key-value stores?
64. What is eventual consistency?
65. Compare MongoDB vs MySQL.
66. What is CAP theorem?
67. What is sharding?
68. What is a document store?
69. What is BASE in NoSQL?
70. What is the difference between vertical and horizontal scaling?

---

### 🔹 8. Stored Procedures, Views, and Triggers

71. What is a stored procedure?
72. What are triggers in SQL?
73. What is the difference between procedure and function?
74. What are views in SQL?
75. Can we update a view?
76. What is a materialized view?
77. What is a cursor?
78. What is the difference between a cursor and a trigger?
79. What are system-defined vs user-defined triggers?
80. What is a recursive query?

---

### 🔹 9. Advanced Topics

81. What is a distributed database?
82. What is data warehousing?
83. What is OLAP vs OLTP?
84. What are fact and dimension tables?
85. What is indexing in data warehouses?
86. What is replication?
87. What is partitioning?
88. What is data lake vs data warehouse?
89. What is temporal data?
90. What is ACID vs BASE?

---

### 🔹 10. Miscellaneous

91. What is NULL in SQL?
92. Difference between DELETE, TRUNCATE, and DROP?
93. What are constraints in SQL?
94. What is referential integrity?
95. What is schema vs instance?
96. What are surrogate keys?
97. What is SQL injection?
98. What is a data dictionary?
99. What is an ORDBMS?
100. What is the role of a database administrator (DBA)?

---

Shall I now send the **Computer Networks** 100 questions next?


# 📘 100 Real-World Interview Questions for DBMS (Database Management Systems)
```markdown
# 100 Real-World Interview Questions for DBMS

## 🔹 Section 1: Schema Design & Data Modeling
1. You're building a hospital database. How would you model patient history and ensure efficient querying?
2. A social media app needs to track user followers. Would you use a normalized or denormalized schema?
3. How would you design a schema for an online bookstore with thousands of concurrent buyers?
4. In a food delivery system, how would you store order status transitions to enable analytics?
5. You need to model one-to-many and many-to-many relationships. Give real-world examples and implementations.
6. A ride-sharing app must store real-time driver locations. Would you use a relational model or NoSQL? Why?
7. How would you handle schema changes in a production database with millions of rows?
8. In a multi-tenant SaaS platform, how would you design tenant isolation in the DB schema?
9. How would you model versioning in a document editing application?
10. Design a database for an IoT sensor network logging millions of events per day.

## 🔹 Section 2: SQL & Query Optimization
11. You’re facing slow SQL queries on large join operations. How do you diagnose and fix them?
12. How would you optimize a query that involves `GROUP BY` and `ORDER BY` on millions of rows?
13. You’re asked to fetch the 2nd highest salary without using LIMIT/OFFSET. How?
14. A query is doing full table scans despite indexes. What do you check?
15. How do you write an efficient query to find users who haven’t logged in for 30 days?
16. How would you detect and eliminate redundant joins in complex reports?
17. How do you debug parameter sniffing in SQL Server?
18. What indexing strategies would you apply to improve slow search queries?
19. Write a query to identify customers who ordered the same item more than once in a week.
20. How would you paginate results for a large dataset efficiently?

## 🔹 Section 3: Indexing & Performance
21. A dashboard loads slowly due to a large analytics query. How do you speed it up using indexing?
22. How do composite indexes differ from single-column indexes in practice?
23. What are the trade-offs of using too many indexes on a table?
24. Your query is still slow even with indexing. What might be wrong?
25. How would you index a time-series database storing hourly temperature?
26. What are covering indexes and where would you apply them?
27. How would you detect and remove unused indexes in a large DB?
28. A write-heavy table becomes slow. Would you remove some indexes? Why?
29. What indexing strategy would you recommend for an e-commerce product search?
30. How do bitmap indexes help in filtering low-cardinality columns?

## 🔹 Section 4: Transactions & Isolation
31. Your banking app shows inconsistent balances. What isolation level would you use?
32. How would you handle concurrency in a ticket-booking system?
33. A long-running transaction is blocking other queries. How do you handle it?
34. Explain a deadlock you encountered and how you resolved it.
35. How does optimistic concurrency control help in mobile apps with offline writes?
36. For a food delivery system, how do you handle simultaneous updates to order status?
37. A transaction is taking a lock for too long. How do you detect and mitigate it?
38. How would you log failed transactions for retry without breaking consistency?
39. What isolation level would you use in a read-heavy analytics dashboard?
40. How do you prevent dirty reads in an inventory system?

## 🔹 Section 5: Backup, Recovery & Replication
41. How would you implement automated database backups for a high-traffic e-commerce site?
42. A production table was accidentally dropped. How do you restore it?
43. What backup strategy would you use for a large real-time system with 24/7 uptime?
44. How would you verify integrity of backups before relying on them?
45. You have a master-slave replication lag. What would you check?
46. How do you minimize downtime during schema migrations?
47. How would you configure point-in-time recovery?
48. How do you ensure that backups are stored securely and compliantly?
49. How would you migrate data from on-premise to cloud DB with minimal downtime?
50. What strategies would you use for failover during a DB outage?

## 🔹 Section 6: NoSQL & Modern Databases
51. You need to store real-time chat messages. Would you choose MongoDB or PostgreSQL?
52. Your app stores millions of product reviews with variable formats. Which DB fits best?
53. How does eventual consistency impact real-time applications?
54. How would you design a leaderboard using Redis?
55. What are the pros/cons of using DynamoDB for a user authentication system?
56. How would you implement horizontal scaling in a document store?
57. Compare Cassandra vs MongoDB for logging user interactions.
58. What is your strategy to handle schema evolution in a NoSQL DB?
59. When would you avoid using NoSQL in favor of RDBMS?
60. How do you deal with write conflicts in eventually consistent systems?

## 🔹 Section 7: Stored Procedures, Triggers, Views
61. You want to encapsulate business logic in the DB layer. How would you do it?
62. How do you prevent misuse or overuse of triggers in a transactional system?
63. What’s a scenario where a view could be used instead of a materialized view?
64. How would you optimize a slow stored procedure?
65. What are the risks of nesting stored procedures?
66. When would you prefer a DB-level constraint over an application-level check?
67. How would you implement audit logging using triggers?
68. How would you restrict updates on sensitive fields using DB-level rules?
69. Can a view be updated? Explain a use case where it makes sense.
70. How do stored procedures affect code portability between DB vendors?

## 🔹 Section 8: Security & Access Control
71. How would you restrict column-level access in a database?
72. Your app handles sensitive user data. How do you secure it in the DB?
73. Explain a real-world SQL injection attack and how to prevent it.
74. What is the principle of least privilege and how do you apply it in SQL roles?
75. How do you implement row-level security in PostgreSQL or SQL Server?
76. A client wants field-level encryption. How would you implement this?
77. How do you secure database credentials in production applications?
78. How would you log and alert unauthorized data access?
79. What are audit trails, and when are they required by compliance?
80. How do you design a secure multi-tenant schema in a shared DB?

## 🔹 Section 9: Data Warehousing & Analytics
81. You’re building a reporting dashboard. How would you model your data warehouse?
82. Compare OLTP vs OLAP in real-world use.
83. What partitioning strategy would you use in a fact table with billions of rows?
84. How would you aggregate daily sales across multiple regions efficiently?
85. What ETL strategy would you use for transforming unstructured logs into a warehouse?
86. What’s the role of star schema vs snowflake in performance?
87. You have slow roll-up queries. Would materialized views help? How?
88. How would you monitor ETL failures in production pipelines?
89. You need to deduplicate and normalize logs across systems. How would you do it?
90. What DBMS features help implement time-travel or historical views?

## 🔹 Section 10: Miscellaneous & System Design
91. How would you design a database for a URL shortener?
92. Design a database schema for YouTube-style video sharing.
93. What’s your approach to handling billions of log records per day?
94. How do you handle schema migrations with zero downtime?
95. You need to archive old transactional data. What’s your strategy?
96. How would you store user preferences for a mobile app?
97. Explain your strategy for multi-region database availability.
98. A high-traffic API causes DB spikes. How would you buffer or batch writes?
99. How would you refactor a monolithic DB schema into microservices?
100. How do you decide between SQL and NoSQL when designing a new application?

