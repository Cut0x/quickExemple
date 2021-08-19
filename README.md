# Quick.db c'est quoi ?
[Ce package est destiné à fournir un moyen simple de créer et d'utiliser une base de données, toutes les données sont stockées de manière persistante et sont livrées avec des fonctionnalités supplémentaires faciles à utiliser.](https://quickdb.js.org)
### Développé par [truexpixels](https://www.npmjs.com/~truexpixels) et [zorowastaken](https://www.npmjs.com/~zorowastaken).

# Comment l'installer ?
```
npm install quick.db --save
```
avec le code
```js
const db = require("quick.db");
```
pour appeler le module

# Comment bien l'utiliser ?
```js
// const Discord [...]
const db = require("quick.db");

// Ajouter une valeur numérique
db.add("utilisateur_monnaie", 2)

// Définir une valeur
db.set("utilisateur_bio", "Coucou, je suis Cut0x !")
db.set("utilisateur_bio", 5) // si l'utilisateur était à 10, il sera à 5 !

// Trouver une valeur
const bio = db.get("utilisateur_bio")
console.log(`Ma biographie: ${bio}`)
```
