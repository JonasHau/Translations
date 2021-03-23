<!-- #Fahrenheit to Celsius -->
Cet exercice de programmation est à peu près le même que "Sums in loop", mais nécessite un peu plus de calculs.

<div class="text-center">
	<img alt="fahrenheit and celsius" src="https://codeabbey.github.io/data/fahrenheit_celsius.png"/>
</div>

*Note: le problème [Rounding](./rounding) explique l'algorithme d'arrondi qui sera utilisé dans cet exercice.*

Il existe deux systèmes de mesure de la température très répandus : Celsius et Fahrenheit.
Le premier est assez populaire en Europe et le second bien utilisé aux Etats-Unis par exemple.

Dans l'échelle Celsius, l'eau gèle à 0 degrés et bout à 100 degrés.
Dans l'échelle Fahrenheit, l'eau gèle à 32 degrés et bout à 212 degrés.
Se référer à la page [wikipedia sur le degré Fahrenheit][wiki] pour des explications plus détailées.
Utilisez ces deux points pour la conversion d'autres températures. 

[wiki]: http://fr.wikipedia.org/wiki/Degr%C3%A9_Fahrenheit

Vous devez écrire un programme pour convertir les degrés Fahrenheit en Celsius.

**Input data** Contient `N+1` valeurs. La première étant `N` lui-même (**Notez** que vous ne devriez pas essayer de la convertir).  
**Answer** Devra contenir exactement `N` résultats, arrondis à l'entier le plus proche et séparés par des espaces.

Exemple:

    data:
    5 495 353 168 -39 22
    answer:
    257 178 76 -39 -6

*Veuillez notez que le premier `5` n'est pas une température, mais le nombre de valeurs à convertir*