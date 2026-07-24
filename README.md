# 🛡️ Bastion AI

Bastion AI est un copilote stratégique pour Travian.

Son objectif est simple :

Le joueur envoie des captures d'écran.

Bastion analyse automatiquement la situation.

Puis il fournit un plan d'action clair et priorisé.

## 📋 Exemple

1. Améliorer la scierie niveau 6.
2. Former 20 phalanges.
3. Utiliser le héros pour finir le champ de céréales.
4. Attendre 2h avant de lancer la résidence.
5. Ne pas utiliser le NPC pour le moment.

Le joueur n'a plus besoin de réfléchir.

**Bastion devient son conseiller stratégique.**

---

## 🛠️ Technologies

### Frontend
- **Framework** : Next.js 14+ avec TypeScript
- **Styling** : TailwindCSS
- **State Management** : React Hooks / Context API

### Backend
- **Framework** : FastAPI (Python 3.11+)
- **ORM** : SQLAlchemy
- **Validation** : Pydantic

### AI
- **LLM Integration** : OpenAI / Anthropic / Local Models
- **Vision** : Analyse automatique de captures d'écran
- **NLP** : Compréhension de contexte Travian

### Infrastructure
- **Database** : PostgreSQL 16+
- **Containerization** : Docker & Docker Compose
- **CI/CD** : GitHub Actions

## 📁 Structure du dépôt

```
bastion-ai/
├── frontend/              # Application Next.js (UI)
├── backend/               # API FastAPI
├── ai/                    # Moteur d'IA & analyse d'images
├── database/              # Migrations et schemas PostgreSQL
├── docs/                  # Documentation
├── docker/                # Configuration Docker
├── .github/workflows/     # Pipelines CI/CD
├── .gitignore            # Fichiers ignorés
└── README.md             # Ce fichier
```

## 🚀 Roadmap

### Sprint 0 : Fondations ✅
- [x] Structure de projet
- [ ] Configuration Docker Compose
- [ ] Setup backend FastAPI
- [ ] Setup frontend Next.js
- [ ] Route GET /health

### Sprint 1 : Infrastructure IA
- [ ] Intégration LLM pour analyse
- [ ] Service de vision (screenshot parsing)
- [ ] Prompt engineering pour recommandations
- [ ] Cache responses

### Sprint 2 : API Core
- [ ] Upload et gestion des captures
- [ ] Analyse automatique
- [ ] Génération de recommandations
- [ ] Historique des analyses

### Sprint 3 : Frontend MVP
- [ ] Interface d'upload
- [ ] Affichage du plan d'action
- [ ] Dashboard utilisateur
- [ ] Historique des recommandations

## 📄 Licence

MIT - Libre d'usage et de modification.
