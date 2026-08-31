# CatDex — correction définitive du bouton « Au hasard » (v4)

Cette version sépare complètement la grille d'accueil et la fiche aléatoire.

- `homeBreeds` contient une copie indépendante de toutes les races.
- Le bouton **Au hasard** n'appelle plus `render()`.
- Il ne modifie plus `shown`.
- Il ne modifie ni `grid.innerHTML`, ni le compteur, ni la recherche.
- Il ouvre uniquement la modale avec `openBreedDirect(b)`.

La grille visible derrière la modale reste donc strictement identique à celle présente avant le clic.
