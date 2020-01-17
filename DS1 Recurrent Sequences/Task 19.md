## Задача 19.

Да се намери редицата <img src="https://latex.codecogs.com/svg.latex?\Large&space;\{a_n\}_0^{\infty}">, която е зададена рекурентно с уравнението <img src="https://latex.codecogs.com/svg.latex?\Large&space;a_{n+1}=-3a_n+(2n+1)5^n"> и <img src="https://latex.codecogs.com/svg.latex?\Large&space;a_0=0">.

*Решение:*

Пресмятаме: <img src="https://latex.codecogs.com/svg.latex?\Large&space;a_1=-3a_0+(2.0+1)5^0=1;{\;}a_2=-3a_1+(2.1+1)5^1=-3+3.5=12"><br>
Хомогенна част: <img src="https://latex.codecogs.com/svg.latex?\Large&space;p(-3)^n"><br>
Нехомогенна част: <img src="https://latex.codecogs.com/svg.latex?\Large&space;(qn+r)5^n"><br>
Следователно общия вид е: <img src="https://latex.codecogs.com/svg.latex?\Large&space;\underbrace{a_n=p(-3)^n+(qn+r)5^n}">

 <img src="https://latex.codecogs.com/svg.latex?\Large&space;0=a_0=p+r"><br>
  <img src="https://latex.codecogs.com/svg.latex?\Large&space;1=a_1=-3p+5q+5r"><br>
   <img src="https://latex.codecogs.com/svg.latex?\Large&space;12=a_2=9p+(2q+r).25=9p+50q+25r">
   
<img src="https://latex.codecogs.com/svg.latex?A=\left(\begin{matrix}1&0&1&0\\-3&5&5&1\\9&50&25&12\\\end{matrix}\right)\sim\left(\begin{matrix}1&0&1&0\\-8&5&0&1\\-16&50&0&12\\\end{matrix}\right)\sim\left(\begin{matrix}1&0&1&0\\-8&5&0&1\\0&40&0&10\\\end{matrix}\right)\sim\left(\begin{matrix}1&0&0&\frac{1}{32}\\0&1&0&\frac{1}{4}\\0&0&1&-\frac{1}{32}\\\end{matrix}\right)\Rightarrow{p=\frac{1}{32},q=\frac{1}{4},r=-\frac{1}{32}}.\\\Rightarrow{a_n=\frac{1}{32}.(-3)^n+(\frac{1}{4}n-\frac{1}{32}).5^n}">.
