## Зядача 29.

Нека <img src="https://latex.codecogs.com/svg.latex?\Large&space;G(V,E)"> е граф без цикли и с <img src="https://latex.codecogs.com/svg.latex?\Large&space;n"> на брой върха и <img src="https://latex.codecogs.com/svg.latex?\Large&space;k"> компоненти на свързаност. Намерете <img src="https://latex.codecogs.com/svg.latex?\Large&space;|E|">.

*Решение:*

Нека <img src="https://latex.codecogs.com/svg.latex?\Large&space;G_i(V_i,E_i),{\;}i=\overline{1,k}"> са компонентите на свързаност на <img src="https://latex.codecogs.com/svg.latex?\Large&space;G">. Тогава са в сила следните твърдения:

- <img src="https://latex.codecogs.com/svg.latex?\Large&space;\bigcup_{i=1}^{k}V_i=V">;
- <img src="https://latex.codecogs.com/svg.latex?\Large&space;\bigcup_{i=1}^{k}E_i=E">;
- <img src="https://latex.codecogs.com/svg.latex?\Large&space;i\neq{j}\Rightarrow{V_i\cap{V_j}}=E_i\cap{E_j}=\varnothing">.

Следователно броя на върховете <img src="https://latex.codecogs.com/svg.latex?\Large&space;|V|=|V_1|+|V_2|+\cdots{+}|V_k|=\sum_{i=1}^{k}|V_i|"> и броя на ребрата <img src="https://latex.codecogs.com/svg.latex?\Large&space;|E|=|E_1|+E_2|+\cdots{+}|E_k|=\sum_{i=1}^{k}|E_i|"> (всеки връх и всяко ребро участва в точно една компонента на свързаност). Всяка компонента на свързаност е свързан граф. В <img src="https://latex.codecogs.com/svg.latex?\Large&space;G"> няма цикли, следователно във всяка негова компонента на свързаност няма цикли. Тогава за <img src="https://latex.codecogs.com/svg.latex?\Large&space;\forall{i}{\;}i=\overline{1,k}"> имаме: <img src="https://latex.codecogs.com/svg.latex?\Large&space;G_i"> е дърво <img src="https://latex.codecogs.com/svg.latex?\Large&space;\Rightarrow{|E_i|=|V_i|-1}">. Така <img src="https://latex.codecogs.com/svg.latex?\Large&space;|E|=|E_1|+|E_2|+\cdots{+}|E_k|=\sum_{i=1}^{k}|E_i|=\sum_{i=1}^{k}(|V_i|-1)=\sum_{i=1}^{k}|V_i|-\sum_{i=1}^{k}1=|V|-k=n-k">.
