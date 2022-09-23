# Titre de la compétence

> ❌ A travailler

> ✔️ Auto validation par l'étudiant

## 🎓 J'ai compris et je peux expliquer

- l'état (_state_) pour contrôler l'affichage d'un composant ✔️
  Utilisé avec le hook "useState()", cela permet de garder la valeur d'une variable entre deux appels de fonctions.
  Format :

```javascript
const [maVariable, setMaVariable] = useState();
```

- les composants enfants et les _props_ qu'on leur passe ✔️
  React se divise en plusieurs composants et sous-composants.
  Le passage de props (de parents à enfants seulement) permet de récupérer des données (variables, fonctions, etc...) afin de les réutiliser dans le composant enfant sans avoir besoin de les redéfinir.

- le déclenchement d'instructions en fonction des actions de l'utilisateur ✔️
  Des fonctions peuvent etre déclanchées par action de l'utilisateur (click sur un bouton, écriture dans un input, etc)

- le déclenchement d'instructions en fonction de l'étape du cycle de vie du composant ou du changement de valeur de ses props ✔️
  Pour cette action on utilise le hook "useEffect" qui permet un rechargement du component (et donc des données contenues dans la page).
  Si le tableau de dépendance est vide ce qui est contenu dans la fonction sera exécuté une fois au montage du component (au premier chargement)
  Si le tableau de dépendance contient une variable ce qui est contenu dans la fonction sera exécuté à chaque mofification de cette variable

- l'usage d'un reducer (_useReducer_) pour gérer un état composé dans un composant ❌
  Pas suffisamment utilisé pour être à l'aise avec ce hook qui est similaire au useState mais en gerant des états plus complexes

- l'état stocké dans un composant avec un _context provider_ et accessible dans ses descendants via `useContext`✔️
  Permet de rendre accessible dans tout le site un state par exemple sans avoir à le passer en props du composant parent à l'enfant

## 💻 J'utilise

### Un exemple personnel commenté ❌ / ✔️

### Utilisation dans un projet ❌ / ✔️

[lien github](https://github.com/JulieCombeau/Checkpoint4)

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
