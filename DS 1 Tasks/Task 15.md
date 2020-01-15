## Задача 15. (от писмен изпит - 05.02.2016г.) 

**а)** Докажете, че <img src="https://latex.codecogs.com/svg.latex?\Large&space;(A\cap{B})\cup{C}=A\cap{(B\cup{C})}\Leftrightarrow{C\subseteq{A}}">;<br>
**б)** Напишете всички подмножества на множеството <img src="https://latex.codecogs.com/svg.latex?\Large&space;\{\varnothing{,\{\varnothing\},{\{\{\varnothing\}\}}}\}">.

*Решение:*

Да започнем с **а)**. Задачата е сходна със задача 7., за това тук ще предоставим едно малко по-неформално и различно решение. Първо за <img src="https://latex.codecogs.com/svg.latex?\Large&space;(\Rightarrow)">: Нека

<img src="https://latex.codecogs.com/svg.latex?\Large&space;(A\cap{B})\cup{C}=A\cap{(B\cup{C})}">.<br>
(A\cap{B})\cup{C})=\{a|a\in{A}"> и <img src="https://latex.codecogs.com/svg.latex?\Large&space;a\in{B})"> или <img src="https://latex.codecogs.com/svg.latex?\Large&space;a\in{C}\}"><br>
<img src="https://latex.codecogs.com/svg.latex?\Large&space;A\cap{B\cup{C}}=\{a\in{A}"> и <img src="https://latex.codecogs.com/svg.latex?\Large&space;(a\in{B}"> или <img src="https://latex.codecogs.com/svg.latex?\Large&space;a\in{C})\}=\{a|(a\in{A}"> и <img src="https://latex.codecogs.com/svg.latex?\Large&space;a\in{B}"> или <img src="https://latex.codecogs.com/svg.latex?\Large&space;a\in{A}"> и <img src="https://latex.codecogs.com/svg.latex?\Large&space;a\in{C}\}">.

Условието от лявата страна на „или“ е еднакво и в двете множества, тоест равенството в този случай е изпълнено винаги. Остава да разгледаме случая за елементите от <img src="https://latex.codecogs.com/svg.latex?\Large&space;C">. За да имаме равенство трябва тези елементи да се припокриват с елементите, които отговарят на условието <img src="https://latex.codecogs.com/svg.latex?\Large&space;(a\in{A}"> и <img src="https://latex.codecogs.com/svg.latex?\Large&space;a\in{C})">. Тоест от присъствието на елемента в <img src="https://latex.codecogs.com/svg.latex?\Large&space;C"> трябва да следва присъствието на елемента в <img src="https://latex.codecogs.com/svg.latex?\Large&space;A">, което означава точно <img src="https://latex.codecogs.com/svg.latex?\Large&space;C\in{A}">.

Доказателството в обратната посока е аналогично. От това, че <img src="https://latex.codecogs.com/svg.latex?\Large&space;C\in{A}"> ще следва, че ако един елемент принадлежи на <img src="https://latex.codecogs.com/svg.latex?\Large&space;C">, той също принадлежи и на <img src="https://latex.codecogs.com/svg.latex?\Large&space;A">. Тоест имаме <img src="https://latex.codecogs.com/svg.latex?\Large&space;a\in{C}\Rightarrow{a\in{A}}"> и <img src="https://latex.codecogs.com/svg.latex?\Large&space;a\in{C}"> и като заместим в условията за <img src="https://latex.codecogs.com/svg.latex?\Large&space;(A\cap{B})\cup{C}"> и <img src="https://latex.codecogs.com/svg.latex?\Large&space;A\cap(B\cup{C})"> ще получим равенството.

**б)** Да разделим подмножествата на база брой елементи:
- нула елемента: <img src="https://latex.codecogs.com/svg.latex?\Large&space;varnothing">;
- един елемент: <img src="https://latex.codecogs.com/svg.latex?\Large&space;\{\varnothing\},\{\{\varnothing\}\},\{\{\{\varnothing\}\}\}">;
- два елемента: <img src="https://latex.codecogs.com/svg.latex?\Large&space;\{\varnothing{,\{\varnothing\}}\},\{\varnothing{,}\{\{\varnothing\}\}\},\{\{\varnothing\}\},\{\{\varnothing\}\}\}">;
- три елемента: <img src="https://latex.codecogs.com/svg.latex?\Large&space;\{\varnothing{,}\{\varnothing\},\{\{\varnothing\}\}\}">.
