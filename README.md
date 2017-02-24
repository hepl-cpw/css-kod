# CSS «&nbsp;Kòd&nbsp;»

> CSS exercise given at HEPL

* * *

**CSS "Kòd"** is an educational project, which will be used for `HTML`/`CSS` courses.

**Note:** the school where the course is given, the [HEPL](http://www.provincedeliege.be/hauteecole) from Liège, Belgium, is a french-speaking school. From this point, the instruction will be in french. Sorry.

* * *

> Lors de vos labos de *travaux dirigés*, vous allez découvrir le langage CSS et le mettre en pratique via de courts exercices de mise en situation.  
> Les labos de *travaux pratiques* vont vous confronter à des exercices pratiques et individuels reprenant la matière vue lors du TD précédent.

* * *

## Kòd

Vous trouverez dans ce dossier une page HTML nommée **index.html**. Cette page contient un petit extrait de code concernant les microdatas.  

Toutefois, le formatage HTML fourni ne permet pas l’affichage de l’extrait de code… Vous allez donc devoir commencer par régler ce problème. 

Ensuite, vous allez créer quatre feuilles de style pour permettre d’afficher l’extrait de code selon quatre thèmes de couleur différents.

Les différents styles devront être accessibles depuis le menu *Affichage* du navigateur pour que l’utilisateur puisse choisir son thème préféré&nbsp;:

![Rendu de la page avec CSS](rendu1_Light.png "rendu avec CSS (light) de la solution")

### Consignes

#### 1. Préparer le HTML&nbsp;:

- pour que l’extrait de code s’affiche dans le navigateur&nbsp;;
- pour pouvoir styler les morceaux de code. Prévoir de pouvoir appliquer&nbsp;:
	- un style pour les noms de balise&nbsp;;
	- un style pour les noms d’attributs&nbsp;;
	- un style pour les valeurs d’attributs&nbsp;;
- pour lier les quatre feuilles de style pour les 4 thèmes de couleur différents et avoir accès aux trois feuilles de style alternatives via le menu Affichage -> Style de la page du navigateur. [Aide : les feuilles de style alternatives doivent être liées grâce à une balise `link` dont l’attribut rel a la valeur `alternate stylesheet`. Le nom des feuilles de style qui apparaît le menu du navigateur est ajouté grâce à l’attribut title].

N.B. L’extrait de code doit&nbsp;:

- être balisé comme étant du code&nbsp;
- s’afficher en conservant le formatage réalisé dans l’éditeur de texte&nbsp;;
- se trouver dans une figure de classe `code`.


#### 2. Créer les 4 feuilles de style en CSS :

##### Styles généraux

- Appliquer un reset de base&nbsp;: 

        * {   
            padding: 0;  
            margin: 0;  
	    }
	
- Appliquer au `body`&nbsp;:
	- des marges intérieures de 2 fois la taille de la police à gauche et à droite&nbsp;;
	- des marges extérieures de 2 fois la taille de la police en haut et en bas&nbsp;;
	- une largeur maximum de 1000px&nbsp;;
	- la police *Helvetica Neue* de préférence (et sinon une police de substitution bien choisie) [Aide-rappel : voir sur le site *csssfontsack*]&nbsp;;

- Le titre doit avoir&nbsp;:
	- une taille de police 3 fois plus grande que la taille de base&nbsp;;
	- des marges extérieures de 1.5 fois la taille de la police en haut et 0.8 fois la taille de la police à gauche&nbsp;;
	- une hauteur de ligne de 1.3 fois la taille de la police&nbsp;;
	
- La figure qui contient le code (`figure.code`) doit avoir&nbsp;:
	- une taille de police de 1.5 fois la taille de la police de son parent&nbsp;;
	- une hauteur de ligne de 1 fois la taille de la police&nbsp;;
	- une marge du bas de 3 fois la taille de la police&nbsp;;
	- une bordure à gauche de 0.5 fois la taille de la police en trait plein et de couleur `#ad5dff`&nbsp;;
	- une marge intérieure de 1 fois la taille de la police&nbsp;;
	- pas de retour à la ligne automatique&nbsp;;
	- être écrit de préférence en *Consolas* (et sinon avec une police de substitution bien choisie).

##### Thème clair (*Light*, affiché par défaut) 

![Rendu de la page avec CSS](rendu1_Light.png "rendu avec CSS (light) de la solution")

Couleurs&nbsp;:

- fond&nbsp;: blanc `#fff`&nbsp;;
- titre&nbsp;: gris `#666`&nbsp;;
- balise, bordure&nbsp;: bleu `#006699`&nbsp;;
- attribut&nbsp;: orange `#a46100`&nbsp;;
- valeur&nbsp;: vert `#567c00`&nbsp;;
- texte&nbsp;: noir `#000`.


##### Thème clair solarisé (*Solarized Light*)

![Rendu de la page avec CSS](rendu2_Solarized_Light.png "rendu alterné avec CSS (solarized light) de la solution")

Couleurs&nbsp;:

- fond&nbsp;: crème `#fff4db`&nbsp;;
- titre, bordure&nbsp;: bleu-vert `#009786`&nbsp;;
- balise&nbsp;: bleu `#0079cb`&nbsp;;
- attribut&nbsp;: vert `#698c00`&nbsp;;
- valeur&nbsp;: orange `#b67400`&nbsp;;
- texte&nbsp;: noir `#OOO`.


##### Thème foncé (*Dark*)

![Rendu de la page avec CSS](rendu3_dark.png "rendu alterné avec CSS (dark) de la solution")

Couleurs&nbsp;:

- fond&nbsp;: gris foncé `#1d1e19`&nbsp;;
- titre, bordure&nbsp;: mauve `#ad5dff`&nbsp;;
- balise&nbsp;: rose `#ff005e`&nbsp;;
- attribut&nbsp;: bleu-vert `#00d8ed`&nbsp;;
- valeur&nbsp;: vert `#72e600`&nbsp;;
- texte&nbsp;: `#f6f7ee`.

##### Thème foncé solarisé (*Solariezd Dark*)

![Rendu de la page avec CSS](rendu4_dark_solarized.png "rendu alterné avec CSS (solarized dark) de la solution")

Couleurs&nbsp;:

- fond&nbsp;: `#002129`&nbsp;;
- titre&nbsp;: mauve `#5658ba`&nbsp;;
- balise&nbsp;: orange  `#b67400`&nbsp;;
- attribut&nbsp;: vert  `#698c00`&nbsp;;
- valeur&nbsp;: turquoise `#009786`&nbsp;;
- texte&nbsp;: `#688384`.

* * *

Bon travail&nbsp;!

* * *

Code original par [Myriam Dupont](https://github.com/myriamdupont).
