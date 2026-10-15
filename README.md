# Notes INFO-Y-122 – Analysis (Logseq)

Graphe Logseq personnel pour suivre les présentations hebdomadaires du cours INFO-Y-122.

## Contenu

- `pages/INFO-Y-122.md` : page d'accueil du cours, routine et liste automatique des frameworks vus
- `pages/Templates.md` : modèle de page **framework** (briefing, notes en 3 parties, questions, ce que je retiens)
- `pages/Glossaire EN-FR.md` : glossaire anglais → français, à compléter chaque semaine

## Mise en place (une seule fois)

1. Sur GitHub, crée un dépôt **privé** vide nommé `logseq-info-y-122` (sans README).
2. Dans un terminal, depuis ce dossier :
   ```bash
   git remote add origin git@github.com:<ton-pseudo>/logseq-info-y-122.git
   git branch -M main
   git push -u origin main
   ```
   (ou l'URL `https://github.com/<ton-pseudo>/logseq-info-y-122.git` si tu n'as pas de clé SSH)
3. Dans Logseq : **Ajouter un graphe** → choisis ce dossier.

## Chaque semaine

1. Dimanche : crée la page du framework (ex. `NIST CSF 2.0`), tape `/Template` → **framework**.
2. En cours : remplis les notes en vrac.
3. Après le cours :
   ```bash
   git add . && git commit -m "Séance <date> – <framework>" && git push
   ```

Astuce : dans Logseq, *Paramètres → Contrôle de version → Git auto commit* fait les commits automatiquement (il reste à faire `git push` toi-même).
