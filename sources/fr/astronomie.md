---
title: Le ciel, comment ça marche
alt: ../en/astronomy.html
---

# Le ciel, comment ça marche

Pour les curieux : ce que montrent les cadrans et comment c'est calculé.

## Le soleil

- **Hauteur** : angle du soleil au-dessus de l'horizon (0° à l'horizon, négatif en dessous).
- **Azimut** : sa direction. Il ne se lève plein est qu'aux équinoxes : plus au nord-est en été, au sud-est en hiver.
- **Lever, coucher** : le bord du soleil touche l'horizon. L'air courbe la lumière : on le voit un peu avant qu'il soit vraiment levé.
- **Midi solaire** : le soleil au plus haut. Rarement à 12 h pile (fuseau, heure d'été). **Minuit solaire** : au plus bas.
- **Heure dorée** : soleil entre 0 et 6° au-dessus de l'horizon, lumière chaude et rasante.

## Les crépuscules

Après le coucher, la nuit vient par étapes, selon la hauteur du soleil sous l'horizon :

| | Soleil | Ciel |
|---|---|---|
| Civil (heure bleue) | 0 à −6° | encore clair |
| Nautique | −6 à −12° | premières étoiles |
| Astronomique | −12 à −18° | presque noir |
| Nuit noire | sous −18° | noir |

Le matin, dans l'autre sens. Autour du solstice d'été, à Paris, il n'y a pas de nuit noire. Au-delà du cercle polaire : soleil qui ne se couche pas (jour polaire) ou ne se lève pas (nuit polaire).

## La lune

- **Phases** : un cycle de 29,5 jours. Nouvelle lune (côté soleil, invisible), croissant, premier quartier, gibbeuse, pleine lune (à l'opposé du soleil), puis décroissante. Le pourcentage indique la part éclairée.
- **Lever** : environ 50 minutes plus tard chaque jour. La pleine lune se lève quand le soleil se couche.
- **Hauteur** : la pleine lune est haute en hiver, basse en été, à l'inverse du soleil.
- **Hémisphère sud** : la phase est vue à l'envers.

## Comment c'est calculé

- **Sur la montre**, à partir de l'heure et de votre position. Rien n'est envoyé.
- **Formules** de l'astronome Jean Meeus (*Astronomical Algorithms*), qui décrivent la course apparente du soleil et de la lune.
- **Une fois par jour** (et au changement de position ou de fuseau), puis suivi toutes les deux minutes par interpolation : sobre en batterie.
- **Vérifié** sur 354 journées (de Quito à Tromsø) contre les éphémérides de la NASA-JPL et de l'USNO :

| | Précision |
|---|---|
| Lever, coucher du soleil, crépuscules | ± 1 min |
| Lever, coucher de la lune | ± 5 min |
| Hauteur, azimut | ± 0,1° |
| Part éclairée de la lune | ± 1 % |
| Pleine, nouvelle lune | ± 15 min |

Près des pôles, quand le soleil frôle l'horizon, les heures sont moins précises.
