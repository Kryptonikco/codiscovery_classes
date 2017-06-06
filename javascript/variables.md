# Les variables

La variable est un concept commun en programmation.
La variable est une référence à une valeur. Cette valeur peut être de plusieurs types.

Voici un exemple simple :

```js
let name = 'Emma';
console.log(`Hello ${name}`); // returns: Hello Emma
name = 'Liam';
console.log(`Hello ${name}`); // returns: Hello Liam
```

⚠️ Quand on stocke une valeur texte (que l'on appelle "chaîne de caractères" en programmation, ou `string` pour faire simple), le texte sera TOUJOURS entouré de guillemets.

On peut y stocker des chiffres :

```js
const applesPrice = 3;
const applesNumber = 4;

console.log(applesPrice * applesNumber); // returns: 12 
```

En JavaScript, une variable peut stocker tous types d'objets : chaînes de caractères `string`, nombres `number`, des objets litéraux `object`, des tableux associatifs `array` ou des fonctions `function`, etc...  

## const vs. let

En JavaScript ES6, on distinguera les variales fixes (`const`) et les variables que l'on peut modifer `let`