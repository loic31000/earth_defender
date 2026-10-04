# Earth Defender

<p align="center">
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript">
  <img src="https://img.shields.io/badge/HTML5-Canvas-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5 Canvas">
  <img src="https://img.shields.io/badge/État-base%20pédagogique-lightgrey?style=for-the-badge" alt="Base pédagogique">
</p>

Fork pédagogique de [CHAOUCHI/earth_defender](https://github.com/CHAOUCHI/earth_defender).

## Contenu actuel

La branche `main` contient :

- une page `index.html` avec un élément `canvas` ;
- les images du joueur, de la Terre, des aliens, des lasers, des étoiles et des coeurs ;
- un fichier `tsconfig.json` configuré pour compiler `src/` vers `build/` ;
- un fichier `src/script.ts` actuellement vide.

La page HTML référence `./build/script.js`, mais le dossier `build/` n'est pas présent dans ce dépôt.

## État du projet

Cette branche correspond à une base de travail et n'est pas exécutable telle quelle dans son état actuel, car le script TypeScript source est vide et le JavaScript compilé référencé par la page n'est pas versionné.

La version développée et structurée du jeu se trouve dans :

[loic31000/Earth-Defender-Project](https://github.com/loic31000/Earth-Defender-Project)

## Stack vérifiable

- TypeScript configuré via `tsconfig.json` ;
- HTML5 avec Canvas ;
- assets graphiques locaux.
