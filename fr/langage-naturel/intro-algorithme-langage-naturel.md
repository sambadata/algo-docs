# Algorithme en langage naturel - Introduction

## Définitions

### Algorithme

Un algorithme est une série ordonnée d’*instructions* élémentaire pour aboutir à un résultat final donné répondant à un problème.

### Instruction

Une instruction regroupe une action ou une série d'actions créée à partir de la combinaison de  **quatre commandes de base** :
- affectation de variables
- action de lecture / écriture
- tests
- boucles

## Langage des algorithmes

### Langage naturel

Les algorithmes peuvent être écrits en *langage naturel* (anglais, français, etc.) c'est à dire compréhensible facilement par une personne non experte en programmation (client, lecteur d'un article, etc.). 

Quand on écrit de l'algorithmique en langage naturel, on ne dépend pas de la syntaxe d'un langage informatique comme Python, par exemple. 

En écrivant d'abord nos algorithmes en langage naturel, on peut mieux comprendre leur finalité et donc les programmer plus facilement par la suite, avec le langage informatique de notre choix.

### Langage informatique

Les algorithmes peuvent être également écrits en *langage informatique* c'est à dire dans un langage spécialement créés pour les ordinateurs afin qu'ils puissent les interpréter (comprendre).

### Programmation

C''est une activité qui consiste à créer un script (programme) dans un langage informatique pouvant être compris et utilisé par un ordinateur : Python, Javascript, etc.

## Cheatsheet

## Structure d'un algorithme
```javascript
Algorithme nom_algorithme    // bloc d'en-tête indiquant le nom de l'agorithme
Debut	                  // bloc de traitement où le bloc d'instructions est situé entre Debut et Fin
	bloc d'instructions      // chaque ligne comporte une seule instruction
Fin
```
- **Remarque** :
	- Un **bloc d'instructions** correspond à une **partie de traitement de l'algorithme** composé de commandes de base et est situé entre Debut et Fin.
	- Chaque ligne comporte une seule instruction
	- la notation **//** permet d'ajouter un commentaire



## Affection de variable

**instruction d'affectation**

```javascript 
variable <- donnée à mémoriser  
``` 
- **Remarque** :
L'affection se fait de la droite vers la gauche

- **Exemple** :

Affecter le prénom 'John' à la variable 'prenom' :

```javascript
prenom <- John 
```

## Instructions conditionnelles

**Instruction avec une condition** 
```javascript 
Si condition alors
	instructions
Fin Si
```   

**Instruction avec deux conditions** 

```javascript 
Si condition alors
	instructions 1
Sinon
	instructions 2
Fin Si
``` 
**Instruction avec plusieurs conditions** 

```javascript 
Si condition alors
	instructions 1
Sinon si condition alors
	instructions 2
...
Sinon
	instructions finales
Fin Si
``` 
- **Remarque** :
L'utilisation des **instructions conditionnelles imbriquées** est importante pour rendre les **algorithmes plus simples à écrire et à lire, plus optimisés** par rapport au **temps d'exécution plus performant de l'ordinateur**.


## Contact

Pour envoyer vos commentaires ou suggestions : samba.cisse.data@gmail.com

## Copyright & Licence

Copyright © [Samba Cissé](http://www.sambacisse.com)

License: 
![enter image description here](https://licensebuttons.net/l/by-nc-sa/3.0/88x31.png)
**CC BY-NC-SA**
Attribution - Pas d’Utilisation Commerciale - Partage dans les Mêmes Conditions
*This license lets others remix, adapt, and build upon your work non-commercially, as long as they credit you and license their new creations under the identical terms.*
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTgyMDc1MTAzM119
-->