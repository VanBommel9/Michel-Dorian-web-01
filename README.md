

## 1_La commande `npm install` a également généré un fichier package-lock.json avec package.json. Quel est le but de ce fichier ?
C'est une version détaillée de package.json, qui répertorie également les dépendances transitives (c'est-à-dire les dépendances de nos dépendances) et corrige la version de chaque paquet.
c1.jpg 
c2.jpg

## 2_Par convention, toutes les dépendances NPM utilisent un format à 3 chiffres pour les numéros de version. Comment ça s'appelle?

Il s'agit deu Semantic Versioning

## 3_ Qu'est-ce qu'une devDependency exactement ? Quelles sont les différences avec une dépendance?

les dependances sont utilisées pour les tests
Les devDependencies sont utlisées pour le developpement de l'application Web

## 4_Qu'est-ce qu'une closure/iife ? A quoi servait-il ? Qu'est-ce qui l'a remplacé ?

iife est une fonction qui s"exécute au moment où elle est appelé, également utlisé pour déclarer les fonctions privées pour ne pas utiliser de portées globale

## 5_Quelle est la différence entre import * from './utils' et import{ parseUrl } de './utils' ? Quelles peuvent être les conséquences d'utiliser l'un plutôt que l'autre ?
Avec import * from'./utils', on exporte toutes les methodes du fichier utils
Avec la seconde syntaxe il n'ya que parseUrl qui est appelé

## 6_Pouvez-vous penser à au moins 2 choses possibles avec Java classes, mais cela ne peut pas être fait avec les classes ES6 ?

Avec les classes java, on peut surcharger les méthodes et constructeur
et on peut également utiliser des interfaces

## 7_Quelles sont les différences entre var et let;

var est utilisé avec ES5, let avec ES6
avec var, la portée de la variable est définie et limitée à l'interieur de la fonction où elle est déclarée
avec let, la portée de la variable est bien au delà

## 8_Qu'est-ce que c'est que le .bind(this) ? Que se passe-t-il si vous le supprimez ? Est ce necessaire lors de l'utilisation d'une fonction fléchée ? pourquoi ?

le .bind permet de retrouver le contexte global quan on utilise une fonction qu'ona appélé

## 9_ Que signifie le symbole @ dans @babel/*** ?

C'est une convention de nommage qui définit le package comme associé à Babel

## 10_Quels sont les avantages des Promesses ?

Elle permet de representer l'achevement ou l'echec eventuel d'une fonction asynchrone

## 11_ Dans quelle version d'ECMAScript async/await a-t-il été publié ?

il s'agir de la version 8

## 12_ La programmation orientée composants pour le Web est considérée comme plus maintenable. Pourquoi?
Parce qu'elle isole les modifications

## 13_ Qu'est-ce que la programmation fonctionnelle ?
est un paradigme de programmation où les programmes sont construits en appliquant et en composant des fonctions 

## 14_ Expliquez ce que fait la fonction map() ?

Elle crée un nouveau tableau rempli avec les résultats de l'appel d'une fonction fournie sur chaque élément du tableau appelant.

## 15_Expliquez ce que fait la fonction filter() ?
crée une copie superficielle d'une partie d'un tableau donné, filtrée uniquement pour les éléments du tableau donné qui réussissent le test implémenté par la fonction fournie.

## 16_ Expliquez ce que fait la fonction reduce() ?
 exécute une fonction de rappel "réducteur" fournie par l'utilisateur sur chaque élément du tableau, dans l'ordre, en transmettant la valeur de retour du calcul sur l'élément précédent

## 17_ Quelle est la différence entre .then() et async/wait lors de la gestion des fonctions asynchrones ?

async/await permet d'appeler d'autres fonctions asynchrones sans avoir besoin de configurer la chaîne de promesses.
.then() renvoie une promesse

## 18_ Que signifie le préfixe _ sur un fichier sass?
il signifie que le fichier est destiné à etre importé  d'autres fichiers sass
