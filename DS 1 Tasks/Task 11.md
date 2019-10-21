## Задача 11. (1.5 т.) 02.12.2018 г.
Определете кои от своиствата рефлексивност, симетричност, антисиметричност и транзитивност притежава релацията <img src="https://latex.codecogs.com/svg.latex?\Large&space;R"> в <img src="https://latex.codecogs.com/svg.latex?\Large&space;\mathbb{N}\times{P(\mathbb{N})}">, определена чрез: <img src="https://latex.codecogs.com/svg.latex?\Large&space;(a,A)R(b,B)\Leftrightarrow{a}"> дели <img src="https://latex.codecogs.com/svg.latex?\Large&space;b"> или <img src="https://latex.codecogs.com/svg.latex?\Large&space;B\subseteq{A}">. <img src="https://latex.codecogs.com/svg.latex?\Large&space;R"> *е релация между естествено число и множеството от естествени числа.*

*Решение:*

**1)** *Рефлексивност.*<br>
Нека имаме наредена двойка <img src="https://latex.codecogs.com/svg.latex?\Large&space;(a,A)">. Трябва да проверим дали <img src="https://latex.codecogs.com/svg.latex?\Large&space;(a,A)R(a,A)\Leftrightarrow{a}"> дели <img src="https://latex.codecogs.com/svg.latex?\Large&space;а"> или <img src="https://latex.codecogs.com/svg.latex?\Large&space;A\subseteq{A}">, което очевидно е изпълнено, тъй като <img src="https://latex.codecogs.com/svg.latex?\Large&space;a|a"> и <img src="https://latex.codecogs.com/svg.latex?\Large&space;A\subseteq{A}">, за <img src="https://latex.codecogs.com/svg.latex?\Large&space;\forall{a\in\mathbb{N}}"> и за <img src="https://latex.codecogs.com/svg.latex?\Large&space;\forall{A\subseteq{\mathbb{N}}}">. Следователно <img src="https://latex.codecogs.com/svg.latex?\Large&space;R"> е рефлексивна.

**2)** *Симетричност.* <br>
Нека имаме <img src="https://latex.codecogs.com/svg.latex?\Large&space;(a,A)"> и <img src="https://latex.codecogs.com/svg.latex?\Large&space;(b,B)">. Трябва да проверим дали за <img src="https://latex.codecogs.com/svg.latex?\Large&space;\forall{a,b,A,B:}"> ако <img src="https://latex.codecogs.com/svg.latex?\Large&space;(a,A)R(b,B)">, то <img src="https://latex.codecogs.com/svg.latex?\Large&space;(b,B)R(a,A)">, т.е. ако <br><img src="https://latex.codecogs.com/svg.latex?\Large&space;(a"> *дели* <img src="https://latex.codecogs.com/svg.latex?\Large&space;b"> *или* <img src="https://latex.codecogs.com/svg.latex?\Large&space;B\subseteq{A})">, то <img src="https://latex.codecogs.com/svg.latex?\Large&space;(b"> *дели* <img src="https://latex.codecogs.com/svg.latex?\Large&space;a"> *или* <img src="https://latex.codecogs.com/svg.latex?\Large&space;A\subseteq{B})">. Но това *не* винаги е изпълнено.<br>
Ще дадем *контрапримера* <img src="https://latex.codecogs.com/svg.latex?\Large&space;a=2,b=4,A=\{1,2\},B=\{1\}">. Следователно <img src="https://latex.codecogs.com/svg.latex?\Large&space;R"> не е симетрична.

**3)** *Антисиметричност.* <br>
Трябва да проверим дали, ако <img src="https://latex.codecogs.com/svg.latex?\Large&space;(a,A)R(b,B)"> и <img src="https://latex.codecogs.com/svg.latex?\Large&space;(b,B)R(a,A)">, то <img src="https://latex.codecogs.com/svg.latex?\Large&space;a=b"> и <img src="https://latex.codecogs.com/svg.latex?\Large&space;A=B">. Но това *не* винаги е изпълнено. 
*Контрапример:*<br>
<img src="https://latex.codecogs.com/svg.latex?\Large&space;(2,\{1\})R(4,\{1,2\})">, тъй като <img src="https://latex.codecogs.com/svg.latex?\Large&space;\underbrace{\underbrace{2|4}_{true}\lor\underbrace{\{1,2\}\subseteq\{1\}}_{false}}_{true}"><br> 
и <img src="https://latex.codecogs.com/svg.latex?\Large&space;(4,\{1,2\})R(2,\{1\})">, тъй като <img src="https://latex.codecogs.com/svg.latex?\Large&space;\underbrace{\underbrace{4|2}_{false}\lor\underbrace{\{1\}\subseteq{1,2}}_{true}}_{true}">,

но <img src="https://latex.codecogs.com/svg.latex?\Large&space;(2,\{1\})\neq{(4,\{1,2\})}">. Следователно <img src="https://latex.codecogs.com/svg.latex?\Large&space;R"> не е и антисиметрична. От 2) и 3) следва, че <img src="https://latex.codecogs.com/svg.latex?\Large&space;R"> не е нито релация на еквивалентност, нито частична наредба.

**4)** *Транзитивност.*<br>
Трябва да проверим дали, ако <img src="https://latex.codecogs.com/svg.latex?\Large&space;(a,A)R(b,B)"> и <img src="https://latex.codecogs.com/svg.latex?\Large&space;(b,B)R(c,C)">, то <img src="https://latex.codecogs.com/svg.latex?\Large&space;(a,A)R(c,C)"> за произволни <img src="https://latex.codecogs.com/svg.latex?\Large&space;a,b,c\in{\mathbb{N}}"> и <img src="https://latex.codecogs.com/svg.latex?\Large&space;A,B,C\subseteq{P(\mathbb{N})}">.

Тоест трябва да проверим дали, ако:

<img src="https://latex.codecogs.com/svg.latex?\Large&space;(a|b)\lor(B\subseteq{A})"> и <img src="https://latex.codecogs.com/svg.latex?\Large&space;(b|c)\lor(C\subseteq{B})">, то <img src="https://latex.codecogs.com/svg.latex?\Large&space;(a|c)\lor(C\subseteq{A})">.

Това не е изпълнено винаги и ще намерим *контрапример* за да докажем това твърдение. За контрапримера трябва
<img src="https://latex.codecogs.com/svg.latex?\Large&space;a\nmid{b}"> и <img src="https://latex.codecogs.com/svg.latex?\Large&space;B\subseteq{A};b|c"> и <img src="https://latex.codecogs.com/svg.latex?\Large&space;C\nsubseteq{B}">.

Нека <img src="https://latex.codecogs.com/svg.latex?\Large&space;a=3,b=2,c=4">

<img src="https://latex.codecogs.com/svg.latex?\Large&space;A=\{1,2\},B=\{1\},C=\{4,5\}">.

<img src="https://latex.codecogs.com/svg.latex?\Large&space;(3,\{1,2\})R(2,\{1\})">, тъй като <img src="https://latex.codecogs.com/svg.latex?\Large&space;(\underbrace{(3|2)}_{false}\lor(\underbrace{\{1\}\subseteq\{1,2\}}_{true})"> е винаги истина и <img src="https://latex.codecogs.com/svg.latex?\Large&space;(2,\{1\})R(4,\{4,5\})">, тъй като


