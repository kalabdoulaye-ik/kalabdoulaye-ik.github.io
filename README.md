# Site web personnel — Abdoulaye Idrissa Kalidou

Site statique (HTML/CSS, sans framework) — fonctionne sur n'importe quel hébergement simple.

## Fichiers
- `index.html` — Accueil
- `cv.html` — CV détaillé
- `publications.html` — Publications & distinctions
- `contact.html` — Contact
- `styles.css` — Feuille de style partagée
- `assets/Abdoulaye_Kalidou_CV.pdf` — CV téléchargeable

## Reste à ajouter
Rien d'obligatoire — photo, galerie de conférences et LinkedIn sont déjà intégrés. Vous pouvez remplacer les photos à tout moment en glissant un nouveau fichier dans `assets/photos/` (gardez le même nom de fichier pour ne pas casser les liens, ou mettez à jour le `src` dans le HTML correspondant).

## Prévisualiser en local
Ouvrez simplement `index.html` dans un navigateur, ou lancez un petit serveur local :
```
python3 -m http.server 8000
```
puis ouvrez `http://localhost:8000`.

## Déployer sur GitHub Pages (gratuit)
1. Créez un dépôt GitHub, par exemple `abdoulaye-kalidou.github.io` (remplacez par votre nom d'utilisateur) — ce nom exact rend le site accessible directement à la racine.
2. Mettez tous ces fichiers à la racine du dépôt.
3. Dans les paramètres du dépôt (`Settings` → `Pages`), choisissez la branche `main` et le dossier `/root`.
4. Votre site sera en ligne à `https://VOTRE-NOM.github.io/` après quelques minutes.

Si vous préférez un nom de dépôt différent (ex. `mon-site`), le site sera accessible à `https://VOTRE-NOM.github.io/mon-site/`.
