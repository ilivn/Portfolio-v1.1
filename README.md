# Portfolio BTS SIO — Ilian SEGHIRI

Portfolio de BTS SIO, option SISR (Ensitech). Les projets sont classés par bloc de compétences du référentiel.

En ligne : https://ilivn.github.io/Portfolio-v1.1/

## Contenu du dépôt

| Fichier ou dossier | Rôle |
|---|---|
| `index.html` | Le portfolio (page d'accueil du site) |
| `crm/index.html` | Carnet, le CRM pour entreprise, accessible à l'adresse `/Portfolio-v1.1/crm/` |
| `preuves/` | Captures et documents qui servent de preuves aux projets |
| `.nojekyll` | Demande à GitHub Pages de servir les fichiers tels quels |

## Ajouter une preuve à un projet

1. Déposer le fichier (image, PDF…) dans le dossier `preuves/`, avec un nom simple sans espace ni accent, par exemple `audit-reseau-1.pdf`.
2. Dans `index.html`, trouver la ligne du projet dans la liste `blocs`.
3. Ajouter la preuve en 8e position, sous la forme `[["Nom affiché", "preuves/audit-reseau-1.pdf"]]`.
   Si le projet n'a pas de lien en ligne ou de lien GitHub, mettre `null` à leur place.

Exemple :

```js
["Concevoir une solution d'infrastructure réseau",O,"Conception d'un réseau d'entreprise","Plan d'adressage, VLAN…","Packet Tracer, GNS3",null,null,[["Schéma du réseau","preuves/reseau-1.png"]]]
```

## Ajouter un projet

Copier une ligne existante dans le bon bloc et modifier ses colonnes :
compétence, type (`S` site, `A` application, `O` autre projet), titre, description, outils, lien en ligne, lien du code, preuves.
