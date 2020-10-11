INTRODUCTION
====

L'objectif de ce d�p�t est de fournir une base JavaFx dans les environnement ne disposant pas de r�seau.

Configuration
====

Dans le fichier *build.gradle*, modifier la variable *javafx.sdk* pour pointer sur le r�pertoire de votre SDK JavaFX.

Ajouter des cots
====

Ajouter des plugins gradle
----

Pour ajouter des plugins *gradle*, il faut se rendre � l'adresse suivante:

> [https://plugins.gradle.org/m2/](https://plugins.gradle.org/m2/)

Ensuite il faut se d�placer dans le r�pertoire contentant le *cots*, le t�l�charger, ainsi que le fichier portant l'extension *.pom* correspondant et reproduire la m�me arborescence dans le r�pertoire local *repo*.

Ajouter des d�pendances
----

Pour ajouter des d�pendances, il faut se rendre � l'adresse suivante:

> [https://repo1.maven.org/maven2/](https://repo1.maven.org/maven2/)

Ensuite il faut se d�placer dans le r�pertoire contentant le *cots*, le t�l�charger, ainsi que le fichier portant l'extension *.pom* correspondant et reproduire la m�me arborescence dans le r�pertoire local *repo*.

Installation
---
Une fois que les *cots* sont dans el r�pertoire *repo*, il faut lancer la commande **gradle run** pour lancer l'application.

Il se peut que les d�pendances ou plugins install�es n�cessitent eux aussi d'autres d�pendances, il faut allors utiliser la proc�dure pr�c�dente pour les installer.