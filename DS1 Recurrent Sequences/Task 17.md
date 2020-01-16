## Задача 17. 

Да се намери редицата <img src="https://latex.codecogs.com/svg.latex?\Large&space;\{a_n\}_0^{\infty}">, която е зададена рекурентно с  <img src="https://latex.codecogs.com/svg.latex?\Large&space;a_{n+1}=8a_n+(3n-1)6^n"> и <img src="https://latex.codecogs.com/svg.latex?\Large&space;a_0=0">.

*Решение:*

Пресмятаме:  <img src="https://latex.codecogs.com/svg.latex?\Large&space;a_1=8a_0+(3.0-1)6^0=-1;{\;}a_2=8a_1+(3.1-1)6^1=4."><br>
Хомогенна част:  <img src="https://latex.codecogs.com/svg.latex?\Large&space;p.8^n"><br>
Нехомогенна част:  <img src="https://latex.codecogs.com/svg.latex?\Large&space;(qn+r)6^n"><br>
Следователно общия вид е:  <img src="https://latex.codecogs.com/svg.latex?\Large&space;\underbrace{a_n=p.8^n+(qn+r)6^n}">.

 <img src="https://latex.codecogs.com/svg.latex?\Large&space;0=a_0=p+r"><br>
  <img src="https://latex.codecogs.com/svg.latex?\Large&space;-1=a_1=8p+6q+6r"><br>
   <img src="https://latex.codecogs.com/svg.latex?\Large&space;4=a_2=64p+(2q+r).36=64p+72q+36r">
   
 <img src="https://latex.codecogs.com/svg.latex?A=\left(\begin{matrix}1&0&1&0\\8&6&6&-1\\64&72&36&4\\\end{matrix}\right)\sim\left(\begin{matrix}1&0&1&0\\8&6&6&-1\\16&18&9&1\\\end{matrix}\right)\sim\left(\begin{matrix}1&0&1&0\\0&6&-2&-1\\0&18&-7&1\\\end{matrix}\right)\sim">
 

<img src="https://latex.codecogs.com/svg.latex?\sim\left(\begin{matrix}1&0&1&0\\0&6&-2&-1\\0&0&-1&4\\\end{matrix}\right)\sim\left(\begin{matrix}1&0&1&0\\0&6&0&-9\\0&0&-1&4\\\end{matrix}\right)\sim\left(\begin{matrix}1&0&0&4\\0&1&0&-\frac{3}{2}\\0&0&1&-4\\\end{matrix}\right)">

 <img src="https://latex.codecogs.com/svg.latex?\Large&space;\Rightarrow{p=4,q=-\frac{3}{2},r=4}.{\;}a_n=4.8^n-(\frac{3}{2}n+4)6^n">.
