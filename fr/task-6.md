Quand un programme traite des nombres qui ont une partie fractionnaire, nous voulons parfois **arrondir** ces valeurs à un nombre entier.
Nous en aurons besoin pour programmer certains problèmes ultérieurs (p. ex., pour simplifier les réponses), alors nous allons faire l'exercice suivant pour apprendre cette astuce.

Plusieurs paires de nombres vous serons fournies. Pour chaque paire, vous devez diviser le premier nombre par le second, puis retourner le résultat arrondi **à l'entier le plus proche**.

Dans le cas où la partie fractionnaire du résultat vaut exactement `0.5`, la valeur devra être arrondie vers le haut (c.-à-d., en y ajoutant `0.5`).
A noter que pour une valeur négative, "vers le haut" signifie "plus proche de zéro".
Se référer à la page Wikipédia [Rounding](http://en.wikipedia.org/wiki/Rounding#Round_half_up) pour des explications plus détailées.

Si l'arrondi est cité dans tout autre problème, le même algorithme d'arrondi est attendu (sauf si un autre est explicitement spécifié).

**Input data** Contient sur la première ligne le nombre `N` de cas à traiter.  
Les `N` lignes suivantes contiennent chacune un cas à tester (c.-à-d., une paire de nombres).  
**Answer** Devra contenir le résultat de la division arrondi pour chaque paire, séparés par des espaces.

Exemple:

	input data:
	3
	12 8
	11 -3
	400 5
	
	answer:
	2 -4 80