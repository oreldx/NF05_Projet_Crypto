# Initiation à la cryptographie symétrique

Au cours de notre troisième semestre à l’Université de Technologie de Troyes, nous avons suivi l’Unité d’Enseignement (UE) NF05, « Introduction au langage C ». Dans le cadre de cette UE, nous avons eu l’opportunité de réaliser un projet dans ce langage. Parmi les sujets proposés, nous avons opté pour le sujet portant sur la cryptographie.

La cryptographie est le procédé permettant de chiffrer un message, c’est-à-dire le rendre « secret » afin que seuls les destinataires puissent le lire. Pour pouvoir crypter et décrypter le message, il faut avoir une « clef de chiffrement ». Notre programme applique une méthode de cryptage dite symétrique, cela signifie que la clef permet à la fois de crypter et de décrypter.

La méthode de cryptage que nous avons codé est une méthode itérative. Lors de l’exécution, il y aura, en effet, une répétition des étapes de cryptage N fois, (N étant choisi par l’utilisateur souhaitant crypter). Il y a en tout 5 étapes de cryptage correspondant chacune à une procédure dans notre programme.


L'objectif de notre projet est de pouvoir appliquer cette méthode de cryptage à tout document, quelque soit son type, en choisissant une clé de cryptage ainsi qu’un nombre d’itérations.

### Pré-requis

Ce projet n’a pas été compilé en exécutable, par conséquent il est nécessaire d’avoir un IDE ainsi que CMakes d’installés. De plus, sa conception a été réalisée sur des machines sous Windows 10 [64 bits].

- IDE
- CMakes

### Installation

Les étapes pour installer votre programme....

Dites ce qu'il faut faire...

_exemple_: Executez la commande ``telnet mapscii.me`` pour commencer ensuite [...]


Ensuite vous pouvez montrer ce que vous obtenez au final...

## Démarrage

Afin de faire fonctionner le programme, il est nécessaire de suivre l'odre suivant des saisies : 

1. Saisir l'opération à éffectuer, 2 options se présentent : 
- Le CRYPTAGE
- Le DECRYPTAGE  

2. Saisir la clé de chiffrement (que vous choisissez arbitrairement).

3. Saisir le nombre d'itérations

4. Saisir le ""nom"" du fichier en entrée [chemin d'accès + nom + extension]

4. Indiquer si l'on souhaite définir le nom du fichier en sortie d'éxecution 
  a. Si oui, alors entrer une chaine de caractères définissant le nom [nom]
 
##Fonctionnalités

- Ce programme permet d'effectuer le cryptage et le décryptage d'un fichier de tout type et toute taille selon une clé de chiffrement et un nombre d'itérations.

- Il est possible de choisir un nom spécifique pour le fichier en sortie d'opération

- Lors de l'opération, il y a un suivi de l'avancement de celle-ci.

## Fabriqué avec

* [Clion](https://www.jetbrains.com/fr-fr/clion/) - IDE C from JetBrains
* [Atom](https://atom.io/) - Editeur de textes

## Auteurs
Listez le(s) auteur(s) du projet ici !
* **Orel** _alias_ [@pyropony](https://github.com/PyroPony)
* **Aya** _alias_ [@aya-adl](https://github.com/aya-adl)
