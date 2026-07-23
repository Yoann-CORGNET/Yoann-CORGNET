<p align="center">
  <a href="./README.md">English</a> •
  <strong>Français</strong>
</p>

<!-- Profile README - Yoann CORGNET -->
<h1 align="center">&gt; Yoann CORGNET</h1>
<p align="center">
  Tech Lead @ <strong><a href="https://nerionsoft.com">NerionSoft</a></strong><br/>
  <em>Étudiant ingénieur ESIEA · Software Engineering</em>
</p>

<p align="center">
  <a href="https://yoann-corgnet.dev">yoann-corgnet.dev</a> •
  <a href="https://www.linkedin.com/in/yoann-corgnet-26a039270/">LinkedIn</a> •
  <a href="mailto:yoann.corgnet@laposte.net">yoann.corgnet@laposte.net</a>
</p>

---

Tech Lead chez [NerionSoft](https://nerionsoft.com) depuis septembre 2025, où j'architecture Hestia,
notre moteur de réservation hôtelier. Le vrai enjeu technique tient aux connecteurs PMS (l'ERP hôtelier) :
synchroniser réservations et tarifs en temps réel via Apaleo (certifié) et Adyen pour le paiement
(3DS, cartes virtuelles), sans jamais désynchroniser l'état d'une réservation entre les deux.

Mon parcours s'est construit autour d'une volonté de challenge académique : je termine mon diplôme d'ingénieur
par un double diplôme à CentraleSupélec. Avant ça, le double diplôme à l'UQAC (2024-2025) m'a fait sortir du software pur,
avec une ouverture à l'international et une exploration de domaines adjacents (IA/data et cybersécurité).

Côté projets, StockElec (2A) a été le premier contact avec un vrai produit : cadrer le besoin avec un client,
et surtout apprendre à transmettre un projet proprement (la docs c'est important). Undrive (4A) est allé plus loin :
première mise en prod, sur GCP, avec découverte de l'architecture en microservices au passage.

## # projects

### ▸ Hestia <small>Réservation</small> · [\[↗\]](https://nerionsoft.com/moteur-de-reservation)
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

- → Domaine DDD avec adaptateurs PMS modulaires : Apaleo aujourd'hui, Mews / Cloudbeds demain sans toucher au cœur métier
- → Outbox transactionnel (aucun e-mail de confirmation perdu), webhooks idempotents (pas de double-booking sur replay), machine à états explicite du cycle de vie d'une réservation
- → Dashboard KPI temps réel (revenus, taux d'occupation, ADR, RevPAR, funnel de conversion) sur agrégations PostgreSQL optimisées, avec visualisations interactives
- → Next.js 16 sur Vercel · Neon · better-auth · Resend · CI/CD avec preview envs par PR
- → Tech Lead, de la conception à la mise en production

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
