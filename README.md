# Entraînement Certificat Voltaire — Professionnel 500/1000

Site d'entraînement personnel au Certificat Voltaire (niveau Professionnel), en une seule page HTML autonome : fiches de règles, vocabulaire, « L'officiel du Voltaire », modules d'apprentissage par bulles, examen blanc chronométré et mode sombre.

Tout est contenu dans **`index.html`** — aucun serveur, aucune dépendance à installer. La progression est sauvegardée dans le navigateur (localStorage), donc propre à chaque appareil/navigateur.

## Mettre le site en ligne avec GitHub Pages (gratuit)

### Étape 1 — Créer le dépôt sur GitHub

1. Va sur [github.com](https://github.com) et connecte-toi (crée un compte gratuit si besoin).
2. Clique sur le bouton **+** en haut à droite → **New repository**.
3. Donne-lui un nom, par exemple `voltaire-entrainement`.
4. Laisse-le en **Public** (obligatoire pour la version gratuite de GitHub Pages).
5. Ne coche aucune case d'initialisation (pas de README, pas de .gitignore) — on va uploader les fichiers directement.
6. Clique sur **Create repository**.

### Étape 2 — Mettre en ligne le fichier `index.html`

**Option la plus simple (sans rien installer) :**

1. Sur la page de ton nouveau dépôt, clique sur **uploading an existing file** (ou **Add file → Upload files**).
2. Glisse-dépose le fichier `index.html` de ce dossier (et ce `README.md` si tu veux).
3. En bas de page, clique sur **Commit changes**.

**Option avec Git en ligne de commande** (si tu préfères) :

```bash
cd chemin/vers/ce/dossier
git init
git add index.html README.md
git commit -m "Site d'entraînement Voltaire"
git branch -M main
git remote add origin https://github.com/TON-PSEUDO/voltaire-entrainement.git
git push -u origin main
```

### Étape 3 — Activer GitHub Pages

1. Dans ton dépôt, va dans **Settings** (onglet en haut).
2. Dans le menu de gauche, clique sur **Pages**.
3. Sous « Build and deployment » → **Source**, choisis **Deploy from a branch**.
4. Sous **Branch**, choisis `main` et le dossier `/ (root)`, puis **Save**.
5. Attends une à deux minutes : GitHub affiche en haut de la page l'URL de ton site, du type :
   `https://TON-PSEUDO.github.io/voltaire-entrainement/`

Ton site est en ligne et accessible depuis n'importe quel appareil.

## Mettre à jour le site plus tard

Si tu me redemandes des modifications sur le fichier, il suffira de re-uploader le nouveau `index.html` sur GitHub (même méthode qu'à l'étape 2 : **Add file → Upload files**, en remplaçant l'ancien) — la page se met à jour automatiquement en quelques minutes.

## Remarque sur la progression

Comme la progression est stockée dans le navigateur (localStorage), elle est **propre à chaque navigateur/appareil** utilisé pour ouvrir le site en ligne — elle ne se synchronise pas automatiquement entre ton ordinateur et ton téléphone, par exemple.
