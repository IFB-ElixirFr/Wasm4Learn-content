---
title: 'R en quelques mots'
description: 'meta description of the page'
---

## Pourquoi ?

Langage de programmation qui permet de :

- manipuler des données : importer, transformer, exporter faire des analyses statistiques plus ou moins complexes : description, exploration, modélisation...
- créer des (jolies) figures

## Comment l'avoir ?

Disponible sur [RCRAN](https://cran.r-project.org/){target="_blank"}

## Sur quel OS ?

Tous !

## Historique

- 1993 : Début du projet R
- 2000 : sortie de R 1.0.0
- 2022 : R 4.2.2

## R vs Excel

![](images/rblogger.png)
Source: R-bloggers

### Pourquoi plus Excel ?

Un exemple parmi tant d'autres ! 

![](images/covid.png)

Source Alexandre Counis, Les Echos, 5 oct. 2020

## Avantages et inconvénients

### Avantages

- Souplesse d’utilisation pour réaliser des analyses statistiques
- Libre et gratuit, même s'il existe maintenant des versions payantes de RStudio (shiny et/ou server)
- Reproductibilité des analyses en écrivant/sauvegardant les commandes R dans des scripts
- Large communauté d’utilisateurs/aide en ligne
- Grand nombre de packages spécifiques

### Inconvénients

## Geeks and repetitive tasks

![](images/geeks.png)

## R sait tout faire

Lire un tableau de données

```r
read.table()
```

Fusionner deux tableaux

```r
merge()
```

Filtrer des lignes

```r
data[data$x > 10]
```

Sélectionner des colonnes

```r
data[,c(“x”,”y”)]
```

Rechercher une chaîne de caractères

```r
grep()
```

Réaliser une ACP

```r
prcomp()
```

Calculer une moyenne

```r
mean()
```

Additionner deux matrices

```r
mat1 + mat2
```

Exporter un tableau de données

```r
write.table()
```

Calculer une variance

```r
var()
```

Régression linéaire

```r
lm()
```

Tracer une courbe

```r
plot()
```

Tester une hypothèse

```r
t.test()
```

Dessiner un histogramme

```r
hist()
```

Convertir des données

```r
as.matrix()
```