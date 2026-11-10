# CampusCards

CampusCards est une petite application React Native réalisée dans le cadre du TP3. Elle présente les étudiants de la filière IAIL S5 sous forme de cartes.

## Objectif

Afficher les informations de quatre étudiants avec leur nom, leur filière, leur note et leur statut (Admis ou Ajourné). L'écran affiche également le nombre d'admis et la moyenne.

## Technologies utilisées

- React Native
- React
- TypeScript
- Expo

## Fonctionnalités réalisées

- Affichage des quatre étudiants : Amine, Sara, Lina et Youssef.
- Détermination automatique du statut Admis / Ajourné à partir de la note.
- Calcul du nombre d'admis et de la moyenne.
- Affichage dynamique des cartes avec `map()` et une clé stable.
- Organisation de l'interface avec Flexbox et `StyleSheet`.

## Installation et lancement

Depuis le dossier du projet :

```bash
npm install
npx expo start
```

Scanne ensuite le QR code affiché avec l'application Expo Go.
