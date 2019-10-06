### ДИСКРЕТНИ СТРУКТУРИ 2
#### *ТЕОРИЯ 2*

***КСГ***

**1.** Контекстно-свободна граматика. КСГ наричаме следната наредена четворка <img src="https://latex.codecogs.com/svg.latex?\Large&space;G=<V,\sum{,}R,S>">, където:<br>
- <img src="https://latex.codecogs.com/svg.latex?\Large&space;V"> - азбука;
- <img src="https://latex.codecogs.com/svg.latex?\Large&space;\sum\subseteq{V}"> - множество на терминалните символи. <img src="https://latex.codecogs.com/svg.latex?\Large&space;V\setminus\sum"> - множество на нетерминалните символи;
- <img src="https://latex.codecogs.com/svg.latex?\Large&space;R\subseteq(V\setminus\sum)\times{V^{\ast}}"> - крайно множество от правила;
- <img src="https://latex.codecogs.com/svg.latex?\Large&space;S\in{V\setminus{\sum}}"> - начален символ.

**2.** Релацията <img src="https://latex.codecogs.com/svg.latex?\Large&space;\Rightarrow_G"> за дадена контекстно-свободна граматика (КСГ) <img src="https://latex.codecogs.com/svg.latex?\Large&space;G">.<br>Нека <img src="https://latex.codecogs.com/svg.latex?\Large&space;G=<V,\sum{,},R,S>"> е КСГ. За всеки две думи <img src="https://latex.codecogs.com/svg.latex?\Large&space;u,v\in{V^{\ast}}:{\;}u\Rightarrow_Gv"> (за една стъпка) <img src="https://latex.codecogs.com/svg.latex?\Large&space;\stackrel{\text{def.}}{\Leftrightarrow}\exists{x,y\in{V^{\ast}}}"> и <img src="https://latex.codecogs.com/svg.latex?\Large&space;A\in{V\setminus{\sum}}"> : <img src="https://latex.codecogs.com/svg.latex?\Large&space;v=xv'y,{\;}u=xAy"> и правило <img src="https://latex.codecogs.com/svg.latex?\Large&space;A\rightarrow_Gv'">.

**3.** Кога една дума се приема от КСГ <img src="https://latex.codecogs.com/svg.latex?\Large&space;\big(w\in{L(G)\big)}">. Казваме, че <img src="https://latex.codecogs.com/svg.latex?\Large&space;w\in{L(G)}"> т.т.к. от началния символ <img src="https://latex.codecogs.com/svg.latex?\Large&space;S"> за краен брой стъпки се извежда <img src="https://latex.codecogs.com/svg.latex?\Large&space;w"> : <img src="https://latex.codecogs.com/svg.latex?\Large&space;S\Rightarrow_G^{\ast}w">, където <img src="https://latex.codecogs.com/svg.latex?\Large&space;\Rightarow_G^{\ast}"> е рефлексивно и транзитивно затваряне на <img src="https://latex.codecogs.com/svg.latex?\Large&space;\Rightarow_G">. <img src="https://latex.codecogs.com/svg.latex?\Large&space;\big(L(G)=\{w|S\Rightarow_G^{\ast}w"> *и* <img src="https://latex.codecogs.com/svg.latex?\Large&space;w\in{\sum\ast}\}\big)">.

**4.** Граматика в нормална форма на Чомски. Казваме, че КСГ <img src="https://latex.codecogs.com/svg.latex?\Large&space;G=<V,\sum{,}R,S>"> е в нормално форма на Чомски, ако <img src="https://latex.codecogs.com/svg.latex?\Large&space;R\subseteq{(V\setminus{\sum})\times{V^2}}"> <img src="https://latex.codecogs.com/svg.latex?\Large&space;\big(G"> не може да породи дума с дължина по малка от <img src="https://latex.codecogs.com/svg.latex?\Large&space;2\big)">.

**5.** Лемата за разрастването на граматични дървета. Нека <img src="https://latex.codecogs.com/svg.latex?\Large&space;G=<V,\sum{,}R,S>"> е КСГ. За всяка дума <img src="https://latex.codecogs.com/svg.latex?\Large&space;w\in{L(G)}">, т.ч. <img src="https://latex.codecogs.com/svg.latex?\Large&space;|w|>\oint(G)^{|V\setminus{\sum}|}">, съществуват думи <img src="https://latex.codecogs.com/svg.latex?\Large&space;u,v,x,y,z">, такива че <img src="https://latex.codecogs.com/svg.latex?\Large&space;w=u\cdot{v}\cdot{x}\cdot{y}\cdot{z},{\;}v\cdot{y}\neq\epsilon"> и за всяко <img src="https://latex.codecogs.com/svg.latex?\Large&space;i\in{\mathbb{N}_0}:{\;}u\cdot{v^i}\cdot{x\cdot{y^i}}\cdot{z}\in{L(G)}">.

***СТЕКОВ АВТОМАТ***

**1.**
