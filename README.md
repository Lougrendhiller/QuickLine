🚀 QuickLine
Smart Queue Management System

QuickLine est une application web moderne permettant la gestion numérique des files d’attente en temps réel. Elle vise à améliorer l’organisation, réduire les temps d’attente et optimiser l’expérience utilisateur.

✨ Fonctionnalités

🎟️ Génération automatique de tickets

📋 Gestion FIFO (First In, First Out)

👤 Authentification sécurisée (Clerk)

🖥️ Interface moderne et responsive

🗂️ Gestion des statuts de tickets

🔐 Protection des routes via middleware

🛠️ Stack Technique

Next.js 15 (App Router)

TypeScript

Prisma ORM

Clerk Authentication

TailwindCSS + DaisyUI

📦 Installation
git clone <repository-url>
cd quick-line
npm install


Configurer le fichier .env :

DATABASE_URL=
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=


Puis :

npx prisma migrate dev
npm run dev

📌 Architecture

Frontend & Backend intégrés via Next.js

Server Actions pour la logique métier

Base de données relationnelle via Prisma

Sécurité via Clerk et middleware

📈 Améliorations futures

Notifications en temps réel

Statistiques avancées

Système multi-services

QR Code pour tickets

📄 Licence

Projet académique / démonstration technique.