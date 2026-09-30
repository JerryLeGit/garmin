---
title: Lire le cadran — 24h Astro
alt: ../en/reading-the-face.html
---

# Lire le cadran

<img class="schema" src="../img/schema-fr.png" alt="Le cadran avec ses repères numérotés">

1. **Minuit**, en bas de l'anneau.
2. **Midi**, en haut.
3. **Lever du soleil.**
4. **Coucher du soleil.**
5. **Nuit noire** : fin du crépuscule astronomique.
6. **Le soleil, maintenant.**
7. **L'arc de la lune**, de son lever à son coucher.
8. **Boussole** : direction du lever du soleil.
9. **Barre centrale** : hauteur du soleil.
10. **Jauges** : vos données.
11. **Champ du haut** : la batterie par défaut.
12. **Date et ligne lune.**
13. **Barre d'état** : Bluetooth, position.
14. **Notifications.**

## L'anneau des 24 heures

Un tour complet = 24 heures : minuit en bas, 6 h à gauche, midi en haut, 18 h à droite. Traits aux heures paires (plus longs à 0, 6, 12 et 18 h), points aux heures impaires.

**L'arc de jour.** La partie colorée de l'anneau va du lever au coucher du soleil. Sa couleur suit le ciel du moment : bleu très sombre la nuit, bleu moyen tôt le matin et en fin de journée, bleu vif en plein jour.

- Soleil **juste sous l'horizon** : le bout de l'arc, de son côté, s'allume — violet au crépuscule nautique, orange à l'heure bleue.
- Soleil **levé** : un halo l'entoure, doré près de l'horizon (heure dorée), pâle plus haut. Plus le soleil est bas, plus le halo est large.
- Réglage « Dégradés du ciel » : **tramés** (grain fin, par défaut) ou **paliers nets**.

**Les points.** Gros points blancs : lever, coucher, midi solaire (soleil au plus haut) et minuit solaire (au plus bas). Petits points : crépuscules astronomique (−18°), nautique (−12°), civil (−6°), et fin de l'heure dorée (+6°).

**Le soleil.** Disque orangé à cœur blanc quand il est levé, cercle blanc quand il est couché. Il avance avec l'heure.

**Au-delà du cercle polaire.** Jour polaire : l'anneau est coloré sur tout le tour. Nuit polaire : pas d'arc de jour, seulement les points des crépuscules s'il y en a.

## La Lune

- **L'arc gris**, juste à l'intérieur de l'anneau, va de son lever à son coucher. Il passe au suivant quand la lune est au plus bas.
- **Le disque** montre sa phase : nouvelle, croissant, quartier, gibbeuse, pleine. Gris clair quand elle est levée, sombre quand elle est couchée.
- Le disque passe **par le haut** de l'anneau quand la lune est levée, **par le bas** quand elle est couchée : de l'horizon du lever à celui du coucher.
- Réglage « Lune sur le cadran 24 h » : masque l'arc et le disque (la ligne lune reste).

## La boussole

Les triangles posés sur les graduations sont des **directions**, comme sur une carte : nord en haut, est à droite, sud en bas, ouest à gauche. Ce n'est pas une boussole magnétique : le cadran ne connaît pas l'orientation de votre poignet.

- Petit triangle blanc en bas : le **sud**, fixe.
- Triangles blancs : d'où le soleil **se lève** et où il **se couche** aujourd'hui.
- Où est le soleil **maintenant** : triangle orange plein s'il est levé, contour blanc s'il est couché.
- Réglage « Boussole sur les graduations » : soleil (par défaut), lune (triangles gris) ou aucune.

## La barre centrale

Par défaut, la **hauteur du soleil** : le trait blanc est l'horizon, les graduations sont tous les 10°, le petit soleil est à sa hauteur, le remplissage prend la couleur du ciel. Autres styles : soleil et lune, lune seule, batterie, ou barre simple.

## L'heure et les champs

Les grands chiffres donnent l'heure en 24 h. Quatre champs se règlent : en haut, en bas, et deux lignes sous les minutes (par défaut : batterie en haut, date et lune sous les minutes).

**La ligne lune :**

| Affichage | Signification |
|---|---|
| `▲ 8j │ 47%` | Lune croissante : pleine lune dans 8 jours ; 47 % du disque éclairé. |
| `▼ 5j │ 60%` | Lune décroissante : nouvelle lune dans 5 jours. |
| `● 5h` | Pleine lune dans 5 heures (le disque est déjà plein). |
| `● +4h │ 100%` | Pleine lune passée depuis 4 heures. |
| `○ +1j` | Nouvelle lune passée depuis 1 jour. |
| `47h`, `2j` | Durées : en heures sous 48 h, en jours au-delà. |

Sur les petits écrans, le séparateur « │ » disparaît quand la place manque.

**Autres champs propres au cadran :** prochain lever ou coucher du soleil (`7:12`), durée du jour (`12h26`). Les données de la montre : voir [Les données de la montre](../../fr/donnees.html).

## La barre d'état

| Icône | Signification |
|---|---|
| ![](../../img/icones/bluetooth.png) gris clair | Téléphone connecté. |
| ![](../../img/icones/bluetooth-sombre.png) gris foncé | Bluetooth actif, téléphone non connecté. |
| ![](../../img/icones/position-barree.png) | Aucune position connue : le cadran calcule pour Paris. |
| ![](../../img/icones/prise.png) | Montre en charge (seule, si la batterie n'est pas déjà affichée ailleurs). |
| ![](../../img/icones/notifications.png) et un nombre | Notifications en attente (en bas de la colonne de droite). |

## Les jauges

Six dispositions : 4 barres, 3 barres, 1 anneau et 2 barres, 2 barres, 2 anneaux, ou aucune. Ce que montre chaque donnée : [Les données de la montre](../../fr/donnees.html).

## Les thèmes

**Classique** (blanc), **Soleil** (orangé), **Azur** (bleu) : ils changent la couleur de l'heure, des jauges et du point des heures.
