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

**5.** Лемата за разрастването на граматични дървета. Нека <img src="https://latex.codecogs.com/svg.latex?\Large&space;G=<V,\sum{,}R,S>"> е КСГ. За всяка дума <img src="https://latex.codecogs.com/svg.latex?\Large&space;w\in{L(G)}">, т.ч. <img src="https://latex.codecogs.com/svg.latex?\Large&space;|w|>\Phi(G)^{|V\setminus{\sum}|}">, съществуват думи <img src="https://latex.codecogs.com/svg.latex?\Large&space;u,v,x,y,z">, такива че <img src="https://latex.codecogs.com/svg.latex?\Large&space;w=u\cdot{v}\cdot{x}\cdot{y}\cdot{z},{\;}v\cdot{y}\neq\epsilon"> и за всяко <img src="https://latex.codecogs.com/svg.latex?\Large&space;i\in{\mathbb{N}_0}:{\;}u\cdot{v^i}\cdot{x\cdot{y^i}}\cdot{z}\in{L(G)}">.

***СТЕКОВ АВТОМАТ***

**1.** Стеков автомат. Стеков автомат наричаме следната наредена шесторка <img src="https://latex.codecogs.com/svg.latex?\Large&space;M=<K,\sum{,}\Gamma{,\Delta},s,F>">, където:
- <img src="https://latex.codecogs.com/svg.latex?\Large&space;K"> - крайно множество от състояния;
- <img src="https://latex.codecogs.com/svg.latex?\Large&space;\sum"> - азбука от входните символи;
- <img src="https://latex.codecogs.com/svg.latex?\Large&space;\Gamma"> - азбука от стековите символи;
- <img src="https://latex.codecogs.com/svg.latex?\Large&space;s\in{K}"> - начално състояние;
- <img src="https://latex.codecogs.com/svg.latex?\Large&space;F\subseteq{K}"> - множество от финалните състояния;
- <img src="https://latex.codecogs.com/svg.latex?\Large&space;\Delta"> - релация на преходите: крайно подмножество на <img src="https://latex.codecogs.com/svg.latex?\Large&space;\bigg(K\times{\big(\sum\cup}\{\epsilon\}\big)\times{\Gamma^{\ast}}\bigg)\times\big(K\times{\Gamma^{\ast}}\big)">.

**2.** <img src="https://latex.codecogs.com/svg.latex?\Large&space;\vdash_M"> за стеков автомат <img src="https://latex.codecogs.com/svg.latex?\Large&space;M">. Елементите на <img src="https://latex.codecogs.com/svg.latex?\Large&space;K\times{\sum\ast}\times\Gamma\ast"> ще наричаме конфигурации на <img src="https://latex.codecogs.com/svg.latex?\Large&space;M">, където <img src="https://latex.codecogs.com/svg.latex?\Large&space;M=<K,\sum{,}\Gamma{,\Delta},s,F>">. Нека <img src="https://latex.codecogs.com/svg.latex?\Large&space;(p,u,\alpha)"> и <img src="https://latex.codecogs.com/svg.latex?\Large&space;(q,v,\gamma)"> са две конфигурации на <img src="https://latex.codecogs.com/svg.latex?\Large&space;M">. Дефинираме релацията <img src="https://latex.codecogs.com/svg.latex?\Large&space;\vdash_M"> по следния начин: <img src="https://latex.codecogs.com/svg.latex?\Large&space;(p,u,\alpha)\vdash{(q,v,\gamma)}\stackrel{\text{def.}}{\Leftrightarrow}\exists{\big((p,a,\beta),(q,\delta)\big)}\in\Delta">, т.ч. <img src="https://latex.codecogs.com/svg.latex?\Large&space;u=a\cdot{v},{\;}\alpha{=\beta\cdot{\eta},{\;}\gamma{=\delta\cdot\eta}}">, за някое <img src="https://latex.codecogs.com/svg.latex?\Large&space;\eta\in\Gamma\ast">

**3.** Кога една дума се приема от стеков автомат. Казваме, че стековият автомат <img src="https://latex.codecogs.com/svg.latex?\Large&space;M=<K,\sum{,}\Gamma{,\Delta},s,F>"> приема думата <img src="https://latex.codecogs.com/svg.latex?\Large&space;w">, ако е изпълнено <img src="https://latex.codecogs.com/svg.latex?\Large&space;(s,w,\epsilon)\vdash_M^{\ast}(f,\epsilon{,}\epsilon),f\in{F},\vdash_M^{\ast}"> е рефлексивно и транзитивно затваряне на <img src="https://latex.codecogs.com/svg.latex?\Large&space;\vdash_M">.

