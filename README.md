Lego Challenge
==============

Présentation
------------

Projet réalisé dans le cadre du challenge Lego GMD : 24 heures pour la réalisation d'un robot Mindstorms RCX2.

Chaque boîte contenait en plus des briques de Lego standards 1 brique programmable, 3 moteurs, 2 capteurs de lumière et 2 capteurs de pression.

Installation
------------

Le logiciel utilisé (Brixcc) est pourri jusqu'à la moëlle et ne fonctionnera pas sous machines 64 bits. Pas plus de réussite avec des machines virtuelles 32 bits...

La meilleure solution est d'utiliser ce tuto pour coder en bas niveau sous Linux tel que décrit sur http://techmalt.com/?p=268.

Ensuite, on installe le firmware `nqc -firmware firm0328.lgo` (c'est long)

Puis on code son fichier NQC que l'on envoie avec `nqc -d src.nqc`.