# JSON

Abbréviation de l'anglais : JavaScript Object Notation

Le JSON est un format texte, proche de l'objet `object` en JavaScript dans sa syntaxe.

Voici un exemple : 

```js
{
  "person": {
    "name": "Olivia",
    "age": 23,
    "degrees": [
      "high school",
      "business school"
    ]
  }
}
```

`name` est la clé qui contient la valeur `Olivia`

Après avoir parsé le texte en JavaScript, on peut accéder aux valeurs du JSON de la valeur suivante :

```js
console.log(json.person.name); // returns: Olivia
console.log(json.person.age); // returns: 23
console.log(json.person.degrees[0]); // returns: high school
console.log(json.person.degrees[1]); // returns: business school

```