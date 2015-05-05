# Flexbox Grid.
Flexbox Grid est un système de grille complet en CSS. Il utilise les flexbox layout ce qui lui permet une meilleure gestion des positionnements. Il est compatible IE 10+, ce qui lui permet de s'implémenter dans des projets de plus en plus vaste.


## Installation
```html
<link rel="stylesheet" href="https://rawgit.com/w-jerome/flexbox-grid/master/src/flexbox-grid.min.css">
```

## Introduction
Flexbox Grid utilise les classes pour se structurer. Les classes sont nommé sans abréviations, ce qui permet pour un nouvel utilisateur de comprendre plus facilement l'utilisation de l'outil.

Il utilise toujours le plus petit écran renseigné comme point de départ, par exemple si une colonne n'a que la classe `small-6` il va l'appliquer sur tous les écrans, cela évite d'écrire `small-6 medium-6 large-6 xlarge-6 xxlarge-6`

Les points de rupture (breakpoints) sont ceux utilisé par Foundation :

    small   : all screen
    medium  : min-width 641px
    large   : min-width 1025px
    xlarge  : min-width 1441px
    xxlarge : min-width 1921px

## Premier pas

Pour le système de grille est similaire aux autres frameworks

### Basique

```html
<div class="row">
    <div class="column small-3">
        column small-3
    </div>
    <div class="column small-3">
        column small-3
    </div>
    <div class="column small-3">
        column small-3
    </div>
    <div class="column small-3">
        column small-3
    </div>
</div>
```

Il est important de noter que par défaut si une colonne n'a plus de place, elle va automatiquement se placer sur une nouvelle ligne. Il n'y a donc pas besoin d'attribuer de classe `end` une fois que la `row` est pleine.

Par ailleurs, si la `row` n'est pas pleine, elle ne va pas s'étendre dans le reste de la ligne et restera aligné à gauche.

#### Sans gouttières

Par défaut une gouttière de 1em est attribuée, mais il est possible de supprimer cette gouttière sur l'ensemble des colonnes ou sur une seule en particulier, l'inverse est également possible :

```html
<div class="row no-gutter">
    <div class="column small-3">
        small-3
    </div>
    <div class="column small-3 no-gutter">
        small-3  no-gutter
    </div>
    <div class="column small-3 gutter">
        small-3 gutter
    </div>
    <div class="column small-3 gutter">
        small-3 gutter
    </div>
</div>
```


### Alignement horizontal

Par défaut, les colonnes sont aligné à gauche, mais il est possible de les centrer ou de les aligner à droite avec les classe `content-left`, `content-center` et `content-right` (à appliquer sur la `row`) :

```html
<div class="row content-center">
    <div class="column small-3">
        small-3
    </div>
    <div class="column small-3">
        small-3
    </div>
</div>
```
