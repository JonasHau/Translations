Quand nous parlons de **suite arithmétique** (ou séquence arithmétique), nous entendons une série
de nombres avec une propriété spéciale - chaque valeur est plus grande que la précédente, d'une valeur prédéfinie (le pas).

La différence entre les valeurs `(K+1)` et `K` est donc constante. Voici des exemples de séquences

	1 2 3 4 5 6 7 ...
	4 6 8 10 12 14 16...
	10 13 16 19 22 25 28...

Dès lors, la séquence arithmétique est entièrement définie par son premier terme (`A`) et la
valeur d'incrémentation - le pas - (`B`). Les premiers termes pourraient être exprimés comme suit

    A + (A + B) + (A + 2B) + (A + 3B) + ...

Vous devez calculer la somme des premiers termes de la séquence arithmétique.
[la page Wikipédia][wiki] sur la suite arithmétique pourrait être d'une grande aide pour celui
qui rencontre les séquences arithmétiques pour la première fois.

[wiki]: http://fr.wikipedia.org/wiki/Suite_arithm%C3%A9tique

**Input data:** la première ligne contient le nombre de cas à traiter.  
Les autres lignes contiennent les cas à traiter sous la forme de triplets des valeurs `A B N` où `A` est le premier terme de la séquence,
`B` est le pas et `N` est le nombre de terme à prendre en compte.  
**Answer:** vous devez retourner le résultat (la somme des `N` premiers termes) de chaque séquence, séparés par des espaces.

Exemple:

    data:
    2
    5 2 3
    3 0 10
    
    answer:
    21 30

_Explications de l'exemple. Dans le premier cas, nous avons une séquence commençant par `5` et grandissant de `2` à chaque terme.
Nous voulons faire la somme des `3` premiers termes de la séquence `5 + 7 + 9 = 21`. La seconde séquence est plus simple. Elle commence par `3` et grandit de `0`,
ce qui donne `3 + 3 + ... + 3 = 30` (un total de `10` termes)._