# Задание для лабораторной работы № 2


### 1.1 Оценки математического ожидания, дисперcии, медианы

##### 1.  Пусть случайная величина $\xi$ имеет распределение, задаваемое плотностью $f_{\xi}(x) = \theta^2xe^{−\theta x}$.  Для каждого $\theta \in {0.5, 2, 8}$

- Аналитически вычислить математическое ожидание, дисперсию и математическое ожидание квадрата $\xi$. Привести в отчет. 
- Для $k \in {2^4, 2^5, \cdots, 2^{15}}$ построить выборку из $k$ элементов. 
- Для каждой из них посчитать оценки: математического ожидания, дисперсии и квадрата математического ожидания параметра из варианта. 
- Для каждой из выборок и оценок визуализировать это все на графиках (для каждой оценки — свой график), где по вертикальной оси — оценка, а по горизонтальной — $k$, плюс, добавьте горизонтальную линию, отвечающую за аналитически полученную оценку.

##### 2.Дана плотность распределения случайной величины $\xi$:

##### $$ f_{\xi}^{\lambda, \alpha} (x) = \begin{cases} \lambda e^{-\lambda(x - \alpha)}, & \quad x \geq \alpha \\  0, & \quad \text{else} \end{cases}$$

- Аналитически вычислите значение моды, математического ожидания и медианы.
- Создайте две выборки: одну довольно большого размера (10000 наблюдений, например), а вторую маленькую (например, 20). Постройте оценки моды, математического ожидания и медианы. 
- Постройте для первой выборки на одном графике: гистограмму распределения значений из выборки и три вертикальных линии оценок моды, математического ожидания и медианы. 
- Для второй выборки сделайте то же самое. 
- Постройте ещё график рядом для первой выборки, но с функцией распределения плотности и аналитическими значениями мод, математического жидания и медианы.
- То же самое, для второй.

##### Попробуйте поизменять размер выборки и посмотреть на то, например, сходится ли медиана к математическому ожиданию, или нет.


### 1.2 Моделирование совместного распределения двух СВ

##### 1. Пусть совместное распределение двух случайных величин задано таблицей

$$
\begin{matrix}
\xi / \eta & 1 & 2 & 3 & \ldots \\
\\
-1 & \frac{2}{5} \cdot \frac{1}{2^1}  &  \frac{2}{5} \cdot \frac{1}{2^2} &  \frac{2}{5} \cdot \frac{1}{2^3} & \ldots  \\
\\
0 & \frac{1}{5} \cdot \frac{1}{2^1}  &  \frac{1}{5} \cdot \frac{1}{2^2} &  \frac{1}{5} \cdot \frac{1}{2^3} & \ldots \\
\\
1 &  \frac{2}{5} \cdot \frac{1}{2^1} &  \frac{2}{5} \cdot \frac{1}{2^2} &  \frac{2}{5} \cdot \frac{1}{2^3} & \ldots
\end{matrix}
$$

##### где $\eta$ принимает все значения из $N$. Вычислить корреляционую матрицу аналитически и приближенно (на основе моделирования).
