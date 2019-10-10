## Задача 8.

Докажете, че за <img src="https://latex.codecogs.com/svg.latex?\Large&space;\forall{A,B,C}"> е изпълнено <img src="https://latex.codecogs.com/svg.latex?\Large&space;A\setminus{(B\cup{C})}=(A\setminus{C})\setminus{(B\setminus{C})}">.

*Док-во:*<br><img src="https://latex.codecogs.com/svg.latex?\Large&space;(\subseteq)"> Нека <img src="https://latex.codecogs.com/svg.latex?\Large&space;x\in{A\setminus{(B\cup{C})}}\Rightarrow{x\in{A}}"> и <img src="https://latex.codecogs.com/svg.latex?\Large&space;x\notin{\underbrace{B\cup{C}}\Rightarrow{x\notin{B}}"> и <img src="https://latex.codecogs.com/svg.latex?\Large&space;x\notin{C}">. Ще докажем, че <img src="https://latex.codecogs.com/svg.latex?\Large&space;x\in{(A\setminus{C})}\setminus{(B\setminus{C})}">.

От <img src="https://latex.codecogs.com/svg.latex?\Large&space;x\in{A}"> и <img src="https://latex.codecogs.com/svg.latex?\Large&space;x\notin{C}\Rightarrow{\underline{x\in{A\setminus{C}}}}{\;}"> *(1)*<br>
От <img src="https://latex.codecogs.com/svg.latex?\Large&space;x\notin{B}"> и <img src="https://latex.codecogs.com/svg.latex?\Large&space;x\notin{C}\Rightarrow{\underline{x\notin{B\setminus{C}}}}{\;}"> *(2)*

От *(1)* и *(2)* <img src="https://latex.codecogs.com/svg.latex?\Large&space;\Rightarrow{x\in{(A\setminus{C})\setminus{{(B\setminus{C})}}}}">.

<img src="https://latex.codecogs.com/svg.latex?\Large&space;(\supseteq)"> Нека <img src="https://latex.codecogs.com/svg.latex?\Large&space;x\in(A\setminus{C})\setminus{(B\setminus{C})}\Rightarrow{\underbrace{x\in{A\setminus{C}}}_{(\ast)}}"> и <img src="https://latex.codecogs.com/svg.latex?\Large&space;\underbrace{x\notin{B\setminus{C}}}_{(\ast\ast)}">.<br>
От <img src="https://latex.codecogs.com/svg.latex?\Large&space;(\ast)\Rightarrow{x\in{A}}"> и <img src="https://latex.codecogs.com/svg.latex?\Large&space;x\notin{C}">; От <img src="https://latex.codecogs.com/svg.latex?\Large&space;(\ast\ast)\Rightarrow{x\notin{B}}"> или <img src="https://latex.codecogs.com/svg.latex?\Large&space;x\in{B}"> и <img src="https://latex.codecogs.com/svg.latex?\Large&space;x\in{C}">, но от <img src="https://latex.codecogs.com/svg.latex?\Large&space;(\ast)\Rightarrow{x\notin{C}}\Rightarrow{x\notin{B}}">.<br>Имаме, че <img src="https://latex.codecogs.com/svg.latex?\Large&space;x\int{A},{\;}x\notin{C}"> и <img src="https://latex.codecogs.com/svg.latex?\Large&space;x\notin{B}\Rightarrow{x\notin{B\cup{C}}}\Rightarrow{x\in{A\setminus{(B\cup{C})}}}">.



