<div align="center">

# Mohit Kumar
**Full-Stack Engineer · RGIPT '27**

Building systems that scale — from voice-first AI pipelines to multi-tenant SaaS platforms.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mohit-kumar-42b159289/)
[![LeetCode](https://img.shields.io/badge/LeetCode-FFA116?style=flat&logo=leetcode&logoColor=white)](https://leetcode.com/u/MohitKumar2512/)
[![Medium](https://img.shields.io/badge/Medium-12100E?style=flat&logo=medium&logoColor=white)](https://medium.com/@mohitrkumar2512)
[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=flat&logo=vercel&logoColor=white)](https://wizardofolio-v1.matrix-9560.workers.dev/)

</div>

---

## About

I'm a 4th-year IT student at RGIPT who builds and ships full-stack products. I care about the details that actually matter in production: query performance, caching strategy, auth flows that don't break, and APIs that are consistent under load.

Currently focused on backend engineering, distributed systems fundamentals, and competitive programming.

---

## Projects

### TrueTone — Voice-First AI Feedback System
> React · TypeScript · Node.js · Express · PostgreSQL · Groq/Openrouter APIs

A full-stack platform that processes audio sessions end-to-end: transcription → LLM analysis → sentiment + topic extraction → summarization.

**What I built and why it was non-trivial:**
- Handles 100+ daily audio sessions with automated transcription pipeline; had to think carefully about async processing to avoid blocking the request cycle
- PostgreSQL indexing strategy reduced query latency by 35% under real query load
- Ran sentiment analysis + summarization across 500+ records via Openrouter/Groq — had to manage rate limits, retries, and cost-aware batching
- JWT auth + role-based access control with clean separation between user roles

[Live Demo](#) · [GitHub](#)

---

### NAMS — News Agency Management System
> React · TypeScript · Node.js · Express · PostgreSQL · Prisma · Redis · BullMQ

A multi-tenant SaaS platform where each newspaper agency gets isolated data, billing, and customer management — fully production-deployed.

**What made this architecturally interesting:**
- Multi-tenancy at the data layer: had to design schema with proper tenant isolation without sacrificing query performance
- Redis caching + BullMQ background workers to handle subscription billing jobs async, decoupled from the request path
- CDN setup (AWS CloudFront + Cloudinary) brought asset load times down 40% — measured before/after with Lighthouse
- Deployed across Vercel (frontend) + AWS EC2 (backend); set up proper env management and zero-downtime deploys

[Live Demo](#) · [GitHub](#)

---

## Technical Stack

**Languages:** C++ · TypeScript · JavaScript · Python · SQL

**Backend:** Node.js · Express.js · REST APIs · PostgreSQL · MongoDB · Prisma · Redis · BullMQ

**Frontend:** React.js · Next.js · Tailwind CSS

**Infrastructure:** AWS (EC2, CloudFront) · Docker · Vercel · Linux

**AI/Tooling:** Groq · Openrouter · Postman · Git

---

## DSA

- **247+ problems** solved on LeetCode (C++)
- Strong in: Dynamic Programming · Graph algorithms · Binary Search · Hash Tables
- Consistent streak: 50 Days Badge 2025, 100 Days Badge 2025, 50 Days Badge 2026

[![LeetCode Stats](https://leetcard.jacoblin.cool/MohitKumar2512?theme=dark&font=Nunito&ext=contest)](https://leetcode.com/u/MohitKumar2512/)

---

## Experience

**Frontend Web Development Intern — Leaf Gains Finance** *(May–Jul 2026)*
Built 10+ responsive pages and 15+ React components; resolved 20+ interface bugs; shipped features in agile Git-based workflows that cut delivery cycles by 25%.

---

## Achievements

- 🥈 Runner-up (2nd of 150+ teams) — IIT Delhi National Photography Competition, 2026
- 🥇 Winner in 2 categories (300+ entries) — Antaragni, IIT Kanpur, 2025
- ✍️ Published photographer/writer in *Karobar* Annual Magazine, Sri Venkateswara College, DU

---

## GitHub Activity

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=MateeRixx&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=true&show_icons=true)

![Streak](https://nirzak-streak-stats.vercel.app/?user=MateeRixx&theme=tokyonight&hide_border=true)

---

<div align="center">
  <sub>Open to SDE roles · Graduating 2027 · <a href="mailto:mohitrkumar2512@gmail.com">mohitrkumar2512@gmail.com</a></sub>
</div>
