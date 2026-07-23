*<p align="center">
  <strong>English</strong> •
  <a href="./README.fr.md">Français</a>
</p>

<!-- Profile README - Yoann CORGNET -->
<h1 align="center">&gt; Yoann CORGNET</h1>
<p align="center">
  Tech Lead @ <strong><a href="https://nerionsoft.com">NerionSoft</a></strong><br/>
  <em>Software Engineering student · ESIEA</em>
</p>

<p align="center">
  <a href="https://yoann-corgnet.dev">yoann-corgnet.dev</a> •
  <a href="https://www.linkedin.com/in/yoann-corgnet-26a039270/">LinkedIn</a> •
  <a href="mailto:yoann.corgnet@laposte.net">yoann.corgnet@laposte.net</a>
</p>

--- 

Tech Lead at [NerionSoft](https://nerionsoft.com) since September 2025, where I architect Hestia,
our hotel booking engine. The real technical challenge lies in the PMS connectors (the hotel ERP):
syncing reservations and rates in real time through Apaleo (certified) and Adyen for payments
(3DS, virtual cards), without ever letting a reservation's state drift out of sync between the two.

My path has been shaped by a taste for academic challenge: I'm finishing my engineering degree with
a dual-degree program at CentraleSupélec. Before that, the dual degree at UQAC (2024-2025) took me
beyond pure software, with an international experience and a look into adjacent fields (IA/data and cybersecurity).

On the projects side, StockElec (2nd year) was my first contact with a real product: scoping the need
with a client, and above all learning to hand a project off cleanly (docs matter). Undrive (4th year)
went further: my first production deployment, on GCP, and a first dive into microservices architecture.

## # projects

### ▸ Hestia <small>Reservation</small> · [\[↗\]](https://nerionsoft.com/en/booking-engine)
> SaaS booking engine for independent hoteliers, a direct alternative to OTAs.

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=for-the-badge&logo=prisma&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)
![Vitest](https://img.shields.io/badge/Vitest-6E9F18?style=for-the-badge&logo=vitest&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![SonarQube](https://img.shields.io/badge/SonarQube-126ED3?style=for-the-badge&logo=sonarqubecloud&logoColor=white)

- → DDD domain with pluggable PMS adapters: Apaleo today, Mews / Cloudbeds tomorrow without touching the core
- → Transactional outbox (no confirmation e-mail ever lost), idempotent webhooks (no double-booking on replay), explicit reservation state machine
- → Real-time KPI dashboard (revenue, occupancy rate, ADR, RevPAR, conversion funnel) on optimized PostgreSQL aggregations, with interactive visualizations
- → Next.js 16 on Vercel · Neon · better-auth · Resend · CI/CD with preview envs per PR
- → Tech Lead, from design to production

### ▸ Undrive · <small>*Sept 2025 → Feb 2026*</small>
> Mobile gamification app rewarding public-transport usage.

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Google Cloud](https://img.shields.io/badge/Google_Cloud-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)

- → CI/CD infra on GCP with Terraform, Cloud Run deploys, GitHub Actions workflows
- → Django backend API + Python microservices, PostgreSQL / PostGIS

### ▸ StockElec 🥈 · <small>*2023 → 2024*</small>
> Web stock-management app for ESIEA's electronics lab. *(Silver medal, 2nd-year project)*

![Vue.js](https://img.shields.io/badge/Vue.js-4FC08D?style=for-the-badge&logo=vuedotjs&logoColor=white)
![Quasar](https://img.shields.io/badge/Quasar-1976D2?style=for-the-badge&logo=quasar&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)
![Java Spring](https://img.shields.io/badge/Java_Spring-6DB33F?style=for-the-badge&logo=spring&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)

- → Quasar (Vue.js) + Tailwind frontend with an interactive analytics dashboard
- → Java Spring REST API · MySQL · fully containerized with Docker
- → Built agile, with direct client requirements gathering

---

## # education

- **2026-2027** · **CentraleSupélec** · Specialization degree in Computer Science, dual-degree program
- **2024-2027** · **ESIEA** · Engineering degree, Software Engineering major
- **2024-2025** · **UQAC** · BSc Computer Science (Cybersecurity · Big Data & AI)
