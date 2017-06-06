# La structure CSS

Le CSS est une abbréviation de l'anglais Cascading StyleSheet.

Le style en cascade. C'est-à-dire que le style partira d'une source et redescendra sur tous les éléments sur son passage.

Au niveau de mon site, on appliquera un texte d'une taille de 30.
Au niveau de ma page, tous mes textes seront gras.
Au niveau d'un élément, le texte sera rouge.

Donc mon élément sera de taille 30, en gras et en rouge.

Pour appliquer du texte au niveau du site, on utilisera un fichier CSS externe qui peut être importé dans le `head` de plusieurs pages.
Au niveau de la page, on utilisera la balise `style` dans le `head` qui ne sera effective que sur la page.
Et sur un élément, on utilisera l'attribut `style` dans lequel on écrira dans propriété.

Voici comment illustrer notre [exemple](https://jsfiddle.net/Kryptonikco/ntgmh6cy/) :

Dans le fichier app.css :

```css
body {
  font-size: 30px;
}
```

Au niveau de la page et de l'élément :

```html
<html>
  <head>
    <style>
      body {
        font-style: bold;
      }
    </style>
  </head>
  <body>
    <p>hello</p>
    <p style="color: red;">text</p>
  </body>
</html>
```