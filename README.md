# Mes fiches d'animation

Répertoire personnel d'activités et de jeux d'animation.
Une seule page web, consultable au téléphone sur le terrain, remplie au calme depuis l'ordinateur.

## Le fichier

Tout tient dans `index.html`. Pas d'installation, pas de logiciel à compiler.
Pour le modifier : ouvrez-le avec le Bloc-notes, tout ce qui vous concerne est
dans le grand encadré tout en haut du fichier.

| À modifier | Où |
|---|---|
| Le code d'accès | `const CODE_ACCES = 'anim2026';` |
| La base de données | `const CONFIG_FIREBASE = { ... }` |

Tant que la configuration Firebase n'est pas collée, l'application marche quand même,
mais en **mode local** : les fiches restent sur l'appareil utilisé, sans synchronisation.

## Règles de sécurité Firestore

Voir `firestore.rules`. À copier dans la console Firebase :
**Firestore Database → Règles**.

## Sauvegarde

Menu ☰ → « Télécharger une sauvegarde ». Cela produit un fichier `.json`
contenant toutes les fiches. À faire de temps en temps et à ranger avec vos documents.
Le même menu permet de restaurer ce fichier.
