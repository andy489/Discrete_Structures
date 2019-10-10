## Задача 07.

Докажете, че за <img src="https://latex.codecogs.com/svg.latex?\Large&space;\forall{A,B,C}"> е в сила, че <img src="https://latex.codecogs.com/svg.latex?\Large&space;(A\cup{B})\cap{C}=A\cup{(B\cap{C})}\Leftrightarrow{A\subseteq{C}}">.

*Док-во:*<br>
<img src="https://latex.codecogs.com/svg.latex?\Large&space;(\Rightarrow)"> Нека <img src="https://latex.codecogs.com/svg.latex?\Large&space;A,B,C"> са такива, че <img src="https://latex.codecogs.com/svg.latex?\Large&space;(A\cup{B})\cap{C}=A\cup{(B\cap{C})}">. Ще покажем, че <img src="https://latex.codecogs.com/svg.latex?\Large&space;A\subseteq{C}">.<br>
За целта нека <img src="https://latex.codecogs.com/svg.latex?\Large&space;x\in{A}"> е произволен елемент. Тогава <img src="https://latex.codecogs.com/svg.latex?\Large&space;x\in{A}\subseteq{A\cup{(B\cap{C})}}=(A\cup{B})\cap{\underline{\underline{C}}}"> , следователно <img src="https://latex.codecogs.com/svg.latex?\Large&space;x\in{C}">. T.e. за произволно <img src="https://latex.codecogs.com/svg.latex?\Large&space;x\in{A}"> доказахме, че <img src="https://latex.codecogs.com/svg.latex?\Large&space;x\in{C}\Rightarrow{A\subseteq{C}}">.

<img src="https://latex.codecogs.com/svg.latex?\Large&space;(\Leftarrow)"> Нека <img src="https://latex.codecogs.com/svg.latex?\Large&space;A\subseteq{C}">. Ще покажем, че <img src="https://latex.codecogs.com/svg.latex?\Large&space;(A\cup{B})\cap{C}=a\cup{(B\cap{C})}">.

<img src="https://latex.codecogs.com/svg.latex?\Large&space;(\subseteq)"> Нека <img src="https://latex.codecogs.com/svg.latex?\Large&space;x\in{(A\cup{B})\cap{C}}">. Тогава <img src="https://latex.codecogs.com/svg.latex?\Large&space;x\in{(A\cup{B})}"> и <img src="https://latex.codecogs.com/svg.latex?\Large&space;x\in{C}">.
- Ако <img src="https://latex.codecogs.com/svg.latex?\Large&space;x\in{A}">, то <img src="https://latex.codecogs.com/svg.latex?\Large&space;x\in{A\cup{(B\cap{C})}}">
- Ако <img src="https://latex.codecogs.com/svg.latex?\Large&space;x\notin{A}">, то <img src="https://latex.codecogs.com/svg.latex?\Large&space;x\in{B}(x\in{A\cup{B}})"><br><img src="https://latex.codecogs.com/svg.latex?\Large&space;\Rightarrow{x\in{B\cap{C}}}\Rightarrow{x\in{A\cup{(B\cap{C})}}}\Rightarrow{(A\cup{B})\cap{C}}\subseteq{A\cup{(B\cap{C})}}"> (тук никъде не използвахме, че <img src="https://latex.codecogs.com/svg.latex?\Large&space;A\subseteq{C}">)

<img src="https://latex.codecogs.com/svg.latex?\Large&space;(\supseteq)"> Нека <img src="https://latex.codecogs.com/svg.latex?\Large&space;x\in{A\cup{(B\cap{C})}}">
- Ако <img src="https://latex.codecogs.com/svg.latex?\Large&space;x\in{A}">, то <img src="https://latex.codecogs.com/svg.latex?\Large&space;x\in{A\cup{B}}(A\subseteq{A\cup{B}})">. Но <img src="https://latex.codecogs.com/svg.latex?\Large&space;(A\subseteq{C}"> по условие <img src="https://latex.codecogs.com/svg.latex?\Large&space;\Rightarrow{x\in{(A\cup{B})}}\cap{C}">.
- Ако <img src="https://latex.codecogs.com/svg.latex?\Large&space;x\notin{A},{\;}x\in{(B\cap{C})}\Rightarrow{\underbrace{x\in{B}}_{\underbrace{x\in{A\cup{B}}}_{x\in{(A\cup{B})\cap{C}}}}}"> и <img src="https://latex.codecogs.com/svg.latex?\Large&space;x\in{C}">.
