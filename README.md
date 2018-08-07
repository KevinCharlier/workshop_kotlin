# workshop_kotlin

![Logo Laravel](kotlin.png)

## Introduction
### Qu'est-ce que Kotlin ?

***Définition:*** Kotlin est un langage de programmation orienté objet et fonctionnel, avec un typage statique qui permet de compiler pour la machine virtuelle Java et JavaScript.  
  
Avant Kotlin, Google ne supportait que le langage Java pour développer les fameuses applications que vous utilisez au quotidien. Kotlin ne nécessite en aucun cas de réécrire l’ensemble des applications. Il est tout à fait possible de faire cohabiter du code Java et du code Kotlin. On comprend aisément pourquoi Google a opté pour cette solution qui offre une transition en douceur. Kotlin est également un langage robuste et éprouvé, puisqu’il est disponible depuis près de six années et qu’il est déjà utilisé en production sur des applications Android. Quelques exemples : Flipboard, Pinterest ou Expedia.

### Qu’offre Kotlin ?
Il offre beaucoup de fonctionnalités, c'est un language plus riche, flexible et concis. Quelques fonctionnalités : ne plus avoir besoin de mettre des points virgules à la fin de chaque instruction, l’inférence de type (mécanisme qui permet à un compilateur de rechercher automatiquement les types associés à des expressions, sans qu'ils soient indiqués explicitement dans le code source), étendre des classes existantes,…  
 Une page officielle détaille plus précisément les [différences que l’on peut trouver avec Java.] (https://kotlinlang.org/docs/reference/comparison-to-java.html "link to différences que l’on peut trouver avec Java.")  
 [google] (http://www.google.com "link to google")
















## Mise en place
### Installation
How to install Oracle Java JDK on Ubuntu Linux

Ouvrez le terminal

sudo apt-add-repository ppa:webupd8team/java 

sudo apt-get update 

sudo apt-get install oracle-java8-installer

java -version

clear

sudo gedit /etc/profile

export JAVA_HOME=/usr/lib/jvm/java-8-oracle




How to install Android Studio in Ubuntu Linux

https://developer.android.com/studio/

Ouvrez le terminal dans le dossier bin

sudo chmod 777 -R studio.sh

./studio.sh

Si erreur -> Error:Unable to run mksdcard SDK tool in ubuntu 

sudo apt-get install lib32z1 lib32ncurses5 lib32bz2-1.0 lib32stdc++6 


