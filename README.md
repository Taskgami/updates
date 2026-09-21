# Taskgami : canal de distribution

Ce dépôt ne contient pas le code de Taskgami. Il sert un seul fichier,
`manifest.json`, que l'application lit au lancement pour savoir où elle en est
(version courante, empreinte du binaire, état de publication).

Le manifeste est signé avec une clé ECDSA P-256 dont la partie publique est
gravée dans chaque exécutable livré. Un fichier modifié ici serait rejeté par
l'application. Ce dépôt peut être muet, il ne peut pas mentir.

Il existe deux autres adresses qui servent le même manifeste signé. Si l'une
tombe, l'application passe à la suivante sans rien demander à personne.

## Contributions

Aucune. Les tickets et les propositions de modification ne sont pas suivis ici.

## Taskgami

Un widget de tâches pour Windows : des bulles ancrées au bord de l'écran, une
criticité par tâche, des rappels qui partent par mail ou sur le téléphone même
quand on a la tête ailleurs.

Édité par DZ IT Strategy : [dzitstrategy.fr](https://dzitstrategy.fr)
