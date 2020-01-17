## Задача 36.

Нека <img src="https://latex.codecogs.com/svg.latex?\Large&space;G"> e ацикличен граф с <img src="https://latex.codecogs.com/svg.latex?\Large&space;2n+2"> върха. Нека броят на върховете от степен <img src="https://latex.codecogs.com/svg.latex?\Large&space;3"> e <img src="https://latex.codecogs.com/svg.latex?\Large&space;n">, а този на върховете от степен <img src="https://latex.codecogs.com/svg.latex?\Large&space;1"> е <img src="https://latex.codecogs.com/svg.latex?\Large&space;n+2">. Докажете, че графът <img src="https://latex.codecogs.com/svg.latex?\Large&space;G"> е свързан.

*Док-во:*

След като по условие <img src="https://latex.codecogs.com/svg.latex?\Large&space;G"> е ацикличен, то <img src="https://latex.codecogs.com/svg.latex?\Large&space;G"> може да се разбие на <img src="https://latex.codecogs.com/svg.latex?\Large&space;k"> компоненти на свързаност, които също ще са ациклични, но за разлика от <img src="https://latex.codecogs.com/svg.latex?\Large&space;G"> за тях може да кажем, че са свързани със сигурност (от разбиването). Следователно тези <img src="https://latex.codecogs.com/svg.latex?\Large&space;D_k"> компоненти на свързаност ще са дървета. За всяка компонента на свързаност <img src="https://latex.codecogs.com/svg.latex?\Large&space;D_k"> ще имаме <img src="https://latex.codecogs.com/svg.latex?\Large&space;|E_D|=|V_D|-1">. Тоест <img src="https://latex.codecogs.com/svg.latex?\Large&space;|E|=\sum^{k}|E_D|=\sum^{k}(|V_D-1|)=|V|-k=2n+2-k."> [(зад. 29)](https://github.com/andy489/Discrete_Structures/blob/master/DS1%20Graphs/Task%2029.md) Сега, от формулата на Ойлер имаме, че

<img src="https://latex.codecogs.com/svg.latex?\Large&space;2|E|=\sum_{u\in{V}}deg(u)=n.3+(n+2).1=4n+2">.

От тук следва, че <img src="https://latex.codecogs.com/svg.latex?\Large&space;2(2n+2-к)=4n+2"> или <img src="https://latex.codecogs.com/svg.latex?\Large&space;k=1">, което искахме да докажем, тъй като <img src="https://latex.codecogs.com/svg.latex?\Large&space;k"> е броя на компонентите на свързаност.
