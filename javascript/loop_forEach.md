# La boucle `forEach`

La boucle est un concept commun en programmation.
La boucle est une instruction qui se répète jusqu'à ce que la condition soit remplie.

La méthode (fonction) `forEach` n'existe que sur un objet de type `array` (tableau). Et elle se répète jusqu'à ce que tous les éléments du tableau soient traversés. `forEach` prend en paramètre une fonction qui aura comme paramètre l'élément courant et l'index de l'élément courant.

La syntaxe du `forEach` est la suivante : 

```js
const array = [];
array.forEach((el, index) => {
  // code
});
``` 

Voici un exemple simple :

```js
const names = ["Freya", "Finley", "Alice", "William"];
names.forEach((name) => {
  console.log(name);
});
```

On peut aussi en profiter pour transformer l'objet :

Exemple :

```js
const names = ["Freya", "Finley", "Alice", "William"];
names.forEach((name) => {
  console.log(name.toUpperCase());
});
```


La boucle `forEach` peut utiliser plusieurs instructions dans la fonction.

