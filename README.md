# Mourad Barkaoui — Braiinz

**Je construis des agents IA et des logiciels métier qui tournent en production, pour les ESN et les équipes qui veulent industrialiser leur delivery.**

Conseil en transformation · IA · data · formation — [braiinz.fr](https://braiinz.fr)

---

### 🏗️ Fulmin — ERP pour ESN *(code privé, démo sur demande)*

Un ERP complet pour sociétés de services numériques : CRM, vivier RH, staffing et missions, temps et facturation, modules IA natifs. Multi-agence, conçu et maintenu seul, de la base de données au déploiement.

| | |
|---|---|
| **Backend** | Python · FastAPI · SQLAlchemy 2 async · PostgreSQL 16 + pgvector · Redis |
| **Frontend** | TypeScript · React · Vite · TanStack Query |
| **Qualité** | tout passe par pull request (160+ PR) · CI à chaque PR · ~100 fichiers de tests · tests de bout en bout |
| **Sécurité** | workflow sécurité dédié · Dependabot · argon2 · isolation stricte des données par agence (anti-IDOR) · requêtes SQL paramétrées |
| **Architecture** | Outbox pattern vers la plateforme d'agents · décisions tracées en ADR · migrations Alembic |

### 🤖 Agents IA appliqués

- **Plateforme multi-agents ESN** *(privé)* — agents spécialisés pour les métiers d'une ESN, orchestrés avec Claude, avec validation humaine avant toute action externe.
- **[`braiinz-education`](https://github.com/braiinz94/braiinz-education)** *(open source, Apache-2.0)* — trois agents pédagogiques sur Telegram : tuteur socratique, coach pratique, diagnostiqueur à répétition espacée (FSRS). Routeur de modèles au coût, option d'hébergement des données en UE.

### 🌐 Contributions open source

- **[storytold/deckcraft](https://github.com/storytold/deckcraft/pull/944)** *(Rust)* — tests de robustesse (fuzzing) des décodeurs vidéo et audio écrits à la main : AV1, VP9, HEVC, H.264, Opus. *PR en cours de revue.*

### 🧭 Ma façon de travailler

- **Humain dans la boucle** : un agent prépare, une personne décide. Rien ne part sans validation.
- **Sécurité dès le départ** : moindre privilège, secrets hors du code, journal d'audit.
- **Mesurer avant d'affirmer** : tests écrits avant le code, CI verte avant fusion.

### 🛠️ Stack

`Python` · `FastAPI` · `PostgreSQL` · `pgvector` · `Redis` · `TypeScript` · `React` · `Docker` · `GitHub Actions` · `Claude API` · `Claude Code` · `MCP` · `Astro`

### 📫 Contact

[braiinz.fr](https://braiinz.fr) · une démo de Fulmin ou des agents ? Écrivez-moi via le site.
