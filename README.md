# COVO Pro — dépôt unique

COVO Pro et tous ses satellites réunis dans **un seul dépôt**, comme Restauration Pro.

```
/
├── index.html      ← redirige vers app/
├── app/            ← COVO Pro (application principale)
├── caisse/         ← Caisse Pro
├── fidelite/       ← Fidélité Pro
├── gestion/        ← Gestion Pro
├── appro/          ← Approvisionnement Pro
├── finances/       ← Finances Pro
├── historique/     ← Historique Pro
├── clotures/       ← Clôtures Pro
├── projets/        ← Projets Pro (+ icônes, manifest, service worker)
├── admin/          ← Admin Pro
├── visites/        ← Visites Pro
└── .nojekyll
```

## Mise en ligne (GitHub Pages)

1. Créez un nouveau dépôt public, par exemple **COVO-Pro-Suite**
   (« COVO-Pro » n'est pas possible : le dépôt « Covo-pro » existe déjà et GitHub ignore les majuscules).
2. Envoyez **le contenu** de ce dossier à la racine du dépôt (index.html à la racine).
3. Settings → Pages → Deploy from a branch → `main` / `(root)` → Save.
4. En ligne après 1–2 min :
   - COVO Pro : `https://aliand0810.github.io/COVO-Pro-Suite/` (→ `app/`)
   - Caisse Pro : `https://aliand0810.github.io/COVO-Pro-Suite/caisse/`
   - Fidélité Pro : `…/fidelite/`, Gestion Pro : `…/gestion/`, etc.

Le nom du dépôt est libre : tous les liens entre applications sont **relatifs**.

## Données, Drive, licence

Même site (`aliand0810.github.io`) : les données de chaque appareil sont retrouvées sans migration.
Google Drive, Firebase et la licence : rien à changer.

## Mettre à jour une application

Remplacez le fichier `index.html` du dossier concerné (ex. `caisse/index.html`).
