### ДИСКРЕТНИ СТРУКТУРИ 1
#### *ТЕОРИЯ 2*

**1.** Максимална верига/антиверига. Нека <img src="https://latex.codecogs.com/svg.latex?\Large&space;<A,R>"> е ч.н.м. и <img src="https://latex.codecogs.com/svg.latex?\Large&space;S"> е негова верига/антиверига. Казваме, че <img src="https://latex.codecogs.com/svg.latex?\Large&space;S"> е максимална верига/антиверига, ако за свяка друга верига/антиверига <img src="https://latex.codecogs.com/svg.latex?\Large&space;S'"> на <img src="https://latex.codecogs.com/svg.latex?\Large&space;A">
е изпълнено: <img src="https://latex.codecogs.com/svg.latex?\Large&space;|S|\ge{|S'|}">.

**2.** Верижно/антиверижно разбиване. Нека <img src="https://latex.codecogs.com/svg.latex?\Large&space;<A,R>"> е ч.н.м. Една фамилия <img src="https://latex.codecogs.com/svg.latex?\Large&space;A_1,A_2,...,A_n"> от подмножества на <img src="https://latex.codecogs.com/svg.latex?\Large&space;A"> ще наричаме верижно/антиверижно разбиване, ако е изпълнено:
- <img src="https://latex.codecogs.com/svg.latex?\Large&space;A_1,A_2,...,A_n"> е разбиване на <img src="https://latex.codecogs.com/svg.latex?\Large&space;A">;
- <img src="https://latex.codecogs.com/svg.latex?\Large&space;A_1,A_2,...,A_n"> са вериги/антивериги.

**3.** Минимално верижно/антиверижно разбиване. Нека <img src="https://latex.codecogs.com/svg.latex?\Large&space;<A,R>"> е ч.н.м. Казваме, че фамилията <img src="https://latex.codecogs.com/svg.latex?\Large&space;S=\{A_1,A_2,...,A_n\}"> от подмножества на <img src="https://latex.codecogs.com/svg.latex?\Large&space;A"> е минимално верижно/антиверижно разбиване на <img src="https://latex.codecogs.com/svg.latex?\Large&space;A">, ако:
- <img src="https://latex.codecogs.com/svg.latex?\Large&space;A_1,A_2,...,A_n"> е верижно/антиверижно разбиване на <img src="https://latex.codecogs.com/svg.latex?\Large&space;A">;
- За всяко верижно/антиверижно разбиване <img src="https://latex.codecogs.com/svg.latex?\Large&space;S'"> на  <img src="https://latex.codecogs.com/svg.latex?\Large&space;A"> имаме <img src="https://latex.codecogs.com/svg.latex?\Large&space;|S|\le{|S'|}">.

**4.** Краен ориентиран мултиграф. Нека <img src="https://latex.codecogs.com/svg.latex?\Large&space;V=\{v_1,v_2,...,v_n\}"> е крайно множество, елементите на което са върхове, а <img src="https://latex.codecogs.com/svg.latex?\Large&space;E=\{e_1,e_2,...,e_m\}"> е крайно множество, елементите на което са ребра. Функцията <img src="https://latex.codecogs.com/svg.latex?\Large&space;f_G:E\rightarrow{V\times{V}}">, съпоставяща на всяко ребро наредена двойка от върхове, наричаме краен ориентиран граф.

**5.** Краен ориентиран граф. Нека <img src="https://latex.codecogs.com/svg.latex?\Large&space;G(V,E,f_G)"> е краен ориентиран мултиграф и функцията <img src="https://latex.codecogs.com/svg.latex?\Large&space;f_G"> е инективна. Тогава <img src="https://latex.codecogs.com/svg.latex?\Large&space;G(V,E,f_G)"> наричаме краен ориентиран граф и бележим само с <img src="https://latex.codecogs.com/svg.latex?\Large&space;G(V,E)">, където <img src="https://latex.codecogs.com/svg.latex?\Large&space;E\subseteq{V\times{V}}">.

**6.** Краен неориентиран граф (*Граф*). Нека <img src="https://latex.codecogs.com/svg.latex?\Large&space;G(V,E)"> е краен ориентиран граф, такъв че релацията <img src="https://latex.codecogs.com/svg.latex?\Large&space;E\subseteq{V\times{V}}"> е антирефлексивна и симетрична. Тогава <img src="https://latex.codecogs.com/svg.latex?\Large&space;G(V,E)"> наричаме краен неориентиран граф или просто *граф*.

**7.** Краен неориентиран мултиграф. Крайният неориентиран граф <img src="https://latex.codecogs.com/svg.latex?\Large&space;G(V,E)"> може да превърнем в краен неориентиран мултиграф, ако позволим повече от едно неориентирано ребро да свързва два върха от <img src="https://latex.codecogs.com/svg.latex?\Large&space;V)">, както и наличието на примки, т.е. ако вместо множеството <img src="https://latex.codecogs.com/svg.latex?\Large&space;E\subseteq{V\times{V}}"> вземем мултимножество от елементите на {V\times{V}}.
