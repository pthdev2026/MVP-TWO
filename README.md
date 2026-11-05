# ORIGIN / MILLENIUM — MVP 2 (front + back-end)

Plateforme de streaming : instantané complet du front et du back-end.

- `frontend/` — interface MILLENIUM (React, TanStack Start). Fonctionne **sans API** en mode « aperçu hors connexion » : voir `frontend/README.md`.
- `backend/` — API (Node 24, Hono, PostgreSQL), pipeline vidéo, déploiement et documentation.
  - Contrat d'API : `backend/docs/API-CONTRACT.md`
  - Brief complet : `backend/docs/BRIEF-BACKEND-COMPLET.md`
  - Démarrage : `backend/api/README.md`

Aucun secret n'est dans ce dépôt (les fichiers `.env` sont exclus ; voir `*.env.example`).
