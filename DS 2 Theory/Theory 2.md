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

**6.** Стеков автомат. Стеков автомат наричаме следната наредена шесторка <img src="https://latex.codecogs.com/svg.latex?\Large&space;M=<K,\sum{,}\Gamma{,\Delta},s,F>">, където:
- <img src="https://latex.codecogs.com/svg.latex?\Large&space;K"> - крайно множество от състояния;
- <img src="https://latex.codecogs.com/svg.latex?\Large&space;\sum"> - азбука от входните символи;
- <img src="https://latex.codecogs.com/svg.latex?\Large&space;\Gamma"> - азбука от стековите символи;
- <img src="https://latex.codecogs.com/svg.latex?\Large&space;s\in{K}"> - начално състояние;
- <img src="https://latex.codecogs.com/svg.latex?\Large&space;F\subseteq{K}"> - множество от финалните състояния;
- <img src="https://latex.codecogs.com/svg.latex?\Large&space;\Delta"> - релация на преходите: крайно подмножество на <img src="https://latex.codecogs.com/svg.latex?\Large&space;\bigg(K\times{\big(\sum\cup}\{\epsilon\}\big)\times{\Gamma^{\ast}}\bigg)\times\big(K\times{\Gamma^{\ast}}\big)">.

**7.** <img src="https://latex.codecogs.com/svg.latex?\Large&space;\vdash_M"> за стеков автомат <img src="https://latex.codecogs.com/svg.latex?\Large&space;M">. Елементите на <img src="https://latex.codecogs.com/svg.latex?\Large&space;K\times{\sum\ast}\times\Gamma\ast"> ще наричаме конфигурации на <img src="https://latex.codecogs.com/svg.latex?\Large&space;M">, където <img src="https://latex.codecogs.com/svg.latex?\Large&space;M=<K,\sum{,}\Gamma{,\Delta},s,F>">. Нека <img src="https://latex.codecogs.com/svg.latex?\Large&space;(p,u,\alpha)"> и <img src="https://latex.codecogs.com/svg.latex?\Large&space;(q,v,\gamma)"> са две конфигурации на <img src="https://latex.codecogs.com/svg.latex?\Large&space;M">. Дефинираме релацията <img src="https://latex.codecogs.com/svg.latex?\Large&space;\vdash_M"> по следния начин: <img src="https://latex.codecogs.com/svg.latex?\Large&space;(p,u,\alpha)\vdash{(q,v,\gamma)}\stackrel{\text{def.}}{\Leftrightarrow}\exists{\big((p,a,\beta),(q,\delta)\big)}\in\Delta">, т.ч. <img src="https://latex.codecogs.com/svg.latex?\Large&space;u=a\cdot{v},{\;}\alpha{=\beta\cdot{\eta},{\;}\gamma{=\delta\cdot\eta}}">, за някое <img src="https://latex.codecogs.com/svg.latex?\Large&space;\eta\in\Gamma\ast">

**8.** Кога една дума се приема от стеков автомат. Казваме, че стековият автомат <img src="https://latex.codecogs.com/svg.latex?\Large&space;M=<K,\sum{,}\Gamma{,\Delta},s,F>"> приема думата <img src="https://latex.codecogs.com/svg.latex?\Large&space;w">, ако е изпълнено <img src="https://latex.codecogs.com/svg.latex?\Large&space;(s,w,\epsilon)\vdash_M^{\ast}(f,\epsilon{,}\epsilon),f\in{F},\vdash_M^{\ast}"> е рефлексивно и транзитивно затваряне на <img src="https://latex.codecogs.com/svg.latex?\Large&space;\vdash_M">.

**9.** Прост стеков автомат. Казваме, че стековия автомат <img src="https://latex.codecogs.com/svg.latex?\Large&space;M=<K,\sum{,}\Gamma{,\Delta},s,F>"> е прост, ако за всяко правило <img src="https://latex.codecogs.com/svg.latex?\Large&space;\big((q,a,\beta),(p,\gamma)\big)\in\Delta">, такова че <img src="https://latex.codecogs.com/svg.latex?\Large&space;q\neq{s}"> е изпълнено, че <img src="https://latex.codecogs.com/svg.latex?\Large&space;\beta\in\Gamma"> и <img src="https://latex.codecogs.com/svg.latex?\Large&space;|\gamma|\le{2}">.

**МАШИНА НА ТЮРИНГ**

