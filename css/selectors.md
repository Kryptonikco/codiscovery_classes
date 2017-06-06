# Les sélecteurs

Les sélecteurs CSS, comme leur nom l'indique, permettent de sélectionner un ou plusieurs éléments HTML afin de leur appliquer un style.
Le style s'appliquera entre les chevrons.


Pour sélectionner toutes les `div` d'une page, on va utiliser :

```css
div {
  /* styles */
}
```

On peut aussi sélectionner l'élément à partir de son attribut.

Pour récupérer un élément HTML avec l'id "logo", on utilisera le dièse `#` (ça s'appelle un dièse et pas un hashtag) :

```html
<img id="logo" />
```

```css
#logo {

}
```

Peu importe l'élément, `div`, `p`, etc... le sélecteur sera sur l'id.

N.B : En HTML, l'id est supposé être unique.

Pour sélectionner plusieurs éléments spécifiques, on sélectionnera l'attribut HTML `class` avec le point `.` :

```html
<p class="promotion">
  Article 1
</p>
<p>
</p>
<p class="promotion">
</p>
```

```css
.promotion {

}
```

# Les pseudo sélecteurs

Pour sélectionner le moment où l'on passe la souris sur un élément, on utilisera le pseudo sélecteur `:hover`.

```css
a:hover {
  color: red;
}
```