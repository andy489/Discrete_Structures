## Задача 33.

Нека <img src="https://latex.codecogs.com/svg.latex?\Large&space;G"> е дърво, в което нито един връх не е от степен по-висока от <img src="https://latex.codecogs.com/svg.latex?\Large&space;3">. Докажете, че броя на върховете от степен <img src="https://latex.codecogs.com/svg.latex?\Large&space;1"> е с <img src="https://latex.codecogs.com/svg.latex?\Large&space;2"> по-голям от този на върховете от степен <img src="https://latex.codecogs.com/svg.latex?\Large&space;3">.

*Док-во:*

Нека с <img src="https://latex.codecogs.com/svg.latex?\Large&space;N(i)"> означаваме броя на върховете от степен <img src="https://latex.codecogs.com/svg.latex?\Large&space;i">. В конкретния случай, ако <img src="https://latex.codecogs.com/svg.latex?\Large&space;i\ge{4}\Rightarrow{N(i)=0}">;<br>
<img src="https://latex.codecogs.com/svg.latex?\Large&space;G"> е дърво <img src="https://latex.codecogs.com/svg.latex?\Large&space;\Rightarrow{|E|=|V|-1=N(1)+N(2)+N(3)-1}">;

Oт формулата на Ойлер имаме:<br>
<img src="https://latex.codecogs.com/svg.latex?\Large&space;2(N(1)+N(2)+N(3)-1)=\sum_{u\in{V}}deg(u)=N(1).1+N(2).2+N(3).3\Rightarrow{N(1)=2+N(3)}">< което искахме да докажем.
