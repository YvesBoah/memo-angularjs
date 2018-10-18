# ma mémoire angular js 

* le ng-model permet de reférencer un champ dans le but de pouvoir récupérer sa valeur en l'appelant ailleurs.
   * Exemple : Nom ` <br> `
	    ` input type="text" ng-model='nom' {{nom}} ` j'ai retirer les balises exprès !!!

	    ** ce code permet d'afficher la valeur saisie dans l'input ce mécanisme est appellé data binding **

* Le séparateur de milliers  : 
    * {{ V.prix | number : fractionSize }}

        ** V.prix symbolise le montant
*