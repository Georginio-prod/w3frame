# w3frame — Squelette Nuxt 4 + Tailwind CSS v4

![Nuxt](https://img.shields.io/badge/Nuxt-4-00DC82?logo=nuxt.js&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-4-06B6D4?logo=tailwindcss&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-5-3178C6?logo=typescript&logoColor=white)
![Statut](https://img.shields.io/badge/Statut-Squelette-lightgrey)

📦 **Code source** : <https://github.com/Georginio-prod/w3frame>

---

## 📌 Présentation

Point de départ **Nuxt 4** pré-configuré avec **Tailwind CSS v4** (plugin Vite officiel)
et les modules Nuxt UI, Image, Scripts, Hints, ESLint et Test Utils.

Le nom fait référence à **w3frame**, le domaine sous lequel mon portfolio est publié
(`georginio.w3frame.com`). Ce dépôt sert de **base réutilisable** pour démarrer rapidement
un nouveau site Nuxt avec ma configuration habituelle ; il ne contient pas encore de
contenu fonctionnel (page « Hello world »).

## 🛠️ Ce qui est configuré

| Élément | Détail |
|---|---|
| Framework | Nuxt 4 (`app/` directory, `compatibilityDate: 2025-07-15`) |
| Styles | Tailwind CSS v4 via `@tailwindcss/vite`, feuille `app/assets/css/main.css` |
| Modules | `@nuxt/ui`, `@nuxt/image`, `@nuxt/scripts`, `@nuxt/hints`, `@nuxt/eslint`, `@nuxt/test-utils` |
| Outils | Nuxt DevTools activés |

## 📁 Structure

```
w3frame/
├── nuxt.config.ts            # Plugin Tailwind + CSS global
├── app/
│   ├── app.vue               # Page d'exemple
│   └── assets/css/main.css   # @import "tailwindcss"
└── public/                   # favicon, robots.txt
```

## 🚀 Utilisation

```bash
git clone https://github.com/Georginio-prod/w3frame.git mon-projet
cd mon-projet
npm install
npm run dev        # http://localhost:3000
```

| Commande | Description |
|---|---|
| `npm run dev` | Développement |
| `npm run build` | Build SSR de production |
| `npm run generate` | Génération statique |
| `npm run preview` | Prévisualisation |

## 🌐 Déploiement

Non déployé (squelette sans contenu). Un `npm run build` suffit pour le publier sur Vercel,
Netlify ou Railway le jour où il accueille un vrai projet.

---

## 👤 Auteur

**Komla Etonam Georges EKLOU** (Georginio) — Développeur Full Stack Web & Web3

[![GitHub](https://img.shields.io/badge/GitHub-Georginio--prod-181717?logo=github)](https://github.com/Georginio-prod)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Profil-0A66C2?logo=linkedin)](https://www.linkedin.com/in/komla-etonam-georges-eklou-68518b23b)
[![Portfolio](https://img.shields.io/badge/Portfolio-georginio.w3frame.com-6C63FF)](https://georginio.w3frame.com/)

> 📚 Tous mes projets sont listés et documentés sur mon [profil GitHub](https://github.com/Georginio-prod).
