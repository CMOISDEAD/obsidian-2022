# Teorema del binomio

## Definición:

Si $x$ y $y$ son variables y $n$ es un numero entero positivo, entonces:

$$
\begin{align*}
	(x+y)^n = 
	(\substack{n\\0})\ x^0\ y^n +
	(\substack{n\\1})\ x^1\ y^{n-1} +
	(\substack{n\\2})\ x^2\ y^{n-2} +
	(\substack{n\\3})\ x^3\ y^{n-3} +
	\ldots +
	(\substack{n\\n})\ x^n\ y^{n-n}
\end{align*}
$$

Es lo mismo que:

$$
\begin{align*}
	\sum_{i\ =\ 0}^n\ (\substack{n\\i})\ x^i\ y^{n-1}
\end{align*}
$$

---

**Ejemplo:** Resuelva aplicando el teorema.
$$
\begin{align*}
	(x+y) = \sum_{i=0}^4\ (\substack{4\\i})\ x^i\ y^{4-i}
\end{align*}
$$
**Solución:**

$$
\begin{align*}
	= (\substack{4 \\ 0})\ x^0\ y^{4-0}\ +\
	(\substack{4 \\ 1})\ x^1\ y^{4-1}\ +\
	(\substack{4 \\ 2})\ x^2\ y^{4-2}\ +\
	(\substack{4 \\ 3})\ x^3\ y^{4-3}\ +\
	(\substack{4 \\ 4})\ x^4\ y^{4-3}\
\end{align*}
$$

$$
\begin{align*}
	= 1\ x^0y^4\ +\
	4\ xy^3\ +\
	6\ x^2y^2\ +\
	4\ x^3y^1\ +\
	1\ x^4y^0\
\end{align*}
$$

$$
\begin{align*}
	= y^4\ +\
	4\ xy^3\ +\
	6\ x^2y^2\ +\
	4\ x^3y\ +\
	x^4\
\end{align*}
$$

---

**Ejemplo:** Cual coeficiente de $x^8y^4$ en el desarrollo de:

$$
\begin{align*}
	(x+y)^{12}
\end{align*}
$$

**Solución:**

$$
\begin{align*}
	(x+y)^{12} &= (\substack{12\\8})\ x^8y^4 \\
			   &= \frac{12!}{4! \cdot 8!} \\ 
			   &= 495\ x^8y^4
\end{align*}
$$

---

## Teorema

Para coeficientes positivos $n,t$ el coeficiente de:

$$
\begin{align*}
	x_{1}^{n_1}\ \cdot
	x_{2}^{n_2}\ \cdot
	x_{3}^{n_3}\ \ldots
\end{align*}
$$

En el desarrollo de:

$$
\begin{align*}
	\frac{n!}{n_1!\ \cdot n_2!\ \cdot n_3!\ \ldots n_t!}
\end{align*}
$$

Donde cada $n_i$ es un elemento entero $0\le n_i < n$ y $n_1\ +\ n_1\ +\ n_1\ +\ \ldots\ +\ n_t\ =\ n$.

**Ejemplo:** En el desarrollo de $(x+y+z)^7$ el coeficiente de $x^2y^22^3$ es:

**Solucion:**
$$
\begin{align*}
	\frac{7!}{2!\ \cdot\ 2!\ \cdot\ 3!}\ &=\ 210
\end{align*}
$$

---

**Ejemplo:** El coeficiente de $a^2\ \cdot\ b^3\ \cdot\ c^2\ \cdot\ d^5$ en el desarrollo de $(a+2b-3c+2d+5)^{16}$ es:

__Nota:__ Se pueden los datos por variables tal que $x,\ y,\ z,\ m,\ p$ representarían los valores de el desarrollo.

**Solucion:**

$$
\begin{align*}	
 \frac{16!}{2!\ \cdot\ 3!\ \cdot\ 2!\ \cdot\ 5!}
\end{align*}
$$

$$
\begin{align*}
	302,702,400\ \cdot\ (5)^4\ \cdot\ x^2\ \cdot\ y^3\ \cdot\ z^2\ \cdot\ m^5
\end{align*}
$$

Se remplazan las variables por los valores originales.

$$
\begin{align*}
	302,702,400\ \cdot\ (5)^4\ \cdot\ a^2\ \cdot\ (2b)^3\ \cdot\ (3c)^2\ \cdot\ (2d)^5
\end{align*}
$$

Se resuelven las potencias.

$$
\begin{align*}
	302,702,400\ \cdot\ (5)^4\ \cdot\ a^2\ \cdot\ 2^3\ \cdot\ b^3\ \cdot\ 3^2\ \cdot\ c^2\ \cdot\ 2^5\ \cdot\ d^5
\end{align*}
$$

Se simplifica.

$$
\begin{align*}
	302,702,400\ \cdot\ (5)^4\ \cdot\ 3^2\ \cdot\ 2^5\ \cdot\ a^2\ \cdot\ 2^3\ \cdot\ b^3\ \cdot\ c^2\ \cdot\ d^5
\end{align*}
$$

---

# Libro
- Pagina #32 -> 33 y 34.
- Pagina #15 -> 26 a 29.
- Pagina #13 -> 25 a 28.