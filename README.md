# 🦵 Protocole Genou · PWA

Progressive Web App de suivi du protocole de rééducation tendinopathie patellaire.

## Fonctionnalités

- 📋 **Protocole** — Exercices par phase avec stick figures, règles de douleur, nutrition
- 📅 **Agenda** — Planning semaine par semaine du 8 mai au 27 septembre 2025
- 📊 **Tracker** — Saisie quotidienne de douleur + checklist + historique

## Installation sur mobile

### iPhone (Safari)
1. Ouvre l'app dans Safari
2. Appuie sur le bouton Partager (carré avec flèche)
3. "Sur l'écran d'accueil"
4. L'app s'installe comme une vraie app

### Android (Chrome)
1. Ouvre l'app dans Chrome
2. Menu ⋮ → "Ajouter à l'écran d'accueil"
3. L'app s'installe comme une vraie app

## Déploiement GitHub Pages

1. Fork ou clone ce repo
2. Va dans **Settings → Pages**
3. Source : `Deploy from a branch` → `main` → `/ (root)`
4. Sauvegarde → ton URL sera : `https://[username].github.io/[repo-name]`

## Structure

```
genou-pwa/
├── index.html      # App complète (single page)
├── manifest.json   # Config PWA
├── sw.js           # Service Worker (offline)
└── icons/
    ├── icon-192.png
    └── icon-512.png
```

## Données

Toutes les données du tracker sont stockées **localement** sur ton téléphone (localStorage). Aucune donnée n'est envoyée sur un serveur.

---
*Protocole basé sur Cook & Purdam 2009 · Rio et al. 2015 · Shaw et al. 2017*
