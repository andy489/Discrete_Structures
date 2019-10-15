## Задача 9.
Нека <img src="https://latex.codecogs.com/svg.latex?\Large&space;A=\{a+b\sqrt{2}|a,b\in{\mathbb{Q}}\}\setminus{\{0\}}">. Нека <img src="https://latex.codecogs.com/svg.latex?\Large&space;R"> е релация над <img src="https://latex.codecogs.com/svg.latex?\Large&space;A">, определена чрез:

<img src="https://latex.codecogs.com/svg.latex?\Large&space;xRy\Leftrightarrow{(\exists{p}\in{\mathbb{Q}}})[x=py{\;}\lor{\;}{xy=p}]">, такова <img src="https://latex.codecogs.com/svg.latex?\Large&space;p"> ще наричаме свидетел за това, че <img src="https://latex.codecogs.com/svg.latex?\Large&space;x"> е в релация с <img src="https://latex.codecogs.com/svg.latex?\Large&space;y">. Покажете, че <img src="https://latex.codecogs.com/svg.latex?\Large&space;R"> е релация на еквивалентност над <img src="https://latex.codecogs.com/svg.latex?\Large&space;A">.

*Док-во:*

**а)** Рефлексивност. Нека <img src="https://latex.codecogs.com/svg.latex?\Large&space;a\in{A}">. Тогава <img src="https://latex.codecogs.com/svg.latex?\Large&space;1\in{\mathbb{Q}}"> и <img src="https://latex.codecogs.com/svg.latex?\Large&space;x=1.x\Rightarrow{(\exists{1}\in{\mathbb{Q}})[\underbrace{x=1.x}_{true}\;\lor\;{x.x=1}]">, т.е. <img src="https://latex.codecogs.com/svg.latex?\Large&space;1"> е свидетел, че <img src="https://latex.codecogs.com/svg.latex?\Large&space;xRx">.

**б)** Симетричност. Нека <img src="https://latex.codecogs.com/svg.latex?\Large&space;xRy"> и <img src="https://latex.codecogs.com/svg.latex?\Large&space;p\in{Q}"> е свидетел за това, т.е. <img src="https://latex.codecogs.com/svg.latex?\Large&space;x=py"> или <img src="https://latex.codecogs.com/svg.latex?\Large&space;xy=p">. Ще намерим свидетел за <img src="https://latex.codecogs.com/svg.latex?\Large&space;yRx">.<br>
Ако <img src="https://latex.codecogs.com/svg.latex?\Large&space;x=py">, то <img src="https://latex.codecogs.com/svg.latex?\Large&space;y=\frac{1}{p}x"> (ако <img src="https://latex.codecogs.com/svg.latex?\Large&space;p=0">, то <img src="https://latex.codecogs.com/svg.latex?\Large&space;x=0\in{A}">). Но <img src="https://latex.codecogs.com/svg.latex?\Large&space;\frac{1}{p}\in\mathbb{Q}"> и така <img src="https://latex.codecogs.com/svg.latex?\Large&space;q=\frac{1}{p}"> е свидетел за <img src="https://latex.codecogs.com/svg.latex?\Large&space;yRx">, защото <img src="https://latex.codecogs.com/svg.latex?\Large&space;y=qx\Rightarrow{(y=qx\;\lor\;{yx=q})}"> е истина.

**в)** Транзитивност. Нека <img src="https://latex.codecogs.com/svg.latex?\Large&space;xRy,{\;}yRx"> и <img src="https://latex.codecogs.com/svg.latex?\Large&space;p,q\in{\mathbb{Q}}"> са свидетели за тези релации съответно.<br>
За да бъде <img src="https://latex.codecogs.com/svg.latex?\Large&space;R"> транзитивна трябва да е изпълнено: 

<img src="https://latex.codecogs.com/svg.latex?\Large&space;\forall{x}\forall{y}\forall{z}(xRy\;\&\;{yRz}\Rightarrow{xRz})">, т.е. <img src="https://latex.codecogs.com/svg.latex?\Large&space;(x=py\;\lor\;{xy=p})"> и <img src="https://latex.codecogs.com/svg.latex?\Large&space;(y=qz\;\lor\;{yz=q})"><br>
Следователно имаме четири възможности за случването на <img src="https://latex.codecogs.com/svg.latex?\Large&space;xRy"> и <img src="https://latex.codecogs.com/svg.latex?\Large&space;yRz"> и при всяка една от тях трябва да проверим дали <img src="https://latex.codecogs.com/svg.latex?\Large&space;\exists"> свидетел за <img src="https://latex.codecogs.com/svg.latex?\Large&space;xRz">, т.е. ще търсим такова <img src="https://latex.codecogs.com/svg.latex?\Large&space;s\in{\mathbb{Q}}">, че <img src="https://latex.codecogs.com/svg.latex?\Large&space;(x=sz\;\lor\;{xz=s}),{\;}s\in{\mathbb{Q}}">

**(1)** <img src="https://latex.codecogs.com/svg.latex?\Large&space;x=py"> и <img src="https://latex.codecogs.com/svg.latex?\Large&space;y=qz{\;}\Rightarrow{\;}x=py=p(qz)=(pq)z\Rightarrow{s=pq\in{Q}}">;

**(2)** <img src="https://latex.codecogs.com/svg.latex?\Large&space;x=py"> и <img src="https://latex.codecogs.com/svg.latex?\Large&space;yz=q\Rightarrow{x.y.z=p.y.q}\Rightarrowxz=pq=s\in{\mathbb{Q}}\Rightarrow{s=pq}">; 

**(3)** <img src="https://latex.codecogs.com/svg.latex?\Large&space;xy=p"> и <img src="https://latex.codecogs.com/svg.latex?\Large&space;y=qz{\;}\Rightarrow{\;}xyzq=y.p\Rightarrow{xz}=\frac{p}{q}\in{\mathbb{Q}},{\;}q\neq{0},{\;}s=\frac{p}{q}"> е свидетел за <img src="https://latex.codecogs.com/svg.latex?\Large&space;xRz"> .

**(4)** <img src="https://latex.codecogs.com/svg.latex?\Large&space;xy=p"> и <img src="https://latex.codecogs.com/svg.latex?\Large&space;yz=q{\;}\Rightarrow{y=\frac{q}{z}},{\;}xy=p\Leftrightarrow{x.\frac{q}{z}}=p\Rightarrow{x}=\frac{p}{q}z,{\;}q\neq{0}\Rightarrow=\frac{p}{q}"> е свидетел.

Следователно релацията е транзитивна, но ние доказахме също, че е и рефлексивна и симетрична, от където следва че <img src="https://latex.codecogs.com/svg.latex?\Large&space;R"> е релация на еквивалентсност.
