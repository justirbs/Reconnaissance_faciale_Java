# Reconnaissance faciale par Analyse en Composantes Principales : Livrable 3

## Introduction

Afin de visualiser la mise en page de ce document, il est conseillé de l'ouvrir avec un logiciel qui interprète le markdown.

## Description

Dans ce livrable nous avons implémenté l'interface utilisateur. Ainsi vous pouvez visualiser  :
- les cinq premiers eigenfaces
- l'image moyenne
- l'évolution de l'erreur lors de la reconstruction de limage de votre choix
- le test de reconnaissance de l'image de votre choix


## Manuel d'utilisation


Pour lancer le programme il faut avoir télécharger le dossier openjfx-18_linux-x64_bin-sdk
(https://gluonhq.com/products/javafx/)

Puis, il faut ouvrir un terminal à la racine du projet et saisir la commande suivante :

``` bash
java -jar --module-path /home/"votreCheminJusquaCeDossier"/openjfx-18_linux-x64_bin-sdk/javafx-sdk-18/lib --add-modules javafx.controls,javafx.fxml groupe10Livrable3.jar
```

Exemple :

``` bash
java -jar --module-path /home/cytech/Cours/ING1/ProgJava/IHM/openjfx-18_linux-x64_bin-sdk/javafx-sdk-18/lib --add-modules javafx.controls,javafx.fxml groupe10Livrable3.jar
```

Dans ce cas, le dossier openjfx-18_linux-x64_bin-sdk se trouve dans les répertoires /home/cytech/Cours/ING1/ProgJava/IHM/
