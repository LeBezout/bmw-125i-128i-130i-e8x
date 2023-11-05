# [TUTO] Rentrer dans les menus cachés de l'ODB

La manipulation suivante décrit la procédure pour rentrer les menus cachés de l'ordinateur de bord et obtenir certaines informations non disponibles de base, comme par exemple le voltage de la batterie.

**La manipulation se fait moteur éteint.** Celle-ci n’est pas forcément évidente, il n'est pas rare de devoir recommencer plusieurs fois. Une fois celle-ci bien mémorisée ça va tout seul.

:information_source: Préalablement il vous faudra calculer la somme des 5 derniers numéros du VIN de votre véhicule. Exemple avec le code chassis `PS12345` : 1+2+3+4+5 = 15

## Procédure

Appuyer sur le bouton de remise à zéro du compteur kilométrique puis insérer la clef dans le slot tout en maintenant le bouton enfoncé.

Un menu s'affiche au tableau de bord avec le numéro `01.__`.

Puis sans attendre, appuyer plusieurs fois sur le bouton de remise a zéro du compteur kilométrique pour naviguer dans les différents menus jusqu'à arriver au numéro `19.__`.

Ce menu `19.00` sert a débloquer provisoirement d'autres menus (`LOCK: ON` s'affiche). Patienter légèrement jusqu'à l'apparition du message `CODE 00`. Puis sans attendre via le bouton de remise a zéro du compteur kilométrique, en incrémentant de 1 en 1 rentrer le code correspondant à la somme des 5 derniers chiffres du numéro de série (ou numéro de châssis) du véhicule (Les 5 derniers chiffres du code commençant par WBA).

Patienter encore un peu, de retour au menu `01` appuyer plusieurs fois sur le bouton de remise a zéro du compteur kilométrique pour naviguer dans les différents menus.

## Exemple : voltage de la batterie

Appuyer plusieurs fois sur le bouton de remise a zéro du compteur kilométrique jusqu'à arriver au numéro `09.00` le voltage de la batterie s'affiche alors.

---
:point_left: [Retour au sommaire](../README.md#sommaire)
