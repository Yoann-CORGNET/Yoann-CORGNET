<p align="center">
  <a href="./README.md">English</a> •
  <strong>Français</strong>
</p>

<!-- Profile README - Yoann CORGNET -->
<h1 align="center">&gt; Yoann CORGNET</h1>
<p align="center">
  <em>Étudiant ingénieur CentraleSupélec &amp; ESIEA · Software Engineering</em>
</p>

<p align="center">
  <a href="https://yoann-corgnet.dev">yoann-corgnet.dev</a> •
  <a href="https://www.linkedin.com/in/yoann-corgnet-26a039270/">LinkedIn</a> •
  <a href="mailto:yoann.corgnet.04@gmail.com">yoann.corgnet.04@gmail.com</a>
</p>

---

Salut, moi c'est Yoann 👋

Étudiant en génie logiciel, je termine un double diplôme entre l'ESIEA et CentraleSupélec.
J'aime construire des produits, et la partie qui m'intéresse le plus vient avant le code : comprendre
le problème assez bien pour que l'architecture en découle.

Sur Hestia, un moteur de réservation hôtelier, la difficulté venait du métier. Une réservation vit dans deux
systèmes, le moteur et le PMS de l'hôtel (son logiciel de gestion), et son état ne doit jamais diverger entre
les deux. C'est de là que découle le reste : adaptateurs PMS modulaires, webhooks idempotents, machine à états
explicite.

Je juge une conception à sa tenue en production, et je pèse ce que coûte chaque couche d'abstraction avant
de l'ajouter. Je tiens aussi à ce qui entoure le code (CI, environnements de preview, tests, documentation),
parce que c'est ce qui permet à un produit de continuer à évoluer une fois que l'équipe d'origine est passée
à autre chose.

## # projects

### ▸ Hestia <small>Réservation</small> · <small>*Sept. 2025 → Août 2026*</small> · [\[↗\]](https://nerionsoft.com/moteur-de-reservation)
> Moteur de réservation SaaS pour hôteliers indépendants, alternative directe aux OTAs.

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=for-the-badge&logo=prisma&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)
![Vitest](https://img.shields.io/badge/Vitest-6E9F18?style=for-the-badge&logo=vitest&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![SonarQube](https://img.shields.io/badge/SonarQube-126ED3?style=for-the-badge&logo=sonarqubecloud&logoColor=white)

- → Domaine DDD avec adaptateurs PMS modulaires : Apaleo d'abord, Mews / Cloudbeds ajoutables sans toucher au cœur métier
- → Outbox transactionnel (aucun e-mail de confirmation perdu), webhooks idempotents (pas de double-booking sur replay), machine à états explicite du cycle de vie d'une réservation
- → Dashboard KPI temps réel (revenus, taux d'occupation, ADR, RevPAR, funnel de conversion) sur agrégations PostgreSQL optimisées, avec visualisations interactives
- → Next.js 16 sur Vercel · Neon · better-auth · Resend · CI/CD avec preview envs par PR
- → Tech Lead chez [NerionSoft](https://nerionsoft.com), de la conception à la mise en production

### ▸ Undrive · <small>*Sept. 2025 → Mars. 2026*</small>
> Application mobile de gamification qui récompense l'usage des transports en commun.

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Google Cloud](https://img.shields.io/badge/Google_Cloud-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)

- → Infra CI/CD sur GCP avec Terraform, déploiement Cloud Run, workflows GitHub Actions
- → API backend Django + microservices Python, base PostgreSQL / PostGIS

### ▸ StockElec 🥈 · <small>*2023 → 2024*</small>
> Application web de gestion de stock pour le laboratoire d'électronique de l'ESIEA. *(Médaille d'argent, projet de 2ᵉ année)*

![Vue.js](https://img.shields.io/badge/Vue.js-4FC08D?style=for-the-badge&logo=vuedotjs&logoColor=white)
![Quasar](https://img.shields.io/badge/Quasar-1976D2?style=for-the-badge&logo=quasar&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)
![Java Spring](https://img.shields.io/badge/Java_Spring-6DB33F?style=for-the-badge&logo=spring&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)

- → Frontend Quasar (Vue.js) + Tailwind, tableau analytique interactif
- → Backend Java Spring · MySQL · le tout conteneurisé via Docker
- → Méthode agile avec recueil du besoin client

---

## # education

- **2026-2027** · **CentraleSupélec** · Diplôme de spécialisation en Science du logiciel, en double diplôme
- **2024-2027** · **ESIEA** · Diplôme d'ingénieur, Majeure Software Engineering
- **2024-2025** · **UQAC** · Double diplôme, Bac+3 Informatique (Cybersécurité · Big Data & IA)
