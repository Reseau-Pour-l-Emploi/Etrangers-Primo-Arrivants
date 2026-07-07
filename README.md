# Suivi 2026 — Intégration des étrangers primo-arrivants

Tableau de bord statique (HTML/CSS/JS vanilla) suivant l'instruction NOR INTV2607925J du 7 avril 2026. Chiffres fictifs — à connecter aux sources réelles (tableau de bord RPE, SI AGIR, PNE, RESANA).

## Déploiement GitHub Pages

1. Créer le repo et pousser ce contenu sur `main`.
2. Settings → Pages → Branch `main` / dossier `/ (root)` → Save.
3. URL générée : `https://<user>.github.io/<repo>/`

## Structure
```
index.html          page unique
fonts/               Marianne (woff2)
assets/              logo France Travail
```

## Mise à jour des données
Chiffres codés en dur dans `index.html` (sections `<section id="...">`). Pas de backend.
