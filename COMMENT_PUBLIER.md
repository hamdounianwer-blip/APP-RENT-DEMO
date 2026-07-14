════════════════════════════════════════════════════════════════════
 COMMENT METTRE CETTE DÉMO EN LIGNE — 100% VIA LE SITE GITHUB.COM
 (aucune installation, aucun terminal, aucun git requis)
════════════════════════════════════════════════════════════════════

ÉTAPE 1 — Créer le repository (2 min)
────────────────────────────────────────────────────────────────────
1. Va sur https://github.com et connecte-toi
2. Clique sur le bouton "+" en haut à droite → "New repository"
3. Nom du repo : par exemple "cityrent-demo"
4. Visibilité : PUBLIC (obligatoire pour que GitHub Pages soit gratuit)
5. Ne coche PAS "Add a README" (on a déjà le nôtre)
6. Clique "Create repository"

ÉTAPE 2 — Uploader les fichiers (3 min)
────────────────────────────────────────────────────────────────────
1. Sur la page de ton nouveau repo (vide), clique sur le lien
   "uploading an existing file"
   (ou : bouton "Add file" → "Upload files")
2. Glisse-dépose TOUT le contenu de ce dossier dans la zone d'upload :
   - index.html
   - README.md
   - logo.png
   - le dossier css/ (avec main.css et theme.css dedans)
   - le dossier js/ (avec tous les fichiers .js dedans)

   Astuce : la plupart des navigateurs modernes (Chrome, Edge) gardent
   la structure des dossiers si tu glisses le dossier "css" et le
   dossier "js" entiers (pas juste les fichiers un par un). Si ça ne
   marche pas, tu peux aussi glisser les fichiers un par un dans
   chaque dossier — GitHub recrée l'arborescence automatiquement selon
   le chemin que tu tapes dans la zone de nom de fichier.
3. En bas de page, message de commit : écris par exemple
   "Version démo publique"
4. Clique "Commit changes"

ÉTAPE 3 — Activer GitHub Pages (1 min)
────────────────────────────────────────────────────────────────────
1. Dans ton repo, va dans l'onglet "Settings" (en haut)
2. Dans le menu de gauche, clique "Pages"
3. Sous "Build and deployment" → "Source" : choisis "Deploy from a branch"
4. Sous "Branch" : choisis "main" et le dossier "/ (root)"
5. Clique "Save"
6. Attends 1-2 minutes, puis recharge la page Settings → Pages
   Le lien apparaît en haut, du genre :
   https://TON-NOM-UTILISATEUR.github.io/cityrent-demo/

ÉTAPE 4 — Tester
────────────────────────────────────────────────────────────────────
1. Ouvre le lien généré
2. Connecte-toi avec : demo / 0000
3. Vérifie que tout s'affiche bien (véhicules, clients, contrats...)
4. Le bouton "🗑️ Réinitialiser démo" en bas à droite efface les
   données de CE navigateur uniquement (chaque visiteur a son propre
   stockage local, indépendant des autres)

════════════════════════════════════════════════════════════════════
 C'est tout ! Le lien est utilisable par n'importe qui, sans rien
 installer. Chaque personne qui l'ouvre a SA PROPRE copie des données
 dans SON PROPRE navigateur (rien n'est partagé entre visiteurs).
════════════════════════════════════════════════════════════════════
