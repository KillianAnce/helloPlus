# Projet HelloPlus

Ce projet est réalisé dans le cadre du cours de programmation Avancée en Master1 MIAGE de l'université de lorraine.

Le but de cet exercice est de se familiariser avec les technologies Maven et Github pour intégrer des bonnes pratiques.

L'application développé coniste à lire un fichier CSV en entrée prenant la forme suivante : 

```
#NOM;PRENOM
```
L'application va renvoyer pour chaque ligne du CSV, le réssultat suivant : 

```
Hello Nom Prenom
```

### Prérequis avant utilisation

Cette application a été developpée pour fonctionner avec Java 8, il faut donc ce prémunir du JDK 8.

## Exemple d'utilisation

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
## Plugin utilisé

* [Maven](https://maven.apache.org/) - Manager de dépendances

### Dépendances utilisés

* Commons-cli : https://commons.apache.org/proper/commons-cli/
* Commons-csv : https://commons.apache.org/proper/commons-csv/


## Auteur

* **Killian Ancé** - [Killian Ancé](https://github.com/KillianAnce)

## License

Ce projet est distribué sous la licence MIT ([LICENSE.md](LICENSE.md) pour plus de détails)
