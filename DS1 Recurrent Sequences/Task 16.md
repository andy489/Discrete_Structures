## Задача 16. (от писмен изпит - 05.02.2016г.)

Дадена е рекурентната зависимост <img src="https://latex.codecogs.com/svg.latex?\Large&space;a_{n+1}=-7a_n+n+1"> и <img src="https://latex.codecogs.com/svg.latex?\Large&space;a_0=0">. Намерете редицата <img src="https://latex.codecogs.com/svg.latex?\Large&space;\{a_n\}^{\infty}_{n=0}">, която удовлетворява тази зависимост и началното условие.

*Решение:*

Първо ще трябва да намерим хомогенна зависимост еквивалентна на дадената. Заместваме в зависимостта с <img src="https://latex.codecogs.com/svg.latex?\Large&space;n"> и <img src="https://latex.codecogs.com/svg.latex?\Large&space;n-1">:<br>
<img src="https://latex.codecogs.com/svg.latex?\Large&space;a_{n+1}+7a_n=n+1"> и <img src="https://latex.codecogs.com/svg.latex?\Large&space;a_n+7a_{n-1}=n">.

Изваждаме второто уравнение от първото:
<img src="https://latex.codecogs.com/svg.latex?\Large&space;a_{n+1}+6a_n-7a_{n-1}=1">, тогава<br>
<img src="https://latex.codecogs.com/svg.latex?\Large&space;a_n+6a_{n-1}-7a_{n-2}=1">. Отново изваждаме второто от първото и получаваме: <img src="https://latex.codecogs.com/svg.latex?\Large&space;a_{n+1}+5a_n-13a_{n-1}+7a_{n-2}=0">. За да намерим характеристичното уравнение извършваме полагане <img src="https://latex.codecogs.com/svg.latex?\Large&space;a_n=x^n,x\neq{0}">. Получаваме: <img src="https://latex.codecogs.com/svg.latex?\Large&space;x^{n+1}+5x^n-13x^{n-1}+7x^{n-2}=0\Rightarrow{x^3+5x^2-13x+7=0}">. Прилагаме схема на Хорнер:

H|1|5|-13|7
-|-|-|-|-
1|1|6|-7|0
1|1|7|0|
-7|1|0||

Характеристичното уравнение има двоен корен равен на 1 и единичен корен равен на -7.

Общ вид: <img src="https://latex.codecogs.com/svg.latex?\Large&space;a_n=(A.n+B).1^n+C.(-7)^n">.

Имаме само първи член на редицата, но ще ни трябват поне три. Нека ги пресметнем:

<img src="https://latex.codecogs.com/svg.latex?\Large&space;a_1=-7a_0+1=1;{\;}a_2=-7a_1+1=-6">. Сега, за да намерим явния вид ще използваме общия вид на първите три елемента от редицата.

<img src="https://latex.codecogs.com/svg.latex?\Large&space;a_0=(A.0+B).1^0+C(-7)^0=0"><br>
<img src="https://latex.codecogs.com/svg.latex?\Large&space;a_1=(A+B).1^1+c(-7)^1=1"><br>
<img src="https://latex.codecogs.com/svg.latex?\Large&space;a_2=(2A+B).1^2+C(-7)^2=-6">.

Горното е изпълнено тогава и само тогава, когато

<img src="https://latex.codecogs.com/svg.latex?\Large&space;B+C=0"><br>
<img src="https://latex.codecogs.com/svg.latex?\Large&space;A+B-7C=1"><br>
<img src="https://latex.codecogs.com/svg.latex?\Large&space;2A+B+49C=-6\Leftrightarrow{A=0,b=\frac{1}{8},C=-\frac{1}{8}}">. Следователно <img src="https://latex.codecogs.com/svg.latex?\Large&space;a_n=\frac{1-(-7)^n}{8}">.
