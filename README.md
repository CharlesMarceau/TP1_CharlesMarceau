TP1_CharlesMarceau

==================

#TP1_Animation.css

`TP1_Animation.css` est une série d'animations CSS simple d'utilisation.

##Usage
Pour utiliser la librairie d'animation CSS, vous n'avez qu'à insérer le "id" et la "class" de votre choix qui sont alliés (#oscilloscope ET .bip / #pow ET .pop / #feuille ET .vent / #horloge ET .aiguille / #animBond1 ET .pointRotation AINSI QUE .balle ( pour ajouter l'effet de rebondissement, vous devez aussi inclure :  #animBond2 ET .pointRotation2 AINSI QUE .balle2 ) tout cela dans les balises `<div>` inclu dans le `<body>` de votre fichier html. Voici comment procéder pour que la librairie soit fonctionnelle ; ( vous pouvez tout aussi bien glisser le fichier de l'endroit où il a été enregistré vers les balises `<head>`et `</head>`) Ex:

```html
<head>
  <link rel="stylesheet" href="animation_lib_MarceauCharles.css">
</head>
```

Pour effectuer des changements d'animation, vous pouvez changer la durée de temps(secondes) d'animation, le délai en temps(secondes) avant le début de l'animation et le nombre de répétition désiré.

```css

/*animation: nomKeyframes durée-animation durée-délai-départ répétition direction*/
#nomElement {
  animation: battement 4s 0s infinite linear;
  }
```

*Note: Soyez certain d'insérer les préfixes correspondant pour que le tout soit fonctionnel dans les navigateurs principaux d'internet  (-webkit-, -moz-, -ms- et -o-)*
 
