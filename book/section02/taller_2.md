
# Taller 2 de MMAF

## A Ejercicios de repaso

### A.1


Recordar que si $a,b$ tienen el mismo signo, entonces $ab$ y $\frac{a}{b}$ son positivos, mientras que si $a$ y $b$ tienen signos contrarios, entonces $ab$ y $\frac{a}{b}$ son negativos.

Con base en lo anterior, y asumiendo que $x > 0$ y $y < 0$, determina el signo de:
$$
\dfrac{x}{y} + \dfrac{y}{x}
$$
Argumenta claramente el modo en que lo determinaste.

Ahora supón que $x < 0$ y $y > 0$. Justifica el signo de:

- $xy^2$
- $\dfrac{x - y}{xy}$
- $y(y - x)$

### A.2

Expresa los siguientes enunciados como una desigualdad:

1. $x$ es negativo.
2. El cociente de $p$ y $q$ es a lo más 7.
3. El valor absoluto de $x$ es mayor a 7.
4. $w$ es mayor o igual a $-4$.

### A.3

Reescribe el número sin usar el símbolo de valor absoluto y simplifica el resultado:

1. $|-3 - 2|$
2. $|-11 + 1|$
3. $|\pi - 4|$
4. $\left|\frac{1}{5} - \frac{1}{3}\right|$

### A.4

Reescribe la expresión sin valor absoluto y simplifica:

1. $|3 + x|$, si $x < -3$.
2. $|a - b|$, si $a < b$.
3. $|7 + x|$, si $x \geq 7$.
4. $|x^2 + 4|$.
5. $|-x^2 - 1|$.

### A.5

Sustituye el símbolo $\square$ con $=$ o $\neq$ para que el enunciado sea verdadero para todos los números reales $a, b, c$ y $d$, siempre que las expresiones estén definidas:

1. $\dfrac{a + c}{b + d} \square \dfrac{a}{b} + \dfrac{c}{d}$
2. $\dfrac{a - b}{b - a} \square -1$
3. $-(a + b) \square -a + b$

### A.6

Simplifica:

1. $\left(-\frac{3}{2}\right)^4 - 2^{-4}$
2. $\left(\dfrac{4a^2b}{a^3b^2}\right)\left(\dfrac{5a^2b}{2b^4}\right)$
3. $\left(\dfrac{3x^5y^4}{x^0y^{-3}}\right)^2$
4. $(4a^2b)^4\left(\dfrac{-a^3}{2b}\right)^2$

### A.7

Determina si el número es positivo o negativo:

1. $(-10 - 10)^{-10 + 10}$
2. $(-1)^{-1}(-1)^0(-1)$
3. $(\pi^2\pi^3\pi^{-4})^{-1}$

### A.8

¿Crees que los siguientes cálculos son correctos? Justifica tu respuesta:

1. $2^3 = 6$
2. $\dfrac{2}{4 + 3} = \dfrac{2}{4} + \dfrac{2}{3}$
3. $-2 + 3 = -(2 + 3)$

### A.9

Simplifica la expresión y racionaliza el denominador cuando sea apropiado:

1. $\sqrt[4]{\dfrac{5x^8y^3}{27x^2}}$
2. $\sqrt[5]{\dfrac{5x^7y^2}{8x^3}}$
3. $\sqrt[3]{3t^4v^2}\sqrt[3]{-9t^{-1}v^4}$

### A.10

Existe una fórmula para determinar la eficiencia del levantamiento de pesas por parte de atletas que practican esta actividad. Si un levantador que pesa $b$ kilogramos levanta $w$ kilogramos de peso, entonces la eficiencia del levantamiento está dada por:

$$
W = \dfrac{w}{\sqrt[3]{b - 35}}
$$

Supón que dos levantadores que pesan 75 y 120 kilogramos levantan pesas de 180 y 250 kilogramos, respectivamente. Usa la fórmula anterior para determinar el mejor levantador de pesas.


### A.11

La temperatura $T$ dentro de una nube a una altura $h$ (en pies) sobre la base de la nube se puede aproximar usando la siguiente ecuación, donde $B$ es la temperatura de la nube en su base:

$$
T = B - \left(\frac{3}{100}\right)h
$$

Determine la temperatura a $10,000$ pies en una nube con una temperatura de su base de $55°F$ y una altura de base de $4000$ pies.


### A.12

La demanda de una mercancía por lo general depende de su precio. Si otros factores no afectan la demanda, entonces la cantidad $Q$ comprada a un precio $P$ (en centavos) está dada por la siguiente ecuación, donde $k$ y $c$ son constantes positivas:

$$
Q = kP^{-c}
$$

Si $k = 10^{5}$ y $c = \frac{1}{2}$, encuentre el precio que resultará en una compra de $5000$ artículos.


### A.13

Si dos resistores $R_{1}$ y $R_{2}$ se conectan en paralelo en un circuito eléctrico, la resistencia neta $R$ está dada por:

$$
\frac{1}{R} = \frac{1}{R_{1}} + \frac{1}{R_{2}}
$$

Si $R_{1} = 10$ ohms, ¿qué valores de $R_{2}$ resultarán en una resistencia neta de menos de $5$ ohms?


## B Ejercicios computacionales

### B.1
Encuentre el resultado de las siguientes operaciones en una celda de código:

1. $3^4$
2. $\sqrt{5}$
3. $\sqrt[3]{8}$
4. $\Big(\frac{3}{4} - \frac{1}{2}\Big)^{-2}$

**Note** debes usar la función print para mostrar el resultado, puede ver la sección de [C.1.5](https://colab.research.google.com/github/abelalv/MMAF_2025/blob/main/seccion_1/MMAF_python_1.ipynb) para más información.


### B.2

Realiza las siguientes operaciones usando la librería `math`:

1. $\sqrt{3} + \sqrt{5}$
2. $|3 - 5|$
3. $\Big|\frac{1}{3} - \Big(\frac{-1}{5}\Big)^{-3}\Big|$
4. $\Big(\sqrt[3]{8} - \Big|\frac{5}{-3}-\frac{-1}{2}\Big|\Big)^2$

**Note** debes usar la función print para mostrar el resultado, puede ver la sección de [C.1.6](https://colab.research.google.com/github/abelalv/MMAF_2025/blob/main/seccion_1/MMAF_python_1.ipynb) para más información.

### B.4

Escribe los resultados de la operaciones anteriores usando notación científica.

1. con 3 cifras significativas
2. con 5 cifras significativas
4. con 7 cifras significativas

**Note** debes usar la función print para mostrar el resultado, puede ver la sección de [C.1.7](https://colab.research.google.com/github/abelalv/MMAF_2025/blob/main/seccion_1/MMAF_python_1.ipynb) para más información.