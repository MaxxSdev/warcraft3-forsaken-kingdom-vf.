# Doublage français — Warcraft III : Forsaken Kingdom

Doublage français non officiel de la campagne DLC *Forsaken Kingdom*,
sortie avec le patch 3.0 de Warcraft III: Reforged uniquement en
anglais.

1231 répliques, soit l'intégralité des dialogues de mission, de
transmission et de cinématique in-game.

---

## Installation

**1. Autoriser les fichiers locaux**

Ouvrir une invite de commandes et coller :

```
reg add "HKEY_CURRENT_USER\SOFTWARE\Blizzard Entertainment\Warcraft III" /v "Allow Local Files" /t REG_DWORD /d 1 /f
```

**2. Copier les fichiers**

Décompresser l'archive, puis copier le dossier `war3.w3mod` dans le
dossier `_retail_` de votre installation, à côté de `x86_64`.

Exemple si le jeu est installé dans `C:\Program Files (x86)\Warcraft III` :

```
C:\Program Files (x86)\Warcraft III\_retail_\war3.w3mod\...
```

Pour trouver votre dossier d'installation : Battle.net, roue dentée à
côté de Warcraft III, Paramètres du jeu, Répertoire d'installation.

**3. Mettre le jeu en français**

Dans Battle.net, même écran : *Langue des textes* et *Langue des
dialogues* sur Français. Sans cela le jeu ne lira pas ces fichiers.

**4. Fermer complètement le jeu et Battle.net**, puis relancer.

---

## Désinstallation

Supprimer le dossier :

```
_retail_\war3.w3mod\_locales\frfr.w3mod\sound\dialogue
```

Le jeu repasse automatiquement sur les voix anglaises d'origine.

---

## Ce qui est doublé, ce qui ne l'est pas

Doublé :
- prologue « Les derniers jours de Lordaéron » (4 missions + interlude)
- campagne « Le royaume des Réprouvés » (3 missions + interlude)
- dialogues de mission, transmissions, cinématiques in-game

Non doublé, reste en anglais :
- les trois cinématiques précalculées (intro, outro, promo), qui sont
  hors du système de localisation du jeu
- deux fichiers non verbaux (bruits de lutte)

---

## Comment c'est fait

Les sous-titres français des dialogues n'étant pas accessibles (les
fichiers de map du DLC sont chiffrés), la traduction a été refaite
intégralement depuis une transcription automatique de l'anglais, puis
relue et réécrite pour tenir dans le temps de parole d'origine.

Les voix sont synthétiques. Le niveau sonore de chaque réplique est
aligné sur celui de la prise anglaise correspondante, et l'intensité
de jeu suit les mesures acoustiques de l'original.

Ce n'est pas un doublage professionnel : la diction est correcte mais
l'interprétation reste celle d'une machine.

---

## Crédits et limites

Les modèles vocaux utilisés proviennent de la communauté RVC et sont
basés sur des voix de personnes réelles. Ce patch est un travail
d'amateur, gratuit, non affilié à Blizzard Entertainment.

Warcraft III et Forsaken Kingdom sont la propriété de Blizzard
Entertainment.
