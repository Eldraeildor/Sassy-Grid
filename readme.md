# Sassy Grid
Sassy Grid is a really minimalistic and easy to use CSS Grid System.
In order to use sassy-grid in your projects, you must have http://sass-lang.com currently installed on your computer.

## English
### Usage
Using sassy-grid is really simple, just include the following line of code into your SCSS file.

```scss
@import 'path/to/sassy-grid/grid';
```

Right after this simple import, create your sassy grids.
The `grid()` function takes 4 parameters :
```scss
$pref      // The class prefix (must be a string) used for the grid system
$cols      // The number of columns (must be an integer) for the grid system
$gutt      // The width of the gutter (pixels, em, etc...) between each column
$row-name  // The class used for the clearfix element (like the 'row' class in bootstrap)
```

## French
### Utilisation
L'utilisation de sassy-grid est très simple, il suffit d'inclure la ligne de code suivante dans votre fichier SCSS.

```scss
@import 'path/to/sassy-grid/grid';
```

Juste après cet import, vous pouvez commencer à créer vos grilles.
La fonction `grid()` prend en compte 4 paramètres :
```scss
$pref      // Le préfixe des classes (chaîne de caractères) utilisé pour le système de grille
$cols      // Le nombre de colonnes (nombre entier) de la grille
$gutt      // La largeur de la gouttière entre les différentes colonnes (pixels, em, etc...)
$row-name  // La classe utilisée pour l'élément de 'clearfix' (comme la classe 'row' de bootstrap)
```