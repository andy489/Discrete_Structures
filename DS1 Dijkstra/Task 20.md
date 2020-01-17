## Задача 20. 

Намерете теглата на най-леките пътища от върха <img src="https://latex.codecogs.com/svg.latex?\Large&space;A"> до останалите върхове в графа:

![](https://github.com/andy489/Data_Structures_and_Algorithms_CPP/blob/master/assets/Dijkstra%20DS1%2001.png)

Алгоритъм на Дейкстра:

<img src="https://latex.codecogs.com/svg.latex?\Large&space;\boxed{A}">|B|C|D|E|F|G|H|непосетени
-|-|-|-|-|-|-|-|-
<img src="https://latex.codecogs.com/svg.latex?\Large&space;\boxed{0}">|<img src="https://latex.codecogs.com/svg.latex?\Large&space;\infty">|<img src="https://latex.codecogs.com/svg.latex?\Large&space;\infty">|<img src="https://latex.codecogs.com/svg.latex?\Large&space;\infty">|<img src="https://latex.codecogs.com/svg.latex?\Large&space;\infty">|<img src="https://latex.codecogs.com/svg.latex?\Large&space;\infty">|<img src="https://latex.codecogs.com/svg.latex?\Large&space;\infty">|<img src="https://latex.codecogs.com/svg.latex?\Large&space;\infty">|<img src="https://latex.codecogs.com/svg.latex?\Large&space;A,B,C,D,E,F,G,H">
-|6|<img src="https://latex.codecogs.com/svg.latex?\Large&space;\boxed{3}">|6|<img src="https://latex.codecogs.com/svg.latex?\Large&space;\infty">|<img src="https://latex.codecogs.com/svg.latex?\Large&space;\infty">|<img src="https://latex.codecogs.com/svg.latex?\Large&space;\infty">|10|<img src="https://latex.codecogs.com/svg.latex?\Large&space;B,C,D,E,F,G,H">
-|5|-|<img src="https://latex.codecogs.com/svg.latex?\Large&space;\boxed{4}">|<img src="https://latex.codecogs.com/svg.latex?\Large&space;\infty">|<img src="https://latex.codecogs.com/svg.latex?\Large&space;\infty">|<img src="https://latex.codecogs.com/svg.latex?\Large&space;\infty">|10|<img src="https://latex.codecogs.com/svg.latex?\Large&space;B,D,E,F,G,H">
-|<img src="https://latex.codecogs.com/svg.latex?\Large&space;\boxed{5}">|-|-|13|<img src="https://latex.codecogs.com/svg.latex?\Large&space;\infty">|9|5|<img src="https://latex.codecogs.com/svg.latex?\Large&space;B,E,F,G,H">
-|-|-|-|13|<img src="https://latex.codecogs.com/svg.latex?\Large&space;\infty">|9|<img src="https://latex.codecogs.com/svg.latex?\Large&space;\boxed{5}">|<img src="https://latex.codecogs.com/svg.latex?\Large&space;E,F,G,H">
-|-|-|-|13|<img src="https://latex.codecogs.com/svg.latex?\Large&space;\infty">|<img src="https://latex.codecogs.com/svg.latex?\Large&space;\boxed{9}">|-|<img src="https://latex.codecogs.com/svg.latex?\Large&space;E,F,G">
-|-|-|-|13|<img src="https://latex.codecogs.com/svg.latex?\Large&space;\boxed{12}">|-|-|<img src="https://latex.codecogs.com/svg.latex?\Large&space;E,F">
-|-|-|-|<img src="https://latex.codecogs.com/svg.latex?\Large&space;\boxed{13}">|-|-|-|<img src="https://latex.codecogs.com/svg.latex?\Large&space;E">
-|-|-|-|-|-|-|-|<img src="https://latex.codecogs.com/svg.latex?\Large&space;\varnothing">
