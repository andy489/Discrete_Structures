## Задача 22. 

Изполвайте алгоритъма на Дейкстра, за да намерите дължините на най-кратките пътища от върха <img src="https://latex.codecogs.com/svg.latex?\Large&space;A"> до останалите върхове в графа:
![](https://github.com/andy489/Data_Structures_and_Algorithms_CPP/blob/master/assets/Dijkstra%20DS1%2004.png)

A|B|C|D|E|F|непосетени
-|-|-|-|-|-|-
<img src="https://latex.codecogs.com/svg.latex?\Large&space;\boxed{0}">|<img src="https://latex.codecogs.com/svg.latex?\Large&space;\infty">|<img src="https://latex.codecogs.com/svg.latex?\Large&space;\infty">|<img src="https://latex.codecogs.com/svg.latex?\Large&space;\infty">|<img src="https://latex.codecogs.com/svg.latex?\Large&space;\infty">|<img src="https://latex.codecogs.com/svg.latex?\Large&space;\infty">|<img src="https://latex.codecogs.com/svg.latex?\Large&space;A,B,C,D,E,F">
-|<img src="https://latex.codecogs.com/svg.latex?\Large&space;\boxed{4}">|<img src="https://latex.codecogs.com/svg.latex?\Large&space;\infty">|<img src="https://latex.codecogs.com/svg.latex?\Large&space;\infty">|<img src="https://latex.codecogs.com/svg.latex?\Large&space;\infty">|4|<img src="https://latex.codecogs.com/svg.latex?\Large&space;B,C,D,E,F">
-|-|9|<img src="https://latex.codecogs.com/svg.latex?\Large&space;\infty">|10|<img src="https://latex.codecogs.com/svg.latex?\Large&space;\boxed{4}">|<img src="https://latex.codecogs.com/svg.latex?\Large&space;C,D,E,F">
-|-|7|<img src="https://latex.codecogs.com/svg.latex?\Large&space;\boxed{5}">|6|-|<img src="https://latex.codecogs.com/svg.latex?\Large&space;C,D,E">
-|-|7|-|<img src="https://latex.codecogs.com/svg.latex?\Large&space;\boxed{6}">|-|<img src="https://latex.codecogs.com/svg.latex?\Large&space;C,E">
-|-|<img src="https://latex.codecogs.com/svg.latex?\Large&space;\boxed{7}">|-|-|-|<img src="https://latex.codecogs.com/svg.latex?\Large&space;C">
-|-|-|-|-|-|<img src="https://latex.codecogs.com/svg.latex?\Large&space;\varnothing">
