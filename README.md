# Hi, I'm Aman Prasad 👋
**Java Backend Engineer | Spring Boot • REST APIs • Messaging & Integrations**

Backend Software Engineer with nearly 2 years of professional experience building and modernizing payment services and enterprise integrations. Hands-on experience across Java (8, 17, 21), Spring Boot, REST APIs, asynchronous messaging (Amazon SQS, RabbitMQ), service resilience (Resilience4j), and database engineering (PostgreSQL, MySQL, Liquibase).

Currently developing **BookIt Platform**, a cinema ticket-booking engine focused on database-level schedule integrity, concurrency control, and automated testing.

---

### 🛠 Technical Skills

- **Languages & Frameworks:** Java (8/17/21), SQL, Spring Boot 2/3, Spring MVC, Spring Data JPA, Microservices, REST APIs
- **Databases & Tools:** PostgreSQL 16, MySQL, Redis, Liquibase, Flyway
- **Messaging & Resilience:** Amazon SQS, RabbitMQ, Apache Camel, Resilience4j, Webhooks, OAuth 2.0
- **Testing:** JUnit 5, Mockito, WireMock, Testcontainers, Unit & Integration Testing
- **Tools & DevOps:** Docker, Docker Compose, Git, Bitbucket, Maven, Jenkins, ArgoCD, CI/CD, Grafana, Postman
- **Fundamentals:** Data Structures & Algorithms, Object-Oriented Programming (OOP), Low-Level Design (LLD)

---

### 🚀 Featured Project

#### [BookIt Platform | High-Concurrency Cinema Ticket Booking Engine](https://github.com/AmanPrasadDev/bookit-platform)
*A cinema ticket-booking engine designed from first principles to explore database-level constraint enforcement, seat contention management, and integration test rigor.*
- **Temporal Schedule Integrity:** Enforced at the database storage engine layer via **PostgreSQL GiST range exclusion constraints (`btree_gist`)**, rejecting overlapping shows on the same cinema screen.
- **Concurrency & Deadlock Mitigation:** Designed an all-or-nothing seat hold mechanism with **ordered row-level locking (`SELECT ... FOR UPDATE` in sorted seat ID order)** to reduce deadlock risk during concurrent seat reservation spikes *(in progress)*.
- **Security & RBAC:** Implemented Google OIDC integration, cryptographic JWT minting/validation (HMAC-SHA256), and granular Role-Based Access Control.
- **Automated Verification:** Verified by **100+ passing automated unit and integration tests** (117 distinct `@Test` methods across 15 test classes), using **Testcontainers with PostgreSQL 16** for database-backed integration testing.
- **Stack:** Java 21, Spring Boot 3, PostgreSQL 16, Flyway, Testcontainers, Docker Compose.

---

### 🏆 Key Highlights
- **Competitive Problem Solving:** Solved **450+ Data Structures & Algorithms** problems across LeetCode and competitive programming platforms.
- **Contest Achievement:** Secured **1st Rank** among 100+ participants in a Scaler Academy Data Structures & Algorithms competition.
- **Enterprise Integrations:** Developed and maintained 20+ third-party connectors (CRM, HRMS, Payroll, Scheduling) across live environments at Repute Network.

---

### 📬 Connect With Me
- **LinkedIn:** [linkedin.com/in/aman-prasad](https://www.linkedin.com/in/aman-prasad-42a88a26b/)
- **LeetCode:** [leetcode.com/u/BigAman](https://leetcode.com/u/BigAman/)
- **Scaler:** [scaler.com/academy/profile](https://www.scaler.com/academy/profile/e95d61e1eb48)
- **Email:** [me.aman.pr@gmail.com](mailto:me.aman.pr@gmail.com)