**10.** Машина на Тюринг. МТ наричаме следната наредена петорка <img src="https://latex.codecogs.com/svg.latex?\Large&space;M=<K,\sum{,}\delta{,}s,H>">, където:
- <img src="https://latex.codecogs.com/svg.latex?\Large&space;K"> - крайно множество от състояния;
- <img src="https://latex.codecogs.com/svg.latex?\Large&space;\sum"> - азбука, която съдържа символ за празна клетка <img src="https://latex.codecogs.com/svg.latex?\Large&space;\sqcup"> и символ за ляв ограничител <img src="https://latex.codecogs.com/svg.latex?\Large&space;\rhd">, но не съдържа <img src="https://latex.codecogs.com/svg.latex?\Large&space;\leftarrow"> и <img src="https://latex.codecogs.com/svg.latex?\Large&space;\rightarrow">;
- <img src="https://latex.codecogs.com/svg.latex?\Large&space;s\in{K}"> - начално състояние;
- <img src="https://latex.codecogs.com/svg.latex?\Large&space;H\in{K}"> - множество от стоп състояния;
- <img src="https://latex.codecogs.com/svg.latex?\Large&space;\delta"> - функция на преходите: <img src="https://latex.codecogs.com/svg.latex?\Large&space;(K\setminus{H})\times\sum\rightarrow{K}\times(\sum\cup\{\leftarrow{,}\rightarrow\})">, за която за всяко <img src="https://latex.codecogs.com/svg.latex?\Large&space;q\in{K\setminus{H}}">:<br>
  - ако <img src="https://latex.codecogs.com/svg.latex?\Large&space;\delta(q,\rhd)=(p,b)">, то <img src="https://latex.codecogs.com/svg.latex?\Large&space;b=\rightarrow">;
  - <img src="https://latex.codecogs.com/svg.latex?\Large&space;\forall{a}\in\sum">, ако <img src="https://latex.codecogs.com/svg.latex?\Large&space;\delta(q,a)=(p,b)"> то <img src="https://latex.codecogs.com/svg.latex?\Large&space;b\neg\rhd">.

**11.** Кога една машина на Тюринг разпознава един език. Езикът <img src="https://latex.codecogs.com/svg.latex?\Large&space;L"> се разпознава от машина на Тюринг <img src="https://latex.codecogs.com/svg.latex?\Large&space;M=<K,\sum{,}\delta{,}s,H>"> с <img src="https://latex.codecogs.com/svg.latex?\Large&space;y,n\in{H}">, ако за всяка дума <img src="https://latex.codecogs.com/svg.latex?\Large&space;w\in\sum{o}{\ast}"> (азбука с допълнителен символ) е изпълнено:
- ако <img src="https://latex.codecogs.com/svg.latex?\Large&space;w\in{L}">, то <img src="https://latex.codecogs.com/svg.latex?\Large&space;M"> приема <img src="https://latex.codecogs.com/svg.latex?\Large&space;w{\;}{\;}\big((s,\rhd\underline{\sqcup}w)"> *спира на приемаща конфигурация* (такава с <img src="https://latex.codecogs.com/svg.latex?\Large&space;y">)<img src="https://latex.codecogs.com/svg.latex?\Large&space;\big)">;
- ако <img src="https://latex.codecogs.com/svg.latex?\Large&space;w\notin{L}">, то <img src="https://latex.codecogs.com/svg.latex?\Large&space;M"> отхвърля <img src="https://latex.codecogs.com/svg.latex?\Large&space;w{\;}{\;}\big((s,\rhd\underline{\sqcup}w)"> *спира на отхвърляща конфигурация* (такава с <img src="https://latex.codecogs.com/svg.latex?\Large&space;n">)<img src="https://latex.codecogs.com/svg.latex?\Large&space;\big)">;

**12.** Какво и в какво преобразува простата машина на Тюринг <img src="https://latex.codecogs.com/svg.latex?\Large&space;R_{\sqcup}">.<br><img src="https://latex.codecogs.com/svg.latex?\Large&space;\rhd{w_1}\underline{\sqcup}w_2\rightarrow_{R_{\sqcup}}\rhd{w_1}\sqcup{w_2}\underline{\sqcup},{\;}w_2\in(\sum\setminus\{\rhd{,}\sqcup\})^{\ast}"><br>- обхожда (сканира) лентата надясно докато не намери символ за празната клетка.

