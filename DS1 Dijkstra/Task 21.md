## Задача 21. 

Намерете теглата на най-леките пътища от върха <img src="https://latex.codecogs.com/svg.latex?\Large&space;A"> до останалите върхове в графа:

![](https://github.com/andy489/Data_Structures_and_Algorithms_CPP/blob/master/assets/Dijkstra%20DS1%2002.png)

Алгоритъм на Дейкстра:

A|B|C|D|E|F|непосетени
-|-|-|-|-|-|-
<img src="https://latex.codecogs.com/svg.latex?\Large&space;\boxed{0}">|<img src="https://latex.codecogs.com/svg.latex?\Large&space;\infty">|<img src="https://latex.codecogs.com/svg.latex?\Large&space;\infty">|<img src="https://latex.codecogs.com/svg.latex?\Large&space;\infty">|<img src="https://latex.codecogs.com/svg.latex?\Large&space;\infty">|<img src="https://latex.codecogs.com/svg.latex?\Large&space;\infty">|<img src="https://latex.codecogs.com/svg.latex?\Large&space;A,B,C,D,E,F">
-|<img src="https://latex.codecogs.com/svg.latex?\Large&space;\boxed{7}">|<img src="https://latex.codecogs.com/svg.latex?\Large&space;\infty">|9|14|<img src="https://latex.codecogs.com/svg.latex?\Large&space;\infty">|<img src="https://latex.codecogs.com/svg.latex?\Large&space;B,C,D,E,F">
-|-|22|<img src="https://latex.codecogs.com/svg.latex?\Large&space;\boxed{9}">|14|<img src="https://latex.codecogs.com/svg.latex?\Large&space;\infty">|<img src="https://latex.codecogs.com/svg.latex?\Large&space;C,D,E,F">
-|-|20|-|<img src="https://latex.codecogs.com/svg.latex?\Large&space;\boxed{11}">|<img src="https://latex.codecogs.com/svg.latex?\Large&space;\infty">|<img src="https://latex.codecogs.com/svg.latex?\Large&space;C,E,F">
-|-|20|-|-|<img src="https://latex.codecogs.com/svg.latex?\Large&space;\boxed{20}">|<img src="https://latex.codecogs.com/svg.latex?\Large&space;C,F">
-|-|20|-|-|-|<img src="https://latex.codecogs.com/svg.latex?\Large&space;C">
-|-|-|-|-|-|<img src="https://latex.codecogs.com/svg.latex?\Large&space;\varnothing">
