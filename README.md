# Flag Application avec React

**Auteur** :

- Tuilier Thomas

## Description du site

Ce site est un projet d'entraînement sur React. C'est une application vitrine issue du cours de _From Scratch_ qui fonctionne en NoSQL (ie : sans une base de données), créé avec `json-server` et qui tourne avec la commande :

```
json-server --w src/assets/db.json --port 3004
```

Par rapport au cours original, certaines modifications ont été effectuées. On peut citer :

- Ce projet a une structure React créée via Vite et non par `react-router-dom`.
- TODO : La page d'accueil du cours a été mise dans la page `Liste des drapeaux`.
- TODO : La page d'accueil présentée ici n'existe normalement pas dans le cours.

## Lancer l'application

Pour lancer l'application il faut lancer le script du back-end dans un premier terminal avec :

```
npm run server
```

Et lancer dans un deuxième terminal :

```
npm run dev
```
