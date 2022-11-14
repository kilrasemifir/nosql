# Information formateur : PLAN DE COURS

## Lancer le cours

Prérequis : NodeJS

Pour lancer le cours, il faut au préalable installer 'reveal-md'.

```shell
npm i reveal-md

```

Ensuite, se placer à la racine du dossier et taper

```shell
reveal-md .\01_Nom_Du_Fichier.md <!-- utiliser Set-ExecutionPolicy si la commande est refusé par le système --> 
```

Le cours se lancera dans le navigateur.
Pour accéder aux notes, une fois la présentation démarrée, appuyez sur la touche 's' du clavier.

## Commandes Reveal-md

- `s` : Mode présentateur
- `c` : Mode stylet (écrire sur les slides)
  - Clic droit pour effacer
- `b` : Mode tableau blanc

En bas à droite se trouve le menu pour accéder rapidement aux chapitres

---

## Utiliser ce support

Le support se compose de plusieurs éléments :

- Cours (répartis en chapitres)
- Démos
  - Un fichier md par démo
- Exercices
  - Poussin,
  - Poulet
  - Coq
  - _Corrections

### Cours

En ce qui concerne les cours, une fois le serveur reveal-md lancé, appuyez sur `s` pour afficher le mode présentateur (similaire à powerpoint).

Les notes du mode présentateurs donnent des informations sur les choses à réaliser :

- Mémo de commandes pour les mini-démos,
- Nom du fichier pour les démos.

Lorsque vous verrez 'démonstration' à l'écran, c'est que c'est à vous de jouer ! Basez vous sur les fichiers indiqués ou contentez vous de taper les commandes indiquées dans le mode présentateur.

A chaque fin de chapitre, un lien vous ammènera directement au support du chapitre suivant.

### Démos

Les démos sont toutes très guidées de sorte à ce qu'elles servent au mieux le propos du chapitre concerné.

Il s'agit de commandes avec explications associées qu'il ne faut **en aucun cas fournir/montrer aux élèves**. Vous les disposerez sur votre écran personnel tandis que vous réaliserez les actions sur l'écran partagé.

L'idée est de suivre cette guideline sans risque de vous perdre ou de passer 5 mn à essayer de comprendre pourquoi votre démo improvisée n'a pas marché.
Cela évite de devoir réfléchir à une démo 'sur le vif', démo qui pourrait ne pas être pertinente vis à vis du contenu théorique déjà montré aux élèves.

### Exercices

Les éxercices sont séparés en deux niveaux : Poussin (facile) et Poulet (moyen) et Coq (difficile).

Dans les deux cas, l'ennoncé est persque identique, mais le mode Poussin sera en général plus guidé et proposera des indices pour aider les stagiaires les moins confiants en leurs capacités.
La version coq ne contient aucune explication et demande juste un résultat. 

Ce n'est pas au formateur de choisir quel niveau est fait par quel élève mais bien à l'élève de choisir lui même quel niveau de difficulté il souhaite s'imposer.

Tous les exercices sont corrigés. Comme pour les démos, il convient **DE NE PAS** donner bêtement le fichier de correction, mais bien de réaliser la correction en live devant les stagiaires en se basant sur le fichier.
Libre à vous de donner ensuite les fichiers que vous produirez vous même lors de cette démo corrective.

N'oubliez pas qu'il est possible de laisser les élèves proposer leur correction.

## Améliorations à apporter

Les améliorations à apporter aux supports : 



---

## Plan de cours : 

reveal-md '.\Historique.md' -w --port 8000 --template template.html --css styles.css"# nosql" 
