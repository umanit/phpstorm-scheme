# Fichiers de configuration PhpStorm

## Pré-requis

1. Utiliser PhpStorm
2. Installer le
   plugin [Php Inspections (EA Extended)](https://plugins.jetbrains.com/plugin/7622-php-inspections-ea-extended-)

## Présentation

Le dépôt contient plusieurs fichiers de configuration à importer dans PhpStorm :

* `Scheme_UmanIT.xml` : Gère les règles de mises en forme du code
* `Profile_UmanIT.xml` : Gère les règles d'inspection du code

Ces configurations sont là afin que tout le monde respecte les mêmes normes de code. Cela ne veut pas pour autant dire
qu'elles sont figées dans le marbre, elles peuvent très bien évoluer avec le temps.

Si certaines règles semblent trop extrêmes ou, au contraire, trop souple, il ne faut pas hésiter à en parler ensemble
afin de voir comment se mettre tous d'accord plutôt que de ne rien dire et modifier seul les règles dans son coin.

Les différents fichiers posent les règles par défaut de l'IDE, mais elles peuvent être surchargées par projet au besoin
(reprise d'un code ayant des règles complètement différentes comme les projets Drupal ou WordPress).

## Mise en place

1. Le fichier `Scheme_UmanIT.xml` s'importe dans **Settings -> Editor -> Code Style**
    * En haut de la fenêtre, cliquer sur le bouton de menu à droite de la liste déroulante
    * Sélectionner **Import Scheme** tout en bas
    * Choisir **IntelliJ IDEA code style XML**
    * Sélectionner le fichier **Scheme UmanIT.xml**
2. Le fichier `Profile_UmanIT.xml` s'importe dans **Settigns -> Editor -> Inspection**
    * En haut de la fenêtre, cliquer sur le bouton de menu à droite de la liste déroulante
    * Sélectionner **Import Profile...** tout en bas
    * Sélectionner le fichier **Profile UmanIT.xml**
