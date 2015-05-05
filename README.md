### Flexbox Grid.
Flexbox Grid est un système de grille complet en CSS. Il utilise les flexbox layout ce qui lui permet une meilleure gestion des positionnements. Il est compatible IE 10+, ce qui lui permet de s'implémenter dans des projets de plus en plus vaste.


### Installation
```html
<link rel="stylesheet" href="https://rawgit.com/w-jerome/flexbox-grid/master/src/flexbox-grid.min.css">
```

### Introduction
Flexbox Grid utilise les classes pour se structurer. Les classes sont nommé sans abréviations, ce qui permet pour un nouvel utilisateur de comprendre plus facilement l'utilisation de l'outil.

Il utilise toujours le plus petit écran renseigné comme point de départ, par exemple si une colonne n'a que la classe `small-6` il va l'appliquer sur tous les écrans, cela évite d'écrire `small-6 medium-6 large-6 xlarge-6 xxlarge-6`

Les points de rupture (breakpoints) sont ceux utilisé par Foundation :

    small   : all screen
    medium  : min-width 641px
    large   : min-width 1025px
    xlarge  : min-width 1441px
    xxlarge : min-width 1921px

### Premier pas

Pour le système de grille est similaire aux autres frameworks

```html
<div class="row">
    <div class="column small-3">
        small-3
    </div>
    <div class="column small-3">
        small-3
    </div>
    <div class="column small-3">
        small-3
    </div>
    <div class="column small-3">
        small-3
    </div>
</div>
```

### Rather Drive Stick?
If you prefer to not use the automatic generator, push a branch named `gh-pages` to your repository to create a page manually. In addition to supporting regular HTML content, GitHub Pages support Jekyll, a simple, blog aware static site generator written by our own Tom Preston-Werner. Jekyll makes it easy to create site-wide headers and footers without having to copy them across every page. It also offers intelligent blog support and other advanced templating features.

### Authors and Contributors
You can @mention a GitHub username to generate a link to their profile. The resulting `<a>` element will link to the contributor's GitHub Profile. For example: In 2007, Chris Wanstrath (@defunkt), PJ Hyett (@pjhyett), and Tom Preston-Werner (@mojombo) founded GitHub.

### Support or Contact
Having trouble with Pages? Check out the documentation at https://help.github.com/pages or contact support@github.com and we’ll help you sort it out.
