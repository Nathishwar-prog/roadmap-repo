# 🏗️ System Design Roadmap

> **Goal:** Learn to design large-scale, reliable, and performant systems like the ones powering Netflix, Uber, and Twitter.

---

## 📌 Overview

| Stage | Topics | Estimated Time |
|---|---|---|
| 🟡 Intermediate | Core Concepts, Databases, Caching | 6–8 weeks |
| 🔴 Advanced | Distributed Systems, Microservices, Real-world Designs | 8–12 weeks |

> ⚠️ **Prerequisites:** Comfortable with at least one programming language and basic web development or backend concepts.

---

## 🟡 Stage 1 — Core Concepts

**Goal:** Understand the building blocks of large-scale systems.

### 🌐 Networking & Web Fundamentals
- ✅ How the internet works: DNS, TCP/IP, HTTP/HTTPS
- ✅ Client-server architecture
- ✅ REST vs GraphQL vs gRPC
- ✅ WebSockets and long polling
- ✅ CDN (Content Delivery Networks)

### 📦 System Components
- ✅ Load balancers: round-robin, weighted, least connections
- ✅ Horizontal vs vertical scaling
- ✅ Reverse proxies (Nginx, HAProxy)
- ✅ Message queues: RabbitMQ, Kafka basics
- ✅ API Gateway patterns

### 🗄️ Databases
- ✅ SQL vs NoSQL — when to use which
- ✅ Database indexing and query optimization
- ✅ ACID vs BASE properties
- ✅ Database replication (master-slave, multi-master)
- ✅ Database sharding strategies
- ✅ Choosing the right DB: PostgreSQL, MongoDB, Cassandra, Redis

### ⚡ Caching
- ✅ What is caching and why it matters
- ✅ Cache strategies: cache-aside, write-through, write-back
- ✅ Redis and Memcached
- ✅ Cache invalidation challenges
- ✅ CDN as a caching layer

---

## 🔴 Stage 2 — Advanced System Design

**Goal:** Design real-world systems end-to-end with trade-off reasoning.

### 🔄 Distributed Systems
- ✅ CAP theorem (Consistency, Availability, Partition tolerance)
- ✅ Consistency models: eventual vs strong consistency
- ✅ Distributed transactions: two-phase commit, SAGA pattern
- ✅ Consensus algorithms: Raft, Paxos (conceptual)
- ✅ Distributed caching and data partitioning

### 🏢 Microservices Architecture
- ✅ Monolith vs microservices trade-offs
- ✅ Service communication: synchronous (REST/gRPC) vs async (events)
- ✅ Service discovery and registration
- ✅ Circuit breakers and fault tolerance
- ✅ Containerization: Docker, Kubernetes basics
- ✅ API versioning strategies

### 🔒 Security & Reliability
- ✅ Authentication: OAuth 2.0, JWT, SSO
- ✅ Rate limiting and throttling
- ✅ Idempotency in distributed systems
- ✅ Disaster recovery and backup strategies
- ✅ Observability: logging, metrics, tracing (ELK, Prometheus, Grafana)

### 🎓 Classic System Design Problems
Practice designing these well-known systems:
- 🔗 URL Shortener (like bit.ly)
- 💬 Chat Application (like WhatsApp)
- 📸 Photo Sharing (like Instagram)
- 🎥 Video Streaming (like YouTube/Netflix)
- 🚗 Ride Sharing (like Uber)
- 🔍 Search Engine (like Google Search)
- 📰 News Feed (like Twitter/Facebook)
- 📦 Distributed File Storage (like Google Drive)

---

## ⏱️ Estimated Time

| Stage | Duration |
|---|---|
| Core Concepts | 6–8 weeks (1–2 hrs/day) |
| Advanced Design | 8–12 weeks (2 hrs/day) |
| **Total** | **~4–6 months** |

---

## 📚 Resources

### Free Resources:
- 🔗 [System Design Primer (GitHub)](https://github.com/donnemartin/system-design-primer) — 270k+ stars, comprehensive guide
- 🔗 [ByteByteGo Newsletter](https://blog.bytebytego.com/) — Visual system design explanations
- 🔗 [High Scalability Blog](http://highscalability.com/) — Real-world architecture teardowns

### Books:
- 📖 *Designing Data-Intensive Applications* — Martin Kleppmann ⭐ (must-read)
- 📖 *System Design Interview* — Alex Xu (Volumes 1 & 2)
- 📖 *Clean Architecture* — Robert C. Martin
- 📖 *The Phoenix Project* — Gene Kim (DevOps culture)

### YouTube Channels:
- 🎥 [Gaurav Sen](https://www.youtube.com/@gkcs) — System design explanations
- 🎥 [ByteByteGo](https://www.youtube.com/@ByteByteGo) — Visual tech breakdowns
- 🎥 [Tech Dummies Narendra L](https://www.youtube.com/@TechDummiesNarendraL) — Deep dives

### Practice:
- 🏋️ [Pramp](https://www.pramp.com/) — Mock system design interviews
- 🏋️ [Exponent](https://www.tryexponent.com/) — Interview preparation platform

---

## 🔮 What's Next?

- 🤖 Apply system design to AI: [AI/ML Roadmap](../ai-ml/README.md)
- 🌐 Build scalable web apps: [Web Development Roadmap](../web-development/README.md)

---

[⬅️ Back to Main README](../../README.md)
