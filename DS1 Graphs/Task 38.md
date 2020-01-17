## Задача 38.

Нека <img src="https://latex.codecogs.com/svg.latex?\Large&space;G"> е граф с <img src="https://latex.codecogs.com/svg.latex?\Large&space;2n+1"> върха <img src="https://latex.codecogs.com/svg.latex?\Large&space;n\ge{2}">, в който всеки връх е от степен поне <img src="https://latex.codecogs.com/svg.latex?\Large&space;n">. Докажете, че <img src="https://latex.codecogs.com/svg.latex?\Large&space;G"> е свързан.

*Док-во:*

Нека <img src="https://latex.codecogs.com/svg.latex?\Large&space;G"> не е свързан и нека <img src="https://latex.codecogs.com/svg.latex?\Large&space;u\neq{v}"> са два върха от различни компоненти на свързаност. Тоест между <img src="https://latex.codecogs.com/svg.latex?\Large&space;u"> и <img src="https://latex.codecogs.com/svg.latex?\Large&space;v"> не съществува път, както и никои връх <img src="https://latex.codecogs.com/svg.latex?\Large&space;v_k"> не е свързан с <img src="https://latex.codecogs.com/svg.latex?\Large&space;v_s,k,s=\overline{1,n}">.

![](https://github.com/andy489/Data_Structures_and_Algorithms_CPP/blob/master/assets/Graphs%20DS1%2001.png)

От условието следва, че във всяка компонента на свързаност ще има поне <img src="https://latex.codecogs.com/svg.latex?\Large&space;n+1"> върха:

<img src="https://latex.codecogs.com/svg.latex?\Large&space;k(n+1)=2n+1">, но <img src="https://latex.codecogs.com/svg.latex?\Large&space;2(n+1)\le{k(n+1)=2n+1}"> от допускането <img src="https://latex.codecogs.com/svg.latex?\Large&space;\Rightarrow{2}\le{1}">, което е противоречие с допускането и следователно <img src="https://latex.codecogs.com/svg.latex?\Large&space;G"> е свързан граф.
