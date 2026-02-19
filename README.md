# SaaS Gestion d'Abonnements

Système de gestion des clients, abonnements et facturation automatisée avec réseau de revendeurs.

## Architecture

- **Frontend**: React + TypeScript + TailwindCSS + shadcn/ui
- **Backend**: Node.js + Express + TypeScript
- **Database**: PostgreSQL
- **Auth**: JWT
- **PDF**: Puppeteer
- **Email**: Nodemailer

## Structure

```
subscription-saas/
├── frontend/          # Application React
├── backend/           # API Node.js
├── shared/            # Types et validations partagés
└── docs/             # Documentation
```

## Modules MVP

1. [x] Authentification & Rôles
2. [ ] Base de données & Modèles
3. [ ] Gestion Clients/Revendeurs
4. [ ] Moteur de Facturation
5. [ ] Portail Revendeur

## Installation

```bash
# Backend
cd backend
npm install
npm run dev

# Frontend
cd frontend
npm install
npm run dev
```
