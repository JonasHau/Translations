<!-- #Triangles -->
Un triangle est un objet construit à part de trois segments (les côtés du triangle), connectés par leurs bouts.
[La page Wikipédia sur le triangle][wiki] donne des explications détaillées.
Si l'on prend trois segments de longeurs `A B C` - soit nous pouvons construire un triangle avec (par exemple avec `3 4 5` ou `3 4 7` - cependant ce triangle a une surface de 0), soit il est impossible de construire un triangle (par exemple avec `1 2 4`).

[wiki]: https://fr.wikipedia.org/wiki/Triangle

You are given several triplets of values representing lengths of the sides of triangles.
Vous devez dire avec quels triplés il est possible de construire un triangle et avec lesquels ce n'est pas possible.

**Input data:** la première ligne contient le nombre de triplés.
Les autres lignes contiennent les triplés eux-mêmes (chacun sur une ligne).
**Answer:** Vous devez retourner `1` ou `0` pour chaque triplé (`1` si le triangle peut être construit et `0`
autrement).

Exemple:

    data:
    2
    3 4 5
    1 2 4
    
    answer:
    1 0