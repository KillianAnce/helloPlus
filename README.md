# Projet HelloPlus (Java8, Maven, Apache-csv)

## Cadre du projet
Ce projet est réalisé dans le cadre du cours de programmation Avancée en Master1 MIAGE de l'université de lorraine.

Le but de cet exercice étant de se familiariser avec les technologies Maven et Github pour intégrer des bonnes pratiques.

## Description de l'application
L'application développé coniste à lire un fichier CSV en entrée prenant la forme suivante : 

```
#NOM;PRENOM
```
L'application va renvoyer pour chaque ligne du CSV, le réssultat suivant : 

```
Hello Nom Prenom
```

## Installation 

### Prérequis avant utilisation

Cette application a été developpée pour fonctionner avec Java 8, il faut donc ce prémunir de JDK 8.

Il faut obligatoirement donner le paramètre `-i` pour pouvoir fournir un fichier CSV.

### Exécution du fichier .jar (jdk1.8)



### Exécution du script

Depuis un terminal se trouvant à la racine du projet : 

Windows : `.\scripts\bin\app.bat -i .\samples\nom.csv` \
Linux & Unix : `/scripts/bin/app -i /samples/nom.csv`

## Exemple d'utilisation

Un fichier CSV d'exemple est disponible dans le répertoire `samples/nom.csv`.

```
app.bat -i ..\..\samples\nom.csv
Hello AUBRY RODOLPHE !
Hello CALLEY NICOLAS !
Hello CANTE BENOIT !
Hello CLADT LAURENE !
Hello DIALLO ABDOULAYE !
Hello DOLET MAXIME !
Hello FERRY EMELINE !
Hello GENG ALEXIS !
```
## Dépendances utilisés

[Maven](https://maven.apache.org/) - Manager de dépendances

* Commons-cli 1.4 : https://commons.apache.org/proper/commons-cli/
* Commons-csv 1.5 : https://commons.apache.org/proper/commons-csv/
* junit 4.12 : https://mvnrepository.com/artifact/junit/junit/4.12

## Auteur

* **Killian Ancé** - [Killian Ancé](https://github.com/KillianAnce)

## License

Ce projet est distribué sous la licence MIT.
