## Задача 21. 

Изполвайте алгоритъма на Дейкстра, за да намерите дължините на най-кратките пътища от върха <img src="https://latex.codecogs.com/svg.latex?\Large&space;A"> до останалите върхове в графа:

![](https://github.com/andy489/Data_Structures_and_Algorithms_CPP/blob/master/assets/Dijkstra%20DS1%2003.png)

A|B|C|D|E|F|G|H|непосетени
-|-|-|-|-|-|-|-|-
<img src="https://latex.codecogs.com/svg.latex?\Large&space;\boxed{0}">|<img src="https://latex.codecogs.com/svg.latex?\Large&space;\infty">|<img src="https://latex.codecogs.com/svg.latex?\Large&space;\infty">|<img src="https://latex.codecogs.com/svg.latex?\Large&space;\infty">|<img src="https://latex.codecogs.com/svg.latex?\Large&space;\infty">|<img src="https://latex.codecogs.com/svg.latex?\Large&space;\infty">|<img src="https://latex.codecogs.com/svg.latex?\Large&space;\infty">|<img src="https://latex.codecogs.com/svg.latex?\Large&space;\infty">|<img src="https://latex.codecogs.com/svg.latex?\Large&space;A,B,C,D,E,F,G,H">
-|<img src="https://latex.codecogs.com/svg.latex?\Large&space;\boxed{2}">|5|4|<img src="https://latex.codecogs.com/svg.latex?\Large&space;\infty">|<img src="https://latex.codecogs.com/svg.latex?\Large&space;\infty">|<img src="https://latex.codecogs.com/svg.latex?\Large&space;\infty">|<img src="https://latex.codecogs.com/svg.latex?\Large&space;\infty">|<img src="https://latex.codecogs.com/svg.latex?\Large&space;B,C,D,E,F,G,H">
-|-|<img src="https://latex.codecogs.com/svg.latex?\Large&space;\boxed{4}">|4|9|<img src="https://latex.codecogs.com/svg.latex?\Large&space;\infty">|<img src="https://latex.codecogs.com/svg.latex?\Large&space;\infty">|14|<img src="https://latex.codecogs.com/svg.latex?\Large&space;C,D,E,F,G,H">
-|-|-|<img src="https://latex.codecogs.com/svg.latex?\Large&space;\boxed{4}">|8|7|<img src="https://latex.codecogs.com/svg.latex?\Large&space;\infty">|14|<img src="https://latex.codecogs.com/svg.latex?\Large&space;D,E,F,G,H">
-|-|-|-|8|<img src="https://latex.codecogs.com/svg.latex?\Large&space;\boxed{7}">|<img src="https://latex.codecogs.com/svg.latex?\Large&space;\infty">|14|<img src="https://latex.codecogs.com/svg.latex?\Large&space;E,F,G<H">
-|-|-|-|<img src="https://latex.codecogs.com/svg.latex?\Large&space;\boxed{8}">|-|14|14|<img src="https://latex.codecogs.com/svg.latex?\Large&space;E,G,H">
-|-|-|-|-|-|<img src="https://latex.codecogs.com/svg.latex?\Large&space;\boxed{13}">|14|<img src="https://latex.codecogs.com/svg.latex?\Large&space;G,H">
-|-|-|-|-|-|-|<img src="https://latex.codecogs.com/svg.latex?\Large&space;\boxed{14}">|<img src="https://latex.codecogs.com/svg.latex?\Large&space;H">
-|-|-|-|-|-|-|-|<img src="https://latex.codecogs.com/svg.latex?\Large&space;\varnothing">
