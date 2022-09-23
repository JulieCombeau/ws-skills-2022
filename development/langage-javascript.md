# Langage Javascript

> ❌ A travailler

> ✔️ Auto validation par l'étudiant

## 🎓 J'ai compris et je peux expliquer

- les `structures` de base du langage ✔️
  Le langage Javascript se décompose en deux ensembles de types de données : les valeurs primitives (données immuables comme les boolean, les nombres, les chaine de caractère, etc) puis les objets

- les normes `ecmascript` ✔️
  C'est un ensemble de normes qui concerne tout les langages de type "script" développé par Ecma International. Actuellement les navigateurs récents supportent la version au minimum la version ES5.

- l'utilisation de l'`asynchrone` ✔️
  Rendre une fonction asynchrone permet d'attendre une réponse avant de "lire" les lignes suivantes. Cela va notamment permettre de faire de la gestion d'erreur sur des requetes par exemple.
  Elles peuvent être définies par le couple ".then().cath()" ou les mots clés "async/await" suivi du couple "try {} catch{}"

- les spécifités du mot-clef `this`✔️
  Vu surtout dans le context des "Classes" au sein d'un constructeur en javascript.

## 💻 Je code en Javascript

### Un exemple de code commenté ✔️

Exemple d'une fonction pour un algo

```javascript
function findAdults(arr) {
  let female = [];
  let male = [];
  for (let i = 0; i < arr.length; i++) {
    if (arr[i].sex === "female" && arr[i].age > 18) {
      female.push(arr[i]);
    } else if (arr[i].sex === "male" && arr[i].age > 18) {
      male.push(arr[i]);
    }
  }
  let adult = [female, male];
  return adult;
}
```

### Utilisation dans un projet ✔️

[lien github](https://github.com/WildCodeSchool/2022-03-JS-RemoteFR-TeamKarma-P3-Habble)

Description :

### J'ai utilisé ce langage en production ❌

[lien du projet](...)

Description :

### J'ai utilisé ce langage en environement professionnel ❌ / ✔️

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
