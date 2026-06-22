# ThreadCart — Backend

Strapi-based headless CMS + API for the ThreadCart industrial e-commerce platform (nuts, bolts, fasteners + a gated CAD diagram library for logged-in users).

## What this repo is

The backend. Product data, user accounts, order management, Razorpay payments, CAD file storage and download gating.

## Stack

- Strapi (headless CMS, TypeScript)
- Razorpay integration for payments
- Deployed on Render

## Local development

```bash
cp .env.example .env
npm install
npm run develop
```

## Related

Frontend: [ThreadCart-Frontend](https://github.com/GaneshPatil22/ThreadCart-Frontend)
