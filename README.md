# Notre projet immobilier — Finistère

Outil de simulation et d'aide à la décision pour notre stratégie d'investissement immobilier à 2 biens en Finistère.

## Ce que contient l'outil

- **Vue d'ensemble** — stratégie à 2 biens, enveloppe totale, séquençage animé
- **Le marché** — comparatif de 9 villes du Finistère, table filtrable par rendement / prix / potentiel saisonnier
- **Bien 1 — appart locatif** — fiches Morlaix et Brest, simulateur avec 4 curseurs (prix, loyer, taux, durée) → cashflow en temps réel
- **Bien 2 — maison saisonnière** — fiches Douarnenez / Crozon, simulateur avec 6 curseurs (prix achat, nuit, occupation, semaines perso, frais, crédit) → revenus nets et cashflow
- **Stratégie & timing** — timeline des 4 phases, critères de recherche, projection des revenus combinés sur 5 ans
- **Points de vigilance** — checklist pré-offre pour chaque bien, loi Le Meur, DPE, fiscalité LMNP

## Déploiement sur GitHub Pages

1. Créer un nouveau repository public sur [github.com](https://github.com) (ex: `projet-immo`)
2. Uploader `index.html`
3. Aller dans **Settings → Pages**
4. Source : **Deploy from a branch** → branche `main`, dossier `/ (root)`
5. Cliquer **Save** — le site est en ligne en 1 à 3 minutes

URL : `https://[username].github.io/projet-immo/`

## Usage local

Ouvrir directement `index.html` dans un navigateur — aucun serveur requis, aucune dépendance à installer.

## Données sources

- DVF DGFiP (transactions notariées)
- DHUP 2025 (loyers d'annonce observatoire)
- MeilleursAgents · juin 2026
- SeLoger / LocService 2026
- Annonces LeBonCoin et Laforêt analysées (juillet 2026)

---

*Usage privé · Non contractuel · Juillet 2026*
