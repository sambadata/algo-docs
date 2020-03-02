# Algorithme en langage naturel

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
Algorithme nom-algorithme    // bloc d'en-tête indiquant le nom de l'agorithme
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
	- L'affection se fait de la droite vers la gauche
	- Une **variable** a **un nom et un type unique**
	- Une variable stocke une valeur dans un emplacement mémoire
	- La valeur stockée dans la variable est modifiée au cours du traitement lors de la lecture de l'algorithme

- **Exemple** :

Affecter le prénom 'John' à la variable 'prenom' :

```javascript
prenom <- John 
```

## Instructions conditionnelles

**Instruction avec une condition** 
```javascript 
Si condition Alors
	instructions
FinSi
```   

**Instruction avec deux conditions** 

```javascript 
Si condition Alors
	instructions 1
Sinon
	instructions 2
FinSi
``` 
**Instruction avec plusieurs conditions** 

```javascript 
Si condition Alors
	instructions 1
SinonSi condition Alors
	instructions 2
SinonSi condition Alors
	instructions 3
SinonSi condition Alors
	instructions 4
FinSi
``` 
- **Remarque** :

	- L'utilisation des **instructions conditionnelles imbriquées** est importante pour rendre les **algorithmes plus simples à lire et à écrire**
	- Avec les **instructions conditionnelles**, les **algorithmes sont plus performants** par rapport au **temps d'exécution de l'ordinateur**.
	- Dans un **test imbriqué**, on peut regrouper **Sinon** et **Si** en **SinonSi** qui devient un seul bloc de test se terminant par un seul Fin Si


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
eyJoaXN0b3J5IjpbMTY0MDA0NzQxMywtNDk1MTY4Mjg3LDE4NT
A5MjUwMDMsLTMzMTQ2OTM0LDQ1OTAyODUxOSwxNjE5MjY4OTMy
XX0=
-->