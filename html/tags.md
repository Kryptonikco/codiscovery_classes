# Les balises, les attributs et les éléments

## Les balises

Une balise est un mot clé qui sera entouré de chevrons à l'ouverture et la fermeture.
La balise de fermeture contiendra un slash.
A l'intérieur d'une balise, il est possible d'y mettre du texte ou d'autres balises.

La balise a pour but de structurer votre page. Chaque balise a un sens précis.

Un exemple avec la balise `div` :

```html
<div>
  <p>text</p>
</div>
```

### Les balises auto-fermantes

Les balises auto-fermantes sont des balises qui n'acceptent rien à l'intérieur.
Le slash se mettra avant le chevron de fermeture.

Exemple :

```html
<hr />
<img />
```

## Les attributs

Les attributs ajoutent des informations complémentaires à la balise.

Ils sont déclarés dans la balise ouvrante.

La syntaxe est la suivante :

```html
<div nom="valeur">
</div>
```

Les `nom`s de l'attribut sont variés. Les plus communément utilisés sont :

- `class` (pour attacher une classe CSS)
- `id` (pour attacher un ID CSS)
- `href` (pour lier à une ressource - un lien web par exemple)
- `src` (pour lier à une ressource binaire - une image par exemple)
- etc...

Pour chaque nom d'attribut, la valeur est différente et spécifique



## Les éléments

C'est tout ce qui se trouve entre dans les balises :

- attributs
- texte
- et autres balises imbriquées

```html
<body>
  <h1>Bonjour !</h1>
  <div>
    <p>Je m'appelle Gaston</p>
    <p>J'ai 23 ans</p>
  </div>
</body>
```

L'élément `div` contient les 2 paragraphes.
Et l'élément `body` contient tous les éléments

