### Задача 03. 
Да се докаже, че <img src="https://latex.codecogs.com/svg.latex?\Large&space;\forall{A,B}"> е изпълнено <img src="https://latex.codecogs.com/svg.latex?\Large&space;A\setminus{B}=A\setminus{(A\cap{B})|">.

*Док-во:* <br>
Нека <img src="https://latex.codecogs.com/svg.latex?\Large&space;A"> и <img src="https://latex.codecogs.com/svg.latex?\Large&space;B"> с произволни множества.

<img src="https://latex.codecogs.com/svg.latex?\Large&space;(\subseteq)"> Нека елемента <img src="https://latex.codecogs.com/svg.latex?\Large&space;x\in{A\setminus{B}}"> е произволен <img src="https://latex.codecogs.com/svg.latex?\Large&space;\Rightarrow{x\in{A}}"> и <img src="https://latex.codecogs.com/svg.latex?\Large&space;x\notin{B}">. Тогава <img src="https://latex.codecogs.com/svg.latex?\Large&space;x\in{A\cap{B}}"> и <img src="https://latex.codecogs.com/svg.latex?\Large&space;x\in{A}">, следователно <img src="https://latex.codecogs.com/svg.latex?\Large&space;x\in{A}\setminus{(A\cap{B})}">. Тъй като <img src="https://latex.codecogs.com/svg.latex?\Large&space;x"> беше произволно, то <img src="https://latex.codecogs.com/svg.latex?\Large&space;A\setminus{B}\subseteq{A\setminus{(A\cap{B})}}">.

<img src="https://latex.codecogs.com/svg.latex?\Large&space;(\supseteq)"> Нека елемента <img src="https://latex.codecogs.com/svg.latex?\Large&space;y\in{A\setminus{(A\cap{B})}}\Rightarrow{y\in{A}}"> и <img src="https://latex.codecogs.com/svg.latex?\Large&space;\underbrace{y\notin{A\cap{B}}}_{}\Rightarrow{y\notin{B}}">, защото <img src="https://latex.codecogs.com/svg.latex?\Large&space;y\in{A}\Rightarrow{y\in{A\setminus{B}}}">. <img src="https://latex.codecogs.com/svg.latex?\Large&space;y">-птоизволен <img src="https://latex.codecogs.com/svg.latex?\Large&space;\Rightarrow{A\setminus{(A\cap{B})}}\subseteq{A\setminus{B}}">.

От <img src="https://latex.codecogs.com/svg.latex?\Large&space;(\subseteq)"> и <img src="https://latex.codecogs.com/svg.latex?\Large&space;(\supseteq)"> следва, че <img src="https://latex.codecogs.com/svg.latex?\Large&space;A\setminus{B}=A\setminus{(A\cap{B})|">.
