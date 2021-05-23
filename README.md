# check-if-hour-is-beetwen-20-00-and-7-59
Battle dev contest nov 2020 2 easy

https://demo.isograd.com/runtest/QuestionDisplayer#output

A partir de la liste des heures de publication d'un compte (les heures sont déjà converties en heure russe), déterminez si ce compte a plus d'activité la nuit que le jour. Si plus de 50% des tweets sont entre 20h et 8h, alors c'est un compte de fake news.


Données

Entrée

Ligne 1 : un entier N compris entre 5 et 1000, représentant le nombre de publications faites par le compte à examiner.
Lignes 2 à N+1 : une chaîne de caractères de la forme hh:mm représentant l'heure d'une publication

Sortie

Votre programme devra renvoyer une seule ligne : SUSPICIOUS si le compte est suspect, OK sinon.

Un compte est considéré suspect si plus de la moitié des publications sont faites la nuit (entre 20:00 et 7:59 compris). Il est garanti qu'aucun compte n'a autant de publications la nuit que le jour.


Exemple

Pour l'entrée :

5
20:04
20:23
08:00
09:15
13:00


Votre code devra renvoyer : OK
En effet, seulement 2 publications ont été faites la nuit sur ce compte.

Pour l'entrée :

5
20:00
00:29
22:58
15:06
17:50


Votre code devra renvoyer : SUSPICIOUS
