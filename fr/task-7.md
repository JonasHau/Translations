<!-- #Fahrenheit to Celsius -->
Cet exercice de programmation est à peu près le même que "counting sums in loop", mais nécessite un peu plus de calculs.

<div class="text-center">
	<img alt="fahrenheit and celsius" src="https://codeabbey.github.io/data/fahrenheit_celsius.png"/>
</div>

*Note: le problème [Rounding](./rounding) explique l'algorithme d'arrondi qui sera utilisé dans cet exercice.*

Il existe deux systèmes de mesure de la température très répandus : Celsius et Fahrenheit.
Le premier est assez populaire en Europe et le second bien utilisé aux Etats-Unis par exemple.

By Celsius scale water freezes at 0 degrees and boils at 100 degrees. By Fahrenheit water freezes
at 32 degrees and boils at 212 degrees. You may learn more from [wikipedia on Fahrenheit][wiki]. Use these two points
for conversion of other temperatures.

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