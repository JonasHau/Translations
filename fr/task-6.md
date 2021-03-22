When program deals with numbers which have fraction part we sometimes want to **round** such values to whole
integer. We'll need this for programming some later problems (to make answers simpler, for example), so let us
have the following dedicated exercise to learn this trick.

There are several pairs of numbers. For each pair you are to divide first by second and return
the result, rounded **to the nearest** integer.

Dans le cas où la partie fractionnaire du résultat est exactement `0.5`, la valeur devra être arrondie vers le haut (c.-à-d., en ajoutant `0.5`).
A noter que pour une valeur négative, "plus grand" signifie "plus proche de zéro".
Se référer à la page Wikipédia [Rounding](http://en.wikipedia.org/wiki/Rounding#Round_half_up) pour des explications plus détailées.

Si l'arrondi est cité dans tout autre problème, le même algorithme d'arrondi est attendu (sauf si un autre est explicitement spécifié).

**Input data** Contient sur la première ligne le nombre `N` de cas à traiter.  
Les `N` lignes suivantes contiennent chacune un cas à tester (c.-à-d., une paire de nombres).  
**Answer** Devra contenir le résultat de la division, arrondi, pour chaque paire, séparatés par des espaces

Exemple:

	input data:
	3
	12 8
	11 -3
	400 5
	
	answer:
	2 -4 80