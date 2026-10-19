# Portfolio BTS SIO — Ilian SEGHIRI

Portfolio de BTS SIO, option SISR (Ensitech).

En ligne : https://ilivn.github.io/Portfolio-v1.1/

## Contenu

Un seul onglet, **Mes projets** : LootRadar (site), Sport Local (application) et Carnet (CRM).
À côté de chaque projet, une pub de 20 secondes façon télé : scénario en 6 scènes, fausse interface animée,
sous-titres et voix off. Les scènes sont écrites dans l'objet `PUBS` du script.

### Voix off

Les voix sont des fichiers MP3 dans `voix/` (un par scène), générés avec [Piper](https://github.com/rhasspy/piper),
un moteur de synthèse vocale open source (licence MIT), avec la voix française « Siwis »
(corpus SIWIS, Université d'Édimbourg, licence CC BY 4.0 : la mention est dans le pied de page).

Pour refaire une voix : `echo "Ton texte" | piper --model fr-siwis-medium.onnx --output_file voix.wav`,
puis convertir en MP3 et mettre le chemin dans le champ `son` de la scène.

## Ajouter un projet

Tout se trouve dans `index.html`, dans la liste `onglets` en haut du script.
Ajouter un objet dans le tableau `projets` en copiant un projet existant, puis écrire ses scènes dans `PUBS` (même nom que le projet).