**13.** Какво и в какво преобразува простата машина на Тюринг <img src="https://latex.codecogs.com/svg.latex?\Large&space;L_{\sqcup}">.<br><img src="https://latex.codecogs.com/svg.latex?\Large&space;\rhd{w_1}{\sqcup}w_2\underline{\sqcup}\rightarrow_{L_{\sqcup}}\rhd{w_1}\underline{\sqcup}{w_2},{\;}w_2\in(\sum\setminus\{\rhd{,}\sqcup\})^{\ast}"><br>- обхожда (сканира) лентата наляво докато не намери символ за празната клетка.

**14.** Какво и в какво преобразува машината (*копи-машината*) <img src="https://latex.codecogs.com/svg.latex?\Large&space;C"> на Тюринг.<br>
<img src="https://latex.codecogs.com/svg.latex?\Large&space;\sqcup{w}\underline{\sqcup}\stackrel{\text{C}}{\rightarrow}\sqcup{w}\sqcup{w}\underline{\sqcup},{\;}w_2\in(\sum\setminus\{\rhd{,}\sqcup\})^{\ast}">

**15.** Какво и в какво преобразува машината (*шифт-машината*) <img src="https://latex.codecogs.com/svg.latex?\Large&space;S\rightarrow"> на Тюринг.<br>
<img src="https://latex.codecogs.com/svg.latex?\Large&space;\sqcup{w}\underline{\sqcup}\stackrel{\text{S}}{\rightarrow}\sqcup\sqcup{w}\underline{\sqcup},{\;}w_2\in(\sum\setminus\{\rhd{,}\sqcup\})^{\ast}">

**16.** Какво и в какво преобразува *delete* машината на Тюринг.<br>
Заменя непразните символи от лентата с празни (изтриване).

