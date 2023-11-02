# Trucs et astuces

## Les schémas de pièces

- La référence [RealOEM](https://www.realoem.com/bmw/partgrp.do?model=UF91&mospid=48927&hg=51)
- [Bmw Fans](http://bmwfans.info/parts-catalog/E87N/Europe/130i-N52N/L-N/jan2006/browse)

## Tarifs des pièces

Pour se faire une idée approximative des tarifs BMW consulter <https://www.leebmann24.de/> ou <https://www.hubauer-shop.de/fr/> et taper la référence de la pièce dans la zone de recherche.

Si la pièce n'est pas trop spécifique, on peut également essayer sur <https://www.auto-doc.fr/> ou <https://www.oscaro.com/>

## E87 Phase 1 : blocage intempestif des essuies-glaces

Au niveau de la boîte à fusibles, au fond de la boîte à gants, il faut remplacer le relais bleu `61 36 6 918 816` par un nouveau relais vert `61 36 6 980 177` (16.07€ HT en 2012).

## Rentrer dans les menus cachés de l'ODB

La manipulation suivante décrit la procédure rentrer les menus cachés de l'ordinateur de bord et obtenir certaines informations non disponible de base, comme par exemple le voltage de la batterie.

**La manipulation se fait moteur éteint.** Celle-ci n’est pas forcément évidente, il n'est pas rare de devoir recommencer plusieurs fois. Une fois celle-ci bien mémorisée ça va tout seul.

Appuyer sur le bouton de remise à zéro du compteur kilométrique puis insérer la clef dans le slot tout en maintenant le bouton enfoncé.

Un menu s'affiche au tableau de bord avec le numéro `01.__`.

Puis sans attendre, appuyer plusieurs fois sur le bouton de remise a zéro du compteur kilométrique pour naviguer dans les différents menus jusqu'à arriver au numéro `19.__`.

Ce menu `19.00` sert a débloquer provisoirement d'autres menus (`LOCK: ON `s'affiche). Patienter légèrement jusqu'à l'apparition du message `CODE 00`. Puis sans attendre via le bouton de remise a zéro du compteur kilométrique, en incrémentant de 1 en 1 rentrer le code correspondant à la somme des 5 derniers chiffres du numéro de série (ou numéro de châssis) du véhicule (Les 5 derniers chiffres du code commençant par WBA).

Patienter encore un peu, de retour au menu `01` appuyer plusieurs fois sur le bouton de remise a zéro du compteur kilométrique pour naviguer dans les différents menus.

## Quelques codes couleurs utiles

- **A97** : Diffuseur arrière Pack M : **SCHIEFERGRAU** (= gris ardoise)
- **668** : Shadow Line : **GLANZSCHWARZ** (= Noir brillant)
- **5002** : Bleu clair du logo ///M
- **4000** : Bleu violet du logo ///M
- **353** : Rouge du logo ///M
- **A44** Couleur jantes grises E8X, F2X **Reflexsilber**
- **A55** Couleur jantes 216M, 261M, 359M, grises : **Dekorsilber**
- **A80** Couleur jantes anthracite 261M, 269, 313M, 361 **Ferric Grey** / **Ferricgrau**
- **B55** Couleur jantes anthracite F2X **Ferric Grey 2**
- **B20** Couleur jantes F2X 383M, 386M **Dekorsilber 2**
- **445** Couleur étriers Performance **Phoenix Gold Metalic** (Teinte M3 E46)
- **472** Couleur étriers 135i **Sterlinggrau**

---
:point_left: [Retour au sommaire](../README.md#sommaire)
