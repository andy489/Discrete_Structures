## Задача 26.

Нека <img src="https://latex.codecogs.com/svg.latex?\Large&space;G(V,E)"> е граф. Да се докаже, че броят на върховете от нечетна степен е четно число.

*Док-во:*

Формулата на Ойлер ни дава:

<img src="https://latex.codecogs.com/svg.latex?\Large&space;2|E|=\sum_{u\in{V}}deg(u)=\sum_{u\in{V_0^2}}deg(u)+\sum_{u\in{V_1^2}}deg(u)">, където <img src="https://latex.codecogs.com/svg.latex?\Large&space;\{V_k^m\},k\le{m-1}"> е множеството от върхове със степен даваща остатък <img src="https://latex.codecogs.com/svg.latex?\Large&space;k"> по модулно деление на <img src="https://latex.codecogs.com/svg.latex?\Large&space;m">.

В нашия случай имаме, че <img src="https://latex.codecogs.com/svg.latex?\Large&space;V_0^2\cup{V_1^2}=V"> и <img src="https://latex.codecogs.com/svg.latex?\Large&space;V_0^2\cap{V_1^2=\varnothing},{\;}V_0^2,V_1^2\subseteq{V}">, следователно сме разбили <img src="https://latex.codecogs.com/svg.latex?\Large&space;V"> на две подмножества.
  
  Но <img src="https://latex.codecogs.com/svg.latex?\Large&space;\sum_{u\in{V_0^2}}deg(u)"> е сума от четни числа <img src="https://latex.codecogs.com/svg.latex?\Large&space;\Rightarrow"><br><img src="https://latex.codecogs.com/svg.latex?\Large&space;{\sum_{u\in{V_0^2}}deg(u)}\equiv{0}(mod{\;}2)">. От друга страна <img src="https://latex.codecogs.com/svg.latex?\Large&space;2|E|"> е четно число.
  
Следователно и <img src="https://latex.codecogs.com/svg.latex?\Large&space;\sum_{u\in{V_1^2}}deg(u)"> е четно число, но в тази сума всяко събираемо е нечетно (от разбиването) от където следва, че броя им е четно число.
