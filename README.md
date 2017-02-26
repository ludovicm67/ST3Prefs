Mes préférences pour Sublime Text 3
===================================

Ce dépôt me permet de récupérer très rapidement mes réglages pour [Sublime Text 3](http://www.sublimetext.com/3), et me permet de gagner pas mal de temps, en m'évitant de tout reconfigurer à chaque fois que je souhaite utiliser ST3 sur un autre appareil. Si vous le souhaitez, vous peuvez en profiter pour avoir les mêmes préférences, si elles vous conviennent, et vous êtes libres de personnaliser le tout selon vos envies !

## Mise en place :
 * Rendez-vous dans le dossier **User** du dossier **Packages**.
 * Ouvrez un terminal et entrez la commande git suivante : `git clone http://github.com/ludovicm67/ST3Prefs.git .`
 * Installez le [Package Control](https://packagecontrol.io/installation), pour que les extensions s'installent automatiquement
 * Ouvrez Sublime Text et attendez quelques secondes
 * That's it !
 * ...et pour rester à jour, faites régulièrement un `git pull` :wink:

## Mes snippets :

### C

 * `dg + TAB` => Commentaires Doxygen pour fonction
 * `dgi + TAB` => Commentaires Doxygen pour fichier

### CSS

 * `** + TAB` => Reset minimaliste + règles de base en CSS

### HTML

 * `html5 + TAB` => Génération d'une page HTML5 basique

### Java

 * `main + TAB` => méthode main
 * `pc + TAB` => base pour une classe publique
 * `sop + TAB` => `System.out.println("")`

### JavaScript

Raccourcis permettant d'écrire des éléments assez longs, et qu'on a souvent besoin :

 * `ael + TAB` => `addEventListener(...)` 
 * `ac + TAB`  => `appendChild()`
 * `ce + TAB`  => `createElement('')`
 * `cl + TAB`  => `console.log()`
 * `dd + TAB`  => `document.`
 * `ih + TAB`  => `innerHTML`
 * `qs + TAB`  => `querySelector('')`
 * `qsa + TAB` => `querySelectorAll('')`

### PHP

 * `cl + TAB` => Permet de générer le squelette d'une classe PHP, gain de temps non négligeable !

### Autres

 * `cc + TAB` => Permet d'insérer un commentaire dans du code PHP ou JavaScript (même fonctionnement que `/**+TAB`)

## Raccourcis

 * `CTRL + ALT + A` => Utilise Alignment pour aligner certains éléments
 * En appuyant sur `F4` dans une classe PHP, cela va ajouter le bon namespace en haut du fichier
 * En appuyant sur `F5` en ayant le curseur sur le nom d'une classe PHP, cela va ajouter un `use` en début de fichier
 * En appuyant sur `F6` en ayant écrit le nom d'une classe, ça va compléter avec le chemin complet
 * En appuyant sur `MAJ+F6` en ayant écrit le nom d'une classe, ça va compléter avec le chemin complet, en commençant par `\`
 * En appuyant sur `F7` ça va ajouter un nouvel attribut à la classe PHP, en ajoutant automatiquement au constructeur un argument supplémentaire
 * `MAJ+F12` sur une méthode PHP pour tomber sur sa définition


N'hésitez surtout pas à utiliser et à personnaliser ces préférences à votre convenance !
