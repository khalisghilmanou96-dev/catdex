# CatDex — version corrigée

Cette version évite le 403 de The Cat API.

- Races : https://catfact.ninja/breeds
- Images : https://cataas.com/
- Aucune clé API
- Compatible GitHub Pages
- CSS et JavaScript directement intégrés dans index.html

Important : Cataas fournit des photos de chats génériques ; elles ne correspondent pas nécessairement exactement à la race affichée.


## Correction bouton Au hasard
Le bouton **Au hasard** ouvre maintenant directement la fiche d’un chat aléatoire sans remplacer la grille d’accueil en arrière-plan.


## Correction v2 bouton Au hasard
Le bouton **Au hasard** n'appelle plus `render([b])` et ne modifie plus la variable `shown`. Il ouvre uniquement la modale via `openBreedDirect(b)`, donc la grille complète reste visible en arrière-plan.
