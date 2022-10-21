# GraphQL

> ❌ A travailler

> ✔️ Auto validation par l'étudiant

## 🎓 J'ai compris et je peux expliquer

- la différence entre REST et GraphQL ✔️
  L'interet de Graphql est de pouvoir obtenir toutes les informations nécessaires en une seule requête. Cela améliore également la performance.
- les besoins auxquels répond GraphQL ✔️
  - Chargement plus efficace des données notamment pour les mobiles
  - Récupération exacte des données dont le client a besoin
- la définition d'un schéma ✔️
  Le schéma est utilisé pour définir comment le client accède aux données
- Query ✔️
  La query est une requête de lecture
- Mutation ✔️
  La mutation est une requête d'écriture

- Subscription ❌

## 💻 J'utilise

### Un exemple personnel commenté ✔️

```javascript
    @Query(() => [Wilder])
    async wilders(): Promise<Wilder[]> {
        const wilders = await datasource.getRepository(Wilder)
        .find({ relations: { grades: { skill: true } } });

      return wilders.map((w) => ({
        ...w,
        skills: w.grades.map((g) => ({
          id: g.skill.id,
          name: g.skill.name,
          votes: g.votes,
        })),
      }));
    }
```

### Utilisation dans un projet ❌

[lien github](...)

Description :

### Utilisation en production si applicable❌

[lien du projet](...)

Description :

### Utilisation en environement professionnel ❌

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
