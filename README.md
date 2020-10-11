INTRODUCTION
====

L'objectif de ce dépôt est de fournir une base JavaFx dans les environnement ne disposant pas de réseau.

Configuration
====

Dans le fichier *build.gradle*, modifier la variable *javafx.sdk* pour pointer sur le répertoire de votre SDK JavaFX.

Ajouter des cots
====

Ajouter des plugins gradle
----

Pour ajouter des plugins *gradle*, il faut se rendre à l'adresse suivante:

> [https://plugins.gradle.org/m2/](https://plugins.gradle.org/m2/)

Ensuite il faut se déplacer dans le répertoire contentant le *cots*, le télécharger, ainsi que le fichier portant l'extension *.pom* correspondant et reproduire la même arborescence dans le répertoire local *repo*.

Ajouter des dépendances
----

Pour ajouter des dépendances, il faut se rendre à l'adresse suivante:

> [https://repo1.maven.org/maven2/](https://repo1.maven.org/maven2/)

Ensuite il faut se déplacer dans le répertoire contentant le *cots*, le télécharger, ainsi que le fichier portant l'extension *.pom* correspondant et reproduire la même arborescence dans le répertoire local *repo*.

Installation
---
Une fois que les *cots* sont dans el répertoire *repo*, il faut lancer la commande **gradle run** pour lancer l'application.

Il se peut que les dépendances ou plugins installées nécessitent eux aussi d'autres dépendances, il faut allors utiliser la procédure précédente pour les installer.