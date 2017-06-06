# Les fonctions

La fonction est un concept commun en programmation.
La fonction est une partie du programme qui effectue une ou plusieurs tâches précises.

En JavaScript ES6, les fonctions seront déclarés de la manière suivantes :

```js
() => {}
```

Un exemple concret de fonction qui retournera le carré d'un nombre : 

```js
(num) => {
  return num * num;
}
```

La variable `num` entre les parenthèse est un paramètre.

Pour utiliser cette fonction, on la stocke dans une variable et on utilise les `()` pour l'appeler:

```js
const square = (num) => {
  return num * num;
};

console.log(square(2)); // returns: 4
console.log(square(3)); // returns: 9
``` 