**4.** Прост стеков автомат. Казваме, че стековия автомат <img src="https://latex.codecogs.com/svg.latex?\Large&space;M=<K,\sum{,}\Gamma{,\Delta},s,F>"> е прост, ако за всяко правило <img src="https://latex.codecogs.com/svg.latex?\Large&space;\big((q,a,\beta),(p,\gamma)\big)\in\Delta">, такова че <img src="https://latex.codecogs.com/svg.latex?\Large&space;q\neq{s}"> е изпълнено, че <img src="https://latex.codecogs.com/svg.latex?\Large&space;\beta\in\Gamma"> и <img src="https://latex.codecogs.com/svg.latex?\Large&space;|\gamma|\le{2}">.


**МАШИНА НА ТЮРИНГ**

**1.** Машина на Тюринг. МТ наричаме следната наредена петорка <img src="https://latex.codecogs.com/svg.latex?\Large&space;M=<K,\sum{,}\delta{,}s,H>">, където:
- <img src="https://latex.codecogs.com/svg.latex?\Large&space;K"> - крайно множество от състояния;
- <img src="https://latex.codecogs.com/svg.latex?\Large&space;\sum"> - азбука, която съдържа символ за празна клетка <img src="https://latex.codecogs.com/svg.latex?\Large&space;\sqcup"> и символ за ляв ограничител <img src="https://latex.codecogs.com/svg.latex?\Large&space;\rhd">, но не съдържа <img src="https://latex.codecogs.com/svg.latex?\Large&space;\leftarrow"> и <img src="https://latex.codecogs.com/svg.latex?\Large&space;\rightarrow">;
- <img src="https://latex.codecogs.com/svg.latex?\Large&space;s\in{K}"> - начално състояние;
- <img src="https://latex.codecogs.com/svg.latex?\Large&space;H\in{K}"> - множество от стоп състояния;
- <img src="https://latex.codecogs.com/svg.latex?\Large&space;\delta"> - функция на преходите: <img src="https://latex.codecogs.com/svg.latex?\Large&space;(K\setminus{H})\times\sum\rightarrow{K}\times(\sum\cup\{\leftarrow{,}\rightarrow\})">, за която за всяко <img src="https://latex.codecogs.com/svg.latex?\Large&space;q\in{K\setminus{H}}">:<br>
  - ако <img src="https://latex.codecogs.com/svg.latex?\Large&space;\delta(q,\rhd)=(p,b)">, то <img src="https://latex.codecogs.com/svg.latex?\Large&space;b=\rightarrow">;
  - <img src="https://latex.codecogs.com/svg.latex?\Large&space;\forall{a}\in\sum">, ако <img src="https://latex.codecogs.com/svg.latex?\Large&space;\delta(q,a)=(p,b)"> то <img src="https://latex.codecogs.com/svg.latex?\Large&space;b\neg\rhd">.

**2.** Кога една машина на Тюринг разпознава един език. Езикът <img src="https://latex.codecogs.com/svg.latex?\Large&space;L"> се разпознава от машина на Тюринг <img src="https://latex.codecogs.com/svg.latex?\Large&space;M=<K,\sum{,}\delta{,}s,H>"> с <img src="https://latex.codecogs.com/svg.latex?\Large&space;y,n\in{H}">, ако за всяка дума <img src="https://latex.codecogs.com/svg.latex?\Large&space;w\in\sum{o}{\ast}"> (азбука с допълнителен символ) е изпълнено:
- ако <img src="https://latex.codecogs.com/svg.latex?\Large&space;w\in{L}">, то <img src="https://latex.codecogs.com/svg.latex?\Large&space;M"> приема <img src="https://latex.codecogs.com/svg.latex?\Large&space;w{\;}{\;}\big((s,\rhd\underline{\sqcup}w)"> *спира на приемаща конфигурация* (такава с <img src="https://latex.codecogs.com/svg.latex?\Large&space;y">)<img src="https://latex.codecogs.com/svg.latex?\Large&space;\big)">;
- ако <img src="https://latex.codecogs.com/svg.latex?\Large&space;w\notin{L}">, то <img src="https://latex.codecogs.com/svg.latex?\Large&space;M"> отхвърля <img src="https://latex.codecogs.com/svg.latex?\Large&space;w{\;}{\;}\big((s,\rhd\underline{\sqcup}w)"> *спира на отхвърляща конфигурация* (такава с <img src="https://latex.codecogs.com/svg.latex?\Large&space;n">)<img src="https://latex.codecogs.com/svg.latex?\Large&space;\big)">;

**3.** Какво и в какво преобразува простата машина на Тюринг <img src="https://latex.codecogs.com/svg.latex?\Large&space;R_{\sqcup}">.<br><img src="https://latex.codecogs.com/svg.latex?\Large&space;\rhd{w_1}\underline{\sqcup}w_2\rightarrow_{R_{\sqcup}}\rhd{w_1}\sqcup{w_2}\underline{\sqcup},{\;}w_2\in(\sum\setminus\{\rhd{,}\sqcup\})^{\ast}"><br>- обхожда (сканира) лентата надясно докато не намери символ за празната клетка.
