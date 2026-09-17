---
date: '5'
title: 'ASAS Online'
cover: './demo.png'
external: 'https://asasonline.asasgate.net'
tech:
  - Next.js
  - Hono
  - Prisma
  - PostgreSQL
  - Docker (blue-green)
---

ASAS Online (أساس أونلاين) is a production e-commerce platform for electronics and consumer tech serving Saudi Arabia and the GCC. It replaced a hosted Zid store with a fully owned stack: an Arabic-first, bilingual storefront across 14 locales in 7 countries, a complete back-office admin, 4 payment gateways (Tap, Paymob, Tabby, Tamara) plus COD and bank transfer, live carrier shipping (Torod, SMSA), and ZATCA Phase 2 compliant e-invoicing. The migration preserved 2,000+ live URLs byte-exact for zero SEO loss. Under the hood: a server-rendered Next.js storefront and a Hono + Prisma + PostgreSQL API (~140 models) owning inventory, order state machines, idempotent payment webhooks, staff RBAC, and blue-green Docker deploys via GitHub Actions.
