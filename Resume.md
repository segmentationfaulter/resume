# Muhammad Saqib

**Software Engineer**

+92 315 0776708 | muhammadsackib@gmail.com | GMT+5  
[github.com/segmentationfaulter](https://github.com/segmentationfaulter) | [linkedin.com/in/segfaulter](https://linkedin.com/in/segfaulter)

---

## Summary

**Full-Stack Software Engineer** with **6+ years** of experience building and scaling production web applications, including shipping and operating a complete platform independently from concept to production. Specializes in modern **frontend technologies (React, Next.js, TanStack Start, Elm, Angular)** with substantial **backend expertise in Node.js and Golang**. Delivered microservices, RESTful APIs, and containerized solutions while collaborating effectively across distributed remote engineering teams. Passionate about clean code, functional programming principles, and evolving into **system architecture** roles with expertise in high-concurrency systems and distributed architectures.

---

## Skills

- **Languages:** JavaScript, TypeScript, Golang, SQL, Elm, HTML, CSS
- **Backend:** Node.js, Express.js, tRPC, RESTful APIs, Drizzle ORM, Zod, Better Auth (Multi-tenancy), JWT Authentication, Inngest (Background Jobs), Redis, BullMQ, Cloudflare (Workers, D1, R2, Images)
- **Databases:** PostgreSQL (ACID compliance, row-level locking, transaction management), SQLite
- **Developer Tools & DevOps:** Docker, Docker Compose, Git, Turborepo, CI/CD (GitHub Actions), Vercel, Playwright, Vitest
- **Frontend:** React (Next.js App Router, TanStack Start), TypeScript, TanStack Query, TanStack Router, Tailwind CSS, shadcn/ui, Angular, Redux

---

## Experience

**Independent Software Engineer** | Self-Employed (Remote) | Jul 2024 - Present

- Built and launched **Rishta Center** (rishta.center), a production matchmaking platform serving the Pakistani community — sole engineer handling all phases from spec/PRD and UI/UX through full-stack development to deployment
- Architected zero-cost infrastructure on **Cloudflare** (Workers, D1, R2, Images) with trunk-based CI/CD, automated **Drizzle ORM** migrations, isolated prod/staging/preview environments, and **PageSpeed Insights** scores of ~90 performance / 100 across all other metrics
- Designed "Give-to-Get" community model with rate-limited contact reveals (5/day), anti-scraping protections, and audit logging to prevent commercial data harvesting
- Built 100% **Urdu RTL** interface with mobile-first responsive design, dual-script input (Urdu/Roman Urdu), and accessibility optimized for older users
- Engineered 1:N multi-profile schema (up to 3 profiles/user) with gender-aware photo logic, **Cloudflare Images** face-cropping, and admin-only CSV bulk-upload for canonical data seeding
- Built multiple portfolio projects (CollabSpace, Tickets Hive, Bookmarks Manager API) demonstrating event-driven architectures with **Inngest**, high-concurrency systems with **BullMQ/Redis**, multi-tenancy with **Better Auth**, and idiomatic **Golang** API design — detailed in Projects section

**Software Engineer - Frontend** | Paack (Remote) | Jul 2020 - Jun 2024

- Developed and maintained features for internal dashboards using Elm, collaborating with backend teams on API design and integration for microservices
- Evolved **[Paack-UI](https://github.com/PaackEng/paack-ui)**, an in-house design system built using Elm, improving developer productivity and ensuring consistent, high-quality user experiences across applications
- Championed functional programming principles for a more predictable, testable, and maintainable codebase

**Software Engineer - Frontend** | Motive (formerly KeepTruckin) (Lahore) | Jul 2019 - Jul 2020

- Developed and enhanced features for an internal dashboard using Angular and TypeScript to improve operational efficiency
- Served on the interviewing panel for frontend team new hires, conducting technical interviews and evaluating candidate competencies

**Software Engineer** | Arbisoft (Lahore) | Feb 2019 - Jun 2019

- Enhanced client's discussion board with performance improvements, new features, and maintenance on Node.js backend

**Frontend Engineer** | Wavetec (Lahore) | May 2018 - Jan 2019

- Led frontend development of queue management simulator using React, enabling clients to model and analyze queuing strategies

**Associate Product Engineer** | Qubit (Lahore) | Nov 2017 - Apr 2018

- Developed web portal in React for internal teams to preview recommendations from Qubit's personalization engine

---

## Projects

[**CollabSpace - Full-Stack Project Collaboration Platform**](https://github.com/segmentationfaulter/collab-space)

- Engineered a collaboration platform using **Next.js (App Router, RSC, Suspense)**, **TypeScript**, and **tRPC** for end-to-end type safety
- Implemented **multi-tenancy** (Workspaces) using **Better Auth Organizations**, enabling secure user roles and permissions management
- Developed **event-driven background jobs** for automated notifications and invitations using **Inngest**
- Designed a scalable relational schema with **PostgreSQL** and **Drizzle ORM**, ensuring high data integrity and performance

[**Tickets Hive - High-Concurrency Event Booking System**](https://github.com/segmentationfaulter/tickets_hive)

- Architected async queue-based system handling extreme concurrency scenarios with zero overbooking guarantee
- Reduced API response latency using BullMQ/Redis job queues and async processing for immediate user feedback
- Implemented **version-based optimistic locking** in PostgreSQL, enabling significantly higher throughput and eliminating database lock contention
- Built production-ready monorepo with Turborepo, Docker, OpenAPI documentation, and horizontal scaling architecture
- Designed comprehensive error handling, load testing suite, and graceful shutdown for production resilience

[**Bookmarks Manager API (Golang)**](https://github.com/segmentationfaulter/bookmarks-manager-api)

- Designed secure, performant RESTful API in Golang using standard library
- Implemented clean, layered microservice architecture for scalability and maintainability
- Used SQLite for data storage with efficient raw SQL queries for CRUD operations
- Secured endpoints with JWT authentication and bcrypt password hashing
