System design questions vary depending on the company and the role you're applying for. Here are some **company-specific** system design questions that are commonly asked:  

---

## **1. FAANG Companies (Facebook, Amazon, Apple, Netflix, Google)**  

### **Facebook (Meta)**
- **Design Facebook News Feed** (How do you handle personalized feeds at scale?)
- **Design a Messenger (WhatsApp/FB Messenger)** (Handling real-time messaging, scalability)
- **Design a URL Shortener (like bit.ly)** (Redirects, database sharding, expiration policy)
- **Design a Live Video Streaming Service** (Handling high concurrency, distributed systems)
- **Design Facebook Events System** (Handling invites, notifications, and recommendations)

### **Amazon**
- **Design Amazon Order Management System** (How to handle orders, payments, inventory?)
- **Design an E-commerce Search Engine** (Ranking, indexing, personalized search)
- **Design a Distributed Caching System** (Handling high read throughput)
- **Design a Scalable Notification System** (Push notifications, email, SMS)
- **Design a Multi-Region Data Storage System** (How to maintain consistency across regions?)

### **Apple**
- **Design an iCloud File Storage System** (Handling file uploads, synchronization)
- **Design Apple Maps Backend** (Efficient route computation, real-time updates)
- **Design a Secure Payment System (Apple Pay)** (How to handle transactions securely?)
- **Design an App Store Recommendation System** (How to recommend apps to users?)
- **Design Apple Health Data Storage** (Handling sensitive medical data securely)

### **Netflix**
- **Design a Video Streaming Service (like Netflix/YouTube)** (How to store and stream videos efficiently?)
- **Design a Recommendation System for Movies** (Collaborative filtering, ranking)
- **Design a Content Delivery Network (CDN)** (Reduce latency, caching strategies)
- **Design a Global Subscription Management System** (How to handle payments in multiple currencies?)
- **Design a System for Handling Millions of Concurrent Users** (Load balancing, caching)

### **Google**
- **Design Google Drive (Cloud Storage Service)** (Handling file storage, sharing, versioning)
- **Design a Web Crawler (like Googlebot)** (Efficient crawling, indexing, freshness)
- **Design Google Maps Traffic System** (How to handle real-time traffic updates?)
- **Design a Distributed Logging System** (Handling billions of logs per second)
- **Design Google Search Autocomplete** (Predictive search suggestions at scale)

---

## **2. Startups & Other Tech Companies**

### **Uber/Lyft**
- **Design a Ride-Sharing Service (like Uber/Lyft)** (Matching riders with drivers, surge pricing)
- **Design a Real-Time Location Tracking System** (How to efficiently track millions of users?)
- **Design a Payment System for Uber** (Handling fraud detection, transactions)
- **Design a Surge Pricing Algorithm** (How to dynamically adjust prices based on demand?)
- **Design Uber Eats Backend** (Handling food delivery, restaurant availability, payments)

### **Airbnb**
- **Design an Online Booking System** (Handling search, payments, availability)
- **Design a Pricing Recommendation System for Hosts** (How to suggest optimal pricing?)
- **Design an Image Search System for Listings** (How to categorize and rank images?)
- **Design a Review and Rating System** (How to prevent spam and fake reviews?)
- **Design a System for Handling Peak Traffic During Holidays** (Load balancing strategies)

### **Twitter**
- **Design Twitter Feed** (Handling real-time updates, ranking tweets)
- **Design a Hashtag Trending System** (How to detect trending topics globally?)
- **Design a URL Shortener for Twitter** (Efficiently storing short URLs)
- **Design a Rate Limiting System for API Requests** (How to prevent abuse?)
- **Design a Distributed System for Handling Billions of Tweets** (Storage, indexing, retrieval)

### **LinkedIn**
- **Design LinkedIn's People You May Know System** (Graph-based recommendations)
- **Design a Resume Parsing System** (How to extract structured data from resumes?)
- **Design LinkedIn Job Search Engine** (Ranking jobs based on relevance)
- **Design a Messaging System for LinkedIn** (Handling millions of messages per second)
- **Design LinkedIn's Activity Feed** (How to efficiently display updates from connections?)

### **Dropbox**
- **Design Dropbox File Sync System** (How to handle real-time file updates?)
- **Design a Scalable Notification System for File Changes** (Detecting updates efficiently)
- **Design a Version Control System for Files** (How to track changes and rollbacks?)
- **Design a Secure File Sharing System** (Handling access control and permissions)
- **Design a Distributed File Storage System** (Handling replication, consistency)

---

## **3. Fintech & Banking Companies**
### **Stripe/PayPal**
- **Design a Payment Processing System** (Handling transactions, fraud detection)
- **Design a Subscription Billing System** (Recurring payments, invoicing)
- **Design a Multi-Currency Wallet System** (Handling currency conversions)
- **Design a Fraud Detection System for Payments** (Anomaly detection, risk assessment)
- **Design a Secure API for Handling Card Payments** (Tokenization, PCI compliance)

### **Goldman Sachs/JPMorgan**
- **Design a Stock Trading Platform** (Real-time stock price updates, transactions)
- **Design a Risk Analysis System for Banks** (Handling financial risk calculations)
- **Design a Large-Scale Data Processing System for Finance** (Handling billions of transactions)
- **Design a Loan Management System** (How to process loan applications efficiently?)
- **Design an Algorithmic Trading System** (Low-latency trade execution)

---

## **4. Cloud & Infrastructure Companies**
### **Microsoft Azure/AWS/Google Cloud**
- **Design a Multi-Tenant Cloud Storage System** (Handling multiple clients securely)
- **Design a Load Balancer for a Cloud Platform** (Efficient traffic distribution)
- **Design a Multi-Region Data Replication System** (Handling consistency, latency)
- **Design a Monitoring System for Cloud Services** (Detecting failures, logging)
- **Design a Cloud Billing System** (Usage tracking, cost estimation)

---

## **5. Gaming Companies**
### **EA/Activision/Unity**
- **Design a Real-Time Multiplayer Gaming Server** (Handling latency, matchmaking)
- **Design a Game Leaderboard System** (Efficiently ranking players globally)
- **Design an In-Game Purchase System** (Handling virtual currency transactions)
- **Design a Cheat Detection System for Online Games** (How to detect suspicious behavior?)
- **Design a Live Game Streaming System** (Handling high concurrency for viewers)

---

### **How to Approach System Design Interviews?**
1. **Clarify Requirements**  
   - Functional (What should the system do?)  
   - Non-functional (Scalability, latency, reliability)  

2. **Define High-Level Architecture**  
   - Microservices, monolithic, event-driven, etc.  

3. **Identify Key Components**  
   - API Gateway, databases, caching, messaging queues  

4. **Discuss Scaling Strategies**  
   - Load balancing, sharding, replication  

5. **Handle Failure Scenarios**  
   - Disaster recovery, failover mechanisms  

6. **Optimize for Performance**  
   - Caching (Redis, Memcached), indexing  

---

These system design questions will help you **prepare for interviews** at different companies based on their domain! Let me know if you need **detailed answers** for any of them. 🚀
