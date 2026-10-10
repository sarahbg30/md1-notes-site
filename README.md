# Journal de bord — mettre le site en ligne

Le site tient en deux fichiers :

- `index.html` : la page (menu, calendrier, dates, sujets). Pas besoin d'y toucher.
- `notes.md` : vos notes. C'est le seul fichier à modifier.

Les visiteurs ne peuvent que lire. Ils n'ont besoin d'aucun compte.

## 1. Mettre le site en ligne (une seule fois)

1. Créez un compte gratuit sur https://github.com.
2. En haut à droite, cliquez sur **+** puis **New repository**.
   - Nom : par exemple `journal`.
   - Cochez **Public**.
   - Cliquez sur **Create repository**.
3. Sur la page qui s'ouvre, cliquez sur le lien **uploading an existing file**.
   Glissez `index.html` et `notes.md`, puis cliquez sur **Commit changes**.
4. Allez dans **Settings**, puis **Pages** dans le menu de gauche.
   - Sous « Branch », choisissez **main** et **/(root)**, puis cliquez sur **Save**.
5. Attendez une à deux minutes. L'adresse du site s'affiche en haut de cette page, par exemple
   `https://votre-nom.github.io/journal/`. C'est le lien à envoyer à vos profs.

## 2. Ajouter une note

1. Sur github.com, ouvrez votre dépôt `journal`, puis le fichier `notes.md`.
2. Cliquez sur l'icône crayon (**Edit this file**).
3. Ajoutez votre note en haut de la liste :

   ```
   ## 2026-10-10
   #cours #idées
   Le texte de la note.
   ```

   - 1re ligne : `##` puis la date au format année-mois-jour.
   - 2e ligne (facultative) : les sujets, chacun commence par `#`.
   - Ensuite : le texte, sur une ou plusieurs lignes.
4. Cliquez sur **Commit changes…**, puis encore sur **Commit changes**.

Le site se met à jour seul en une à deux minutes. Pour modifier ou supprimer une note, faites pareil : changez ou effacez son texte dans `notes.md`.

Ça marche aussi depuis un téléphone, dans le navigateur, sur github.com.

## Bon à savoir

- Si vous ouvrez `index.html` directement depuis votre ordinateur (double-clic), le navigateur bloque la lecture de `notes.md` et la page affiche « Les notes n'ont pas pu être chargées ». C'est normal : en ligne, ça fonctionne.
- Le site est public : toute personne qui a l'adresse peut lire les notes.
