# Pages Wiki Skavens — AoS v4

Archive des pages wiki générées pour l'import du Battletome Skavens.
Format : wikicode MediaWiki, fichiers `.txt`. À importer sur le wiki.

## Organisation
- **Pages/** — les pages de contenu (unités, machines, personnages, lieux, histoire…).
- **Categories/** — les pages de catégorie (dont certaines portent du lore + transclusions).
- **Redirections/** — les redirections (synonymes, formes alternatives, sections, variantes).
- **Textes_non_places/** — fragments non encore affectés à une page définitive (texte d'ouverture, brouillon de répartition).

## Notes d'import
- Le **nom de fichier** est une commodité ; le **titre wiki réel** peut différer (apostrophes typographiques, accents, deux-points de catégorie). Ex. : `Categorie_La_Rogne.txt` → page `Catégorie:La Rogne` ; `Batterie_d_Arme_Malétincelle.txt` → `Batterie d'Arme Malétincelle`.
- Les pages de **catégorie** se créent sous l'espace `Catégorie:`.
- Les **redirections** vers catégorie utilisent `[[:Catégorie:...]]` (deux-points).
- Pas d'images dans les pages : à placer manuellement après import.
- Quelques **liens rouges** subsistent (cibles non encore créées : Maître-terrier, Empire Souterrain, etc.) — c'est normal.

## Doublons potentiels avec l'existant
Les pages Prêtre de la Peste et Moines de la Peste peuvent exister en version obsolète (AoS v3) sur le wiki : arbitrer le remplacement à l'import.
