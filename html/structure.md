# La structure d'une page HTML

HTML est l'abbréviation de l'anglais HyperText Markup Language.

Une page HTML bien construite aura les éléments suivants :

- un doctype
- un élément `html`
- un `head`
- et un `body`

```html
<!DOCTYPE html>
<html>
  <head>
    ...
  </head>
  <body>
    ...
  </body>
</html>
```

Dans chacun de ces éléments, il y en a d'autres spécifique.

## Doctype

Le doctype est une balise qui permet de connaître la version d'HTML utilisé par la page.

En HTML 5, on utilisera :

```html
<!DOCTYPE html>
```

## Elément HTML

Cet élément est obligatoire pour la création de votre page. Il contient uniquement les balises `head` et `body`.

## Elément `head`

Cet élément contient tous les éléments non visible dans votre page et qui serviront à définir le titre, le style et les scripts utilisés dans toute la page.

## Elément `body`

Cet élément est la partie visible de la page. Il contient le texte, les liens, les images, les formulaires et boutons que vous utiliserez.