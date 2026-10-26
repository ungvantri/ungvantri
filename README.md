<h1 align="center">Hi, I'm Ung Văn Trí 👋</h1>

<h3 align="center">Java Backend Intern | Software Engineering student @ HCMUTE</h3>

<p align="center">
  <img src="https://img.shields.io/badge/Java-21-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" />
  <img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white" />
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" />
  <img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
</p>

<p align="center">
  📍 Ho Chi Minh City, Vietnam &nbsp;|&nbsp;
  📧 <a href="mailto:ungvantri91@gmail.com">ungvantri91@gmail.com</a> &nbsp;|&nbsp;
</p>

---

## 👨‍💻 About Me

- 🎓 Software Engineering student at Ho Chi Minh City University of Technology and Education (HCMUTE)
- ☕ Focused on **Java & Spring Boot** backend development
- 🔧 Hands-on with RESTful APIs, concurrency control, stateless authentication, Redis caching, payment integration, and automated testing
- 🌱 Deepening my **system design** fundamentals
- 💡 Interested in building reliable, scalable backend systems

---

## 🛠️ Tech Stack

| Category | Technologies |
|---|---|
| **Languages** | ![Java](https://img.shields.io/badge/Java_21-ED8B00?logo=openjdk&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white) ![SQL](https://img.shields.io/badge/SQL-4479A1?logo=mysql&logoColor=white) |
| **Backend** | ![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?logo=springboot&logoColor=white) ![Spring Security](https://img.shields.io/badge/Spring_Security-6DB33F?logo=springsecurity&logoColor=white) ![Hibernate](https://img.shields.io/badge/Hibernate-59666C?logo=hibernate&logoColor=white) ![JWT](https://img.shields.io/badge/JWT-000000?logo=jsonwebtokens&logoColor=white) |
| **Database & Caching** | ![MySQL](https://img.shields.io/badge/MySQL_8-4479A1?logo=mysql&logoColor=white) ![Redis](https://img.shields.io/badge/Redis_7-DC382D?logo=redis&logoColor=white)|
| **Testing** | ![JUnit5](https://img.shields.io/badge/JUnit_5-25A162?logo=junit5&logoColor=white)|
| **DevOps & Tools** | ![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?logo=githubactions&logoColor=white) ![AWS](https://img.shields.io/badge/AWS_EC2-FF9900?logo=amazonaws&logoColor=white) ![Git](https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white) ![Postman](https://img.shields.io/badge/Postman-FF6C37?logo=postman&logoColor=white) |
| **Frontend** | ![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white) ![React](https://img.shields.io/badge/React-61DAFB?logo=react&logoColor=black) |

---

## 🚀 Featured Projects

### 🎬 [CineBook — Cinema Ticket Booking System](https://github.com/ungvantri/booking-film)
*Aug 2026 – Oct 2026 · Backend Developer*

`Java 21` `Spring Boot 4` `MySQL 8` `Redis 7` `Docker`

- Designed a booking backend with **11 REST controllers** and **12 JPA entities**, using layered architecture, MapStruct DTO mapping, and Jakarta Bean Validation.
- **Prevented double-booking** with Redis `SETNX` seat locks (15-minute TTL), all-or-nothing lock acquisition, and rollback when any requested seat was already held; used Redis key-expiry events to expire unpaid bookings and release promotion usage.
- Implemented **stateless JWT authentication** and **RBAC** (ADMIN / STAFF / CUSTOMER) with Spring Security, OAuth2 Resource Server, BCrypt, and access/refresh tokens.
- Integrated **VNPay** with HMAC-SHA512 signature verification, callbacks, and refunds; added state validation to prevent duplicate payment, cancellation, and refund processing.
- Added **Bucket4j rate limiting** (15 req/min for auth, 60 for general endpoints) with HTTP 429 + `Retry-After`, and Redis caching via `@Cacheable` / `@CacheEvict`.
- Implemented async booking emails with `@Async` and Resilience4j retries, real-time seat updates via WebSocket/STOMP, and Cloudinary poster uploads.
- Wrote **60+ unit/integration tests** (JUnit 5, Mockito, Testcontainers with MySQL); containerized with a multi-stage Dockerfile + Docker Compose health checks; automated build/test/deploy with **GitHub Actions**.

---

### 🍔 [Crave — Online Food Ordering Platform](https://github.com/nguyenvinhz/Servlet_Project_Crave)
*Oct 2026 · Backend Developer · Team of 3*

`Java 17` `Jakarta Servlet/JSP` `Hibernate` `MySQL 8.4` `payOS`

- Implemented a customizable cart with server-side option validation, duplicate-line merging, and **pessimistic locking** to keep quantities and totals consistent.
- Built **voucher validation** at cart, checkout, and order creation, rechecking status, validity window, minimum order value, and maximum discount on the server.
- Implemented delivery checkout using the **Haversine formula** within a 10 km service radius, tiered delivery fees, and a free-shipping threshold; integrated Leaflet maps and address search.
- Contributed to **transactional order creation** with cart locking, server-side price recalculation, order/price snapshots, payment records, and status history in one transaction.
- Collaborated via GitHub pull requests, JUnit 5/Mockito and MySQL integration tests, and a CI/CD pipeline deploying to **AWS EC2**.

---

## 🏆 Honors & Awards

- 🥉 **Bronze Medal** — National Student Mathematics Olympiad, Vietnam (2025)
- 🎓 **Academic Encouragement Scholarship** — Semester 1, Academic Year 2024–2025, HCMUTE

---

## 📫 Let's Connect

<p align="center">
  <a href="mailto:ungvantri91@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
  <a href="https://github.com/ungvantri"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" /></a>
</p>

<p align="center"><i>Thanks for stopping by! If you're hiring a Java Backend, I'd love to hear from you. ⭐</i></p>
