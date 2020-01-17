## Задача 34.

Нека <img src="https://latex.codecogs.com/svg.latex?\Large&space;G"> е дърво, в което има върхове само от степен <img src="https://latex.codecogs.com/svg.latex?\Large&space;1,2"> и <img src="https://latex.codecogs.com/svg.latex?\Large&space;4">. Докажете, че броят на върховете от степен <img src="https://latex.codecogs.com/svg.latex?\Large&space;1"> е с две по-голям от удвоения брой на върховете от степен <img src="https://latex.codecogs.com/svg.latex?\Large&space;4">.

*Док-во:*

Нека отново с <img src="https://latex.codecogs.com/svg.latex?\Large&space;N(i)"> бележим броя на върховете от степен <img src="https://latex.codecogs.com/svg.latex?\Large&space;i">. От това, че <img src="https://latex.codecogs.com/svg.latex?\Large&space;G"> е дърво следва, че <img src="https://latex.codecogs.com/svg.latex?\Large&space;|V|=|E|+1">, a от формулата на Ойлер имаме, че <img src="https://latex.codecogs.com/svg.latex?\Large&space;2|E|=\sum_{u\in{V}}deg(u);">

<img src="https://latex.codecogs.com/svg.latex?\Large&space;2(|V|-1)=2|E|=\sum_{u\in{V}}deg(u)=N(1).1+N(2).2+N(4).4">

<img src="https://latex.codecogs.com/svg.latex?\Large&space;2(N(1)+N(2)+N(4)-1)=N(1)+N(2).2+N(4).4">. T.e.

<img src="https://latex.codecogs.com/svg.latex?\Large&space;N(1)=2.N(4)+2">, което искахме да докажем.
