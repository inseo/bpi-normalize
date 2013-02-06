#bpi-normalize
Le dépôt bpi-normalize regroupe les styles d'uniformisation détaillés dans le livre [Intégration web - les bonnes pratiques](http://www.eyrolles.com/Informatique/Livre/integration-web-les-bonnes-pratiques-9782212133707) publié aux Éditions Eyrolles.

##Styles d'uniformisation
Les styles d'uniformisation proposés ici sont une version personnalisée du projet `normalize.css` conçu par Nicolas Gallagher et Jonathan Neal. Ils sont agrémentés de notes et de références complémentaires, et ont été nettoyés des règles relatives aux balises de structure HTML5 (dont l'utilisation me semble encore trop prématurée à l'heure actuelle).

Les hacks destinés à IE 6 et 7 ont été remplacés par des classes conditionnelles. Pour en savoir plus quand à leur mise en place, vous pouvez vous référer au dépôt [bpi-html](https://github.com/inseo/bpi-html).

##Détail des fichiers
Le fichier d'uniformisation est disponible en trois versions distinctes :

* `normalize.css` uniformise les styles sur les navigateurs modernes, à savoir :
  * Chrome
  * Firefox 4+
  * Opera 12+
  * Safari 5+
  * Internet Explorer 8+
* `normalize-ie7.css` uniformise les styles sur IE 7 et les navigateurs suivants :
  * Chrome
  * Firefox 3+
  * Opera 10+
  * Safari 4+
* `normalize-ie6.css` uniformise les styles sur IE 6 et les navigateurs suivants :
  * Chrome
  * Firefox 3+
  * Opera 10+
  * Safari 4+

##Effets
Les styles d'uniformisation permettent de:

* Conserver les styles navigateurs, à l'inverse des `reset` usuels ;
* Uniformiser les styles par défaut de nombreux éléments ;
* Corriger les incohérences et les bogues de rendu entre les différents navigateurs ;
* Améliorer l'utilisabilité de certains éléments grâce à quelques ajouts spécifiques.

##Utilisation
Ces styles sont à placer avant toute autres instruction CSS et peuvent être customisés ou surchargés selon les besoins.