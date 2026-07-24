# Frontend - Bastion AI

Ceci est l'application client Next.js pour Bastion AI.

## 🎯 Responsabilités

- Interface utilisateur (UI/UX)
- Gestion de l'état client
- Communication avec le backend via API
- Upload et visualisation des captures d'écran
- Affichage des recommandations IA

## 🛠️ Stack Technique

- **Framework** : Next.js 14+ (App Router)
- **Langage** : TypeScript
- **Styling** : TailwindCSS
- **Linting** : ESLint

## 🚀 Getting Started

### Installation

```bash
npm install
```

### Développement

```bash
npm run dev
```

L'application est accessible sur `http://localhost:3000`

### Build Production

```bash
npm run build
npm start
```

### Linting

```bash
npm run lint
```

## 📁 Structure

```
frontend/
├── app/              # Routes et pages (App Router)
│   ├── layout.tsx    # Layout principal
│   ├── page.tsx      # Page d'accueil
│   └── globals.css   # Styles globaux
├── components/       # Composants réutilisables (à créer)
├── lib/             # Utilitaires et services (à créer)
├── types/           # Types TypeScript (à créer)
├── public/          # Assets statiques (à créer)
├── package.json     # Dépendances
├── tsconfig.json    # Configuration TypeScript
├── next.config.js   # Configuration Next.js
├── eslint.config.mjs # Configuration ESLint
├── tailwind.config.js # Configuration TailwindCSS
└── postcss.config.js  # Configuration PostCSS
```

## 📝 Notes

- Aucune logique métier pour le moment
- Les données proviennent du backend `/api/*`
- Le design utilise TailwindCSS pour la cohérence