![](https://github.com/andy489/Data_Structures_and_Algorithms_CPP/blob/master/assets/Turing%20Machine%2001.png)

**17.** Твърденията за разрешимите (рекурсивните) и полуразрешимите (рекурсивно номеруемите) езици:
- всеки разрешим език е полуразрешим;
- ако <img src="https://latex.codecogs.com/svg.latex?\Large&space;L"> е разрешим език, то и допълнението му <img src="https://latex.codecogs.com/svg.latex?\Large&space;\overline{L}=(\sum{\setminus}\{\rhd{,}\sqcup\})^{\ast}"> също е разрешим език;
- съществува полуразрешим език, който не е разрешим.

**18.** Кога една функция <img src="https://latex.codecogs.com/svg.latex?\Large&space;f:\sum{o}\ast\nrightarrow\sum{o}\ast"> се изчисляа с помощта на машина на Тюринг <img src="https://latex.codecogs.com/svg.latex?\Large&space;M=<K,\sum{,}\delta{,}s,H>,{\;}\sum{o}\subseteq{\sum}\setminus\{\rhd{,}\sqcup\}">.<br> Тогава, когато за всяка дума <img src="https://latex.codecogs.com/svg.latex?\Large&space;w\in{\sum{o}\ast}"> са изпълнени условията:
- <img src="https://latex.codecogs.com/svg.latex?\Large&space;(s,\rhd\underline{\sqcup}w)\vdash_M^{\ast}(h,\rhd\underline{\sqcup}y)">, за <img src="https://latex.codecogs.com/svg.latex?\Large&space;y\in\sum{o}\ast\Rightleftarrow{f(w)}=y">;
- <img src="https://latex.codecogs.com/svg.latex?\Large&space;f(w)"> е определена <img src="https://latex.codecogs.com/svg.latex?\Large&space;\Leftrightarrow{M}"> спира работа върху <img src="https://latex.codecogs.com/svg.latex?\Large&space;(s,\rhd\underline{\sqcup}w)">, т.е. <img src="https://latex.codecogs.com/svg.latex?\Large&space;M(w)=y">.

**19.** Кога една машина на Тюринг изчислява една функция <img src="https://latex.codecogs.com/svg.latex?\Large&space;F:\mathbb{N}^k\nrightarrow\mathbb{N}"> на <img src="https://latex.codecogs.com/svg.latex?\Large&space;k"> променливи. Нека <img src="https://latex.codecogs.com/svg.latex?\Large&space;F:\mathbb{N}^k\nrightarrow\mathbb{N}">. Казваме, че машината на Тюринг <img src="https://latex.codecogs.com/svg.latex?\Large&space;M=<K,\sum{,}\delta{,}s,H>"> изчислява функцията <img src="https://latex.codecogs.com/svg.latex?\Large&space;F"> точно тогава, когато са изпълнени следните условия:
- <img src="https://latex.codecogs.com/svg.latex?\Large&space;![F](n_1,...,n_k)"> *е дефинирана* <img src="https://latex.codecogs.com/svg.latex?\Large&space;]\Leftrightarrow{M}(1^{n_1}\sqcup{...}\sqcup{}1^{n_k})\searrow"> спира работа: <img src="https://latex.codecogs.com/svg.latex?\Large&space;(s,\rhd\underline{\sqcup}1^{n_1}\sqcup{...}\sqcup{1^{n_k}})\vdash_M^{\ast}(h,\rhd\underline{\sqcup}1^{f(n_1,...,n_k)})">;
- ако <img src="https://latex.codecogs.com/svg.latex?\Large&space;F(n_1,...,n_k)=m">, то <img src="https://latex.codecogs.com/svg.latex?\Large&space;M(1^{n_1}\sqcup{...}\sqcup{1^{n_k}})=1^m">.

**20.** Теоремата за неразрешимите проблеми на машина на Тюринг свързани с:<br>
a) празната дума;<br>
б) съществуването на вход;<br>
в) стоп-проблема;<br>
г) всеки вход;<br>
д) две машини на Тюринг;<br>
е) регулярните езици;
- Следните проблеми на машината на Тюринг <img src="https://latex.codecogs.com/svg.latex?\Large&space;M"> са неразрешими:
  - дали <img src="https://latex.codecogs.com/svg.latex?\Large&space;M"> спира върху празната дума;
  - дали <img src="https://latex.codecogs.com/svg.latex?\Large&space;M"> спира върху поне един вход <img src="https://latex.codecogs.com/svg.latex?\Large&space;\big(">т.е. дали <img src="https://latex.codecogs.com/svg.latex?\Large&space;\exists{w}:M(w)\searrow"><img src="https://latex.codecogs.com/svg.latex?\Large&space;\big)">;
  - дали <img src="https://latex.codecogs.com/svg.latex?\Large&space;M"> спира при вход <img src="https://latex.codecogs.com/svg.latex?\Large&space;w,{\;}M\searrow">;
  - дали <img src="https://latex.codecogs.com/svg.latex?\Large&space;M"> спира за всяки вход <img src="https://latex.codecogs.com/svg.latex?\Large&space;\big(">т.е. дали <img src="https://latex.codecogs.com/svg.latex?\Large&space;M(w)\searrow"> за всяко <img src="https://latex.codecogs.com/svg.latex?\Large&space;w"><img src="https://latex.codecogs.com/svg.latex?\Large&space;\big)">;
  - дали за дадени машини на Тюринг <img src="https://latex.codecogs.com/svg.latex?\Large&space;M_1"> и <img src="https://latex.codecogs.com/svg.latex?\Large&space;M_2">, <img src="https://latex.codecogs.com/svg.latex?\Large&space;M_1"> и <img src="https://latex.codecogs.com/svg.latex?\Large&space;M_2"> спират върху един и същ вход;
  - дали <img src="https://latex.codecogs.com/svg.latex?\Large&space;L(M)"> е регулярен език.

**ФОРМАЛИЗИРАНЕ НА ОПЕРАЦИИТЕ**

**21.** Операцията минимизация. Нека<img src="https://latex.codecogs.com/svg.latex?\Large&space;f:\mathbb{N}^{n+1}\nrightarrow\mathbb{N}">. Казваме, че <img src="https://latex.codecogs.com/svg.latex?\Large&space;g:\mathbb{N}^n\nrightarrow{\mathbb{N}}"> се получава от <img src="https://latex.codecogs.com/svg.latex?\Large&space;f"> с помощта на операцията минимизация (<img src="https://latex.codecogs.com/svg.latex?\Large&space;\mu">-операция), ако за произволни <img src="https://latex.codecogs.com/svg.latex?\Large&space;x_1,....x_n,y"> е изпълнена еквивалентността:<br>
<img src="https://latex.codecogs.com/svg.latex?\Large&space;g(x_1,...,x_n)=y\Leftrightarrow{f(x_1,...,x_n,y)=0}{\;}\&{\;}\forall{z}<y:f(x_1,...,x_n,z)"> *е дефинирана и* <img src="https://latex.codecogs.com/svg.latex?\Large&space;f(x_1,...,x_n,z)>0">.

