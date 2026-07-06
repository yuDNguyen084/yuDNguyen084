# Hi there 👋, I'm Duy Nguyen (Nguyễn Anh Duy)

### Backend Engineer | System Architecture Enthusiast | Cloud-Native 

I am a fourth-year Computer Science student at **International University (VNU-HCM)**, deeply passionate about building scalable, high-concurrency distributed systems. I thrive on solving complex architectural bottlenecks, optimizing database queries, and managing server memory effectively. 

Currently, I'm researching my graduation thesis focusing on cloud-based backend design and AI-assisted system architecture, while actively seeking a **Backend / Infrastructure Software Engineering Internship**.

---

### Tech Stack & Tools
**Languages:**  
![Go](https://img.shields.io/badge/go-%2300ADD8.svg?style=for-the-badge&logo=go&logoColor=white) 
![NestJS](https://img.shields.io/badge/nestjs-E0234E?style=for-the-badge&logo=nestjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white) 

**Backend & Protocols:**  
![Express.js](https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB)
![gRPC](https://img.shields.io/badge/gRPC-244c5a?style=for-the-badge&logo=grpc&logoColor=white)
![WebSockets](https://img.shields.io/badge/WebSockets-010101?style=for-the-badge&logo=socket.io&logoColor=white)

**Databases & Caching:**  
![Postgres](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white) 
![Redis](https://img.shields.io/badge/redis-%23DD0031.svg?style=for-the-badge&logo=redis&logoColor=white) 
![SQLite](https://img.shields.io/badge/sqlite-%2307405e.svg?style=for-the-badge&logo=sqlite&logoColor=white) 
![Prisma](https://img.shields.io/badge/Prisma-3982CE?style=for-the-badge&logo=Prisma&logoColor=white)

**Infrastructure & DevOps:**  
![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white) 
![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white) 
![GitHub Actions](https://img.shields.io/badge/github%20actions-%232671E5.svg?style=for-the-badge&logo=githubactions&logoColor=white)
---

### Featured Projects

#### 🍿 [VOD-CloudStream Platform](https://github.com/yuDNguyen084/VOD)
*A decentralized media processing pipeline designed for extreme load and memory safety.*
*   **Performance:** Validated via k6 stress testing by processing **~300,000 requests** with **0.00% error rate**, sustaining up to **~900 req/sec** under extreme load (800 VUs) while maintaining `<98ms p95 latency` at stable loads.
*   **Concurrency:** Engineered a bounded Go worker pool (channels/goroutines) to strictly throttle FFmpeg operations, successfully queuing **1,160+ jobs/min** while securely capping server memory at `~4GiB` to prevent OOM crashes.
*   **Cloud Architecture:** Implemented direct-to-cloud AWS S3 Presigned URLs and configured S3 Gateway Endpoints within a custom VPC to isolate data transfer.

#### 📖 [MangaHub - Multi-Protocol Platform](https://github.com/yuDNguyen084/MangaHub)
*A high-speed, unified backend serving multiple network protocols from a single binary.*
*   **Architecture:** Integrated **5 network protocols** into a unified 14,600-line Go backend, benchmarked at **100% uptime** with **gRPC delivering 1.8× lower latency** than REST.
*   **Optimization:** Replaced external message brokers by designing a thread-safe in-memory Event Bus, sustaining **345,000+ events/sec throughput** at **3 µs delivery latency**.
*   **Security & Data:** Secured system integrity via 100%-coverage 3-tier rate limiting and eliminated O(N) full-table scans via targeted SQL indexes, reducing single-record lookups to `~500µs`.

---


### Let's Connect!

I'm always open to discussing system design, backend optimization, or new career opportunities.
*   **Email:** nguyenanhd607@gmail.com
