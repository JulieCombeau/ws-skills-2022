# REST API

> ❌ A travailler

> ✔️ Auto validation par l'étudiant

## 🎓 J'ai compris et je peux expliquer

- les verbes HTTP ✔️
  GET : lire
  POST : créer
  PUT / PATCH : mettre à jour
  DELETE : suprimmer

- les statuts HTTP ✔️
  Il existe plusieurs types de status définis par des codes. Les principales etant : - les 200 : code de succès (200 : ok) - les 400 : erreur coté client (404 : not found) - les 500 : erreur coté serveur (500 : Internal Server Error)

- les endpoints ❌

- CORS ❌

- la nomenclature recommandée pour les routes ✔️
  Les routes ont généralement la nomenclature suivante :
  - la constante correspondante à l'application (App ou router si fichier de route)
  - le verbe http
  - le chemin d'accès (par quel url)
  - la méthode du controleur associé à la requete

## 💻 J'utilise

### Un exemple personnel commenté ✔️

```javascript
router.post("/users", UserController.createOne);
router.get("/users", UserController.getAll);
router.get("/users/:userId", UserController.getOne);
router.put("/users/:userId", UserController.updateOne);
router.delete("/users/:userId", UserController.deleteOne);
```

### Utilisation dans un projet ✔️

[lien github](https://github.com/JulieCombeau/WNS_Livecoding)

Description :

### Utilisation en production si applicable❌ / ✔️

[lien du projet](...)

Description :

### Utilisation en environement professionnel ❌ / ✔️

Description :

## 🌐 J'utilise des ressources

### Titre

- lien
- description

## 🚧 Je franchis les obstacles

### Point de blocage ❌ / ✔️

Description:

Plan d'action : (à valider par le formateur)

- action 1 ❌ / ✔️
- action 2 ❌ / ✔️
- ...

Résolution :

## 📽️ J'en fais la démonstration

- J'ai ecrit un [tutoriel](...) ❌ / ✔️
- J'ai fait une [présentation](...) ❌ / ✔️
