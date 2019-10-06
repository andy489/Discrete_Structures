### ДИСКРЕТНИ СТРУКТУРИ 2
#### *ТЕОРИЯ 1*

**1.** Регулярен израз <img src="https://latex.codecogs.com/svg.latex?\Large&space;\alpha">. Регулярен израз над азбуката <img src="https://latex.codecogs.com/svg.latex?\Large&space;\sum"> е стринг над азбуката <img src="https://latex.codecogs.com/svg.latex?\Large&space;\sum\cup\{\varnothing{,\cdot},\cup{,}\ast\}">, който може да се дефинира индуктивно както следва:
- <img src="https://latex.codecogs.com/svg.latex?\Large&space;\varnothing"> и всеки елемент от <img src="https://latex.codecogs.com/svg.latex?\Large&space;\sum"> е регулярен израз;
- Ако <img src="https://latex.codecogs.com/svg.latex?\Large&space;\alpha"> и <img src="https://latex.codecogs.com/svg.latex?\Large&space;\beta"> са регулярни изрази, то и <img src="https://latex.codecogs.com/svg.latex?\Large&space;\alpha{\cdot}\beta{,{\;}}\alpha{\cup}\beta"> и <img src="https://latex.codecogs.com/svg.latex?\Large&space;\alpha^{\ast}"> са реулярни изрази;
- Нищо друго не е регулярен израз, освен ако не следва от първите две условия.

**2.** Регулярен език <img src="https://latex.codecogs.com/svg.latex?\Large&space;L(\alpha)"> за регулярен израз <img src="https://latex.codecogs.com/svg.latex?\Large&space;\alpha">. <img src="https://latex.codecogs.com/svg.latex?\Large&space;L"> е функцията, която описва връзката между регулярен израз и езика, който той задава. <img src="https://latex.codecogs.com/svg.latex?\Large&space;L"> е дефинирана индуктивно както следва:
- <img src="https://latex.codecogs.com/svg.latex?\Large&space;L(\varnothing)=\varnothing{,{\;}}L(a)=\{a\}{\;}">, за всяко <img src="https://latex.codecogs.com/svg.latex?\Large&space;a\in{\sum}"> (дори и за <img src="https://latex.codecogs.com/svg.latex?\Large&space;a=\epsilon">);
- Ако <img src="https://latex.codecogs.com/svg.latex?\Large&space;\alpha"> и <img src="https://latex.codecogs.com/svg.latex?\Large&space;\beta"> са регулярни изрази, то <img src="https://latex.codecogs.com/svg.latex?\Large&space;L(\alpha{\cdot}\beta)=L(\alpha)\cdot{L(\beta)},{\;}L(\alpha\cup\beta)=L(\alpha)\cup{L(\beta)},{\;}L(\alpha^{\ast})=\big(L(\alpha)\big)^{\ast}">.
