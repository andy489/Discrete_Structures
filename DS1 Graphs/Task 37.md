## Задача 37.

Граф с общо <img src="https://latex.codecogs.com/svg.latex?\Large&space;n"> върха има <img src="https://latex.codecogs.com/svg.latex?\Large&space;7"> върха от степен <img src="https://latex.codecogs.com/svg.latex?\Large&space;n-1">
, <img src="https://latex.codecogs.com/svg.latex?\Large&space;3"> върха от степен <img src="https://latex.codecogs.com/svg.latex?\Large&space;n-2"> и <img src="https://latex.codecogs.com/svg.latex?\Large&space;13"> върха от степен <img src="https://latex.codecogs.com/svg.latex?\Large&space;n-3">. Всеки връх със степен по-малка от <img src="https://latex.codecogs.com/svg.latex?\Large&space;n-3"> е с четна степен. Да се докаже, че графът има четен брой върхове.

*Док-во:*

<img src="https://latex.codecogs.com/svg.latex?\Large&space;(I)"> От формулата на Ойлер следва, че броят на върховете с нечетна степен е четно число [(зад. 26)](https://github.com/andy489/Discrete_Structures/blob/master/DS1%20Graphs/Task%2026.md). Сега, да допуснем, че броят <img src="https://latex.codecogs.com/svg.latex?\Large&space;n"> на върховете на графа е нечетно число. Тогава <img src="https://latex.codecogs.com/svg.latex?\Large&space;n-1"> и <img src="https://latex.codecogs.com/svg.latex?\Large&space;n-3"> са четни, а <img src="https://latex.codecogs.com/svg.latex?\Large&space;n-2"> е нечетно. Следователно единствените върхове от нечетна степен са тези със степен <img src="https://latex.codecogs.com/svg.latex?\Large&space;n-2">. Техният брой, обаче е <img src="https://latex.codecogs.com/svg.latex?\Large&space;3">, което не е четно. Противоречие. Следователно <img src="https://latex.codecogs.com/svg.latex?\Large&space;n"> е четно.

<img src="https://latex.codecogs.com/svg.latex?\Large&space;(II)"> Втори подход: отново от формула на Ойлер:<br>
<img src="https://latex.codecogs.com/svg.latex?\Large&space;2|E|=7(n-1)+3(n-2)+13(n-3)"> - четно<br>
<img src="https://latex.codecogs.com/svg.latex?\Large&space;2|E|=23n-52+even">, т.к. <img src="https://latex.codecogs.com/svg.latex?\Large&space;gcd(2,23)=0">, то <img src="https://latex.codecogs.com/svg.latex?\Large&space;2|n">.
