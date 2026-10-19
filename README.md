# Portfolio BTS SIO — Ilian SEGHIRI

Portfolio de BTS SIO, option SISR (Ensitech).

En ligne : https://ilivn.github.io/Portfolio-v1.1/

## Contenu

Un seul onglet, **Mes projets** : LootRadar (site), Sport Local (application) et Carnet (CRM).
À côté de chaque projet, une pub de 20 secondes façon télé : scénario en 6 scènes, fausse interface animée,
sous-titres et voix off. Les scènes sont écrites dans l'objet `PUBS` du script.

### Voix off

Les voix sont des fichiers MP3 dans `voix/` (un par scène). Elles ont été générées par IA avec vidIQ
(une narration par pub : Liam pour LootRadar, Laura pour Sport Local, Brian pour Carnet), puis découpées scène par scène.

## Ajouter un projet

Tout se trouve dans `index.html`, dans la liste `onglets` en haut du script.
Ajouter un objet dans le tableau `projets` en copiant un projet existant, puis écrire ses scènes dans `PUBS` (même nom que le projet).
