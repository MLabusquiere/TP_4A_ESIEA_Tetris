# TP Architecture Logicielle / Inf4043 
## Tetris Multijoueur Java

>Le but de ce tp est de coder un jeu créé en juin 1984 par Alekseï Pajitnov : _TETRIS_

- Votre tetris pourra être joué seul mais aussi en mode multijoueur (2 personnes sont suffisantes mais vous pouvez faire plus). 
- Le mode multijoueur devra être effectué à travers le réseau (une instance de l'application démarré par joueur).
- En mode multijoueur, chaque fois qu'un joueur casse 10 lignes, il envoie un malus à son adversaire. Un minimum de deux types de malus différents est requis. 
- On vous laisse libre choix sur les malus (plafond qui descend, impossibilité de tourner les pièces pendant un certain temps, rajout de lignes, ...)

- Un minimum de trois types de tétriminos (les pièces du tetris) différents est requis. Le joueur doit au minimum pouvoir tourner la pièce et la déplacer de droite à gauche.
- Les 5 meilleurs scores (nombre de lignes détruites) doivent être enregistrés dans un fichier pour pouvoir être persistés et ainsi pouvoir être affichés a posteriori.
- Une simple interface en ligne de commande est acceptée et suffisante. Vous pouvez aussi utiliser des librairies graphiques si vous le souhaitez.

- Une grande importance sera attachée à la qualité du code, à la conception objet et au découpage par fonctionnalités avec des contrats clairs. 
- Nous vous encourageons à utiliser des analyseurs de code statiques (npm, findbugs, ...). Nous les utiliserons pour corriger.
- Nous encourageons aussi une approche TDD sur le projet. L'utilisation des librairies mockito et AssertJ est fortement conseillée. 

## Exercice Architecture
- Un ou plusieurs paragraphes sont demandés pour présenter et justifier votre architecture. N'hésitez pas à utiliser les techniques de representation d'architecture vues dans le cours

## Exercice Design Pattern / Solid
- Illustrez trois principes SOLID ou design pattern en utilisant vos propres classes. 
- Pourquoi avez-vous utilisé ce design pattern / principe ? Qu'est-ce que cela vous a apporté ? Et comment l'avez-vous appliqué ?


## Barème :

### cours / TP
A priori 50 % TP - 50 % partiel 

### TP

| Points | Descriotion           | 
| :----- |:-------------| 
5 points | Architecture du code, découpage des classes, respect des principes Objects (SOLIDE), méthodes < 15 lignes... |
5 points | La totalité des feature faites. Pas de bug et cas aux limites gérés (pas de stacktrace pendant l'execution) |
3 points | Test : code coverage > 70%, assertions intelligentes dans les tests , tests unitaires (utilisation de mockito ou autre framework de mock) |
3 point  | Exercice Architecture & Design Pattern / Solid |
2 points | Analyse static de code findbug / npm |
1 point  | Utilisation de maven (ou autre logiciel du même type) pour gérer les dépendances et construire le projet. Utilisation de git avec plusieurs commits pour chaque personnes du binome |
1 point  | Conventions java / maven respectées (Camelcase, package, ...) |


## Pour rendre son travail :
Le travail est à rendre pour le _30 Mars 2016_
Il faut envoyer un mail au contacts ci dessous avec le nom de votre binome/trinome et l'adresse github de votre projet

>Utiliser la plateforme github.com (cf : https://guides.github.com/activities/hello-world/) ou bitbucket.org pour rendre le code source
Un readme.md à la racine du repository est attendu contenant :
- le nom de votre binome
- Comment builder et lancer le programme (par default : mvn clean install && java -jar *.jar). Evidemment sans l'utilisation de l'IDE
- Les features faites / ajoutés
- Un paragraphe expliquant comment jouer avec votre Tetris
- L'exercice d'architecture
- L'exercice Design Pattern / SOLID

## Contacts : 
- mlab.cours[at]gmail[dot]com
- cours-esiea[at]xgouchet[dot]fr

## Liens Utiles
http://www.source-code.biz/snippets/java/RawConsoleInput/
