
A **primitive function** (or antiderivative) of $f(x)$ is a function $F(x)$ such that:

$$
F'(x) = f(x) \quad \text{for all } x \in \mathbb{R}
$$

This leads to the definition of the **indefinite integral**:

$$
\int f(x)\, dx = F(x) + C
$$

Where $C$ is the **constant of integration** — information lost during differentiation.

> 💡 *Piensa en una integral indefinida como "la familia de funciones que podrían haber generado esta derivada".*

When adding values, the *indefinite integral* turns into a *[[Definite Integral|definite integral]]


---

## 📏 Basic Integration Rules

### 🔹 Constant Rule

$$
\int a\, dx = ax + C \quad \text{where } a, C \in \mathbb{R}
$$

> 🧠 *Recuerda que integrar una constante es solo multiplicar por $x$.*

---

### 🔹 Power Rule

$$
\int x^a\, dx = \frac{1}{a+1} x^{a+1} + C \quad \text{for } a \ne -1
$$

> ⚠️ *No se puede usar esta regla si el exponente es $-1$. Ese es el caso logarítmico.*

---

### 🔹 Natural Exponential

$$
\int e^x\, dx = e^x + C
$$

> ✨ *$e^x$ is its own integral — muy elegante.*

---

### 🔹 Exponential with Linear Exponent

$$
\int e^{ax}\, dx = \frac{1}{a} e^{ax} + C \quad \text{for } a \ne 0
$$

> 🧠 *Divide por el coeficiente del exponente.*

---

### 🔹 General Exponential Rule

$$
\int a^x\, dx = \frac{1}{\ln a} a^x + C \quad \text{for } a > 0,\ a \ne 1
$$

> 📌 *Para bases como $2^x$, $10^x$, etc.*

---

## 📚 Logarithmic Rules

### 🔹 Basic Logarithmic Rule

$$
\int \frac{1}{x}\, dx = \ln|x| + C
$$

> ⚠️ *Usa valor absoluto siempre.*

---

### 🔹 Log Rule with Derivative on Top

If the **numerator is the derivative of the denominator**, then:

$$
\int \frac{f'(x)}{f(x)}\, dx = \ln|f(x)| + C
$$

**Example:**

$$
\int \frac{2x + 2}{x^2 + 2x}\, dx = \ln|x^2 + 2x| + C
$$

> 🔍 *Busca funciones donde el numerador es la derivada del denominador.*

---

## 🎯 Trigonometric Integrals

$$
\begin{align*}
\int \sin x\, dx &= -\cos x + C \\
\int \cos x\, dx &= \sin x + C
\end{align*}
$$

> 🧠 *Estas debes memorizarlas sí o sí.*

---

## 🤝 Integration by Parts

Used for **products of functions**. It's based on the product rule of differentiation.

### 🔹 Formula

$$
\int u\, dv = uv - \int v\, du
$$

> 💡 Mnemonic:  
> *Un Día Ví, Una Vaca sin cola Vestida De Uniforme*  
> ($u\,dv = uv - \int v\,du$)

---

### 🔹 Example

Evaluate:

$$
\int x \cos x\, dx
$$

Choose:

- $u = x \Rightarrow du = dx$
- $dv = \cos x\, dx \Rightarrow v = \sin x$

Apply the formula:

$$
\int x \cos x\, dx = x \sin x - \int \sin x\, dx = x \sin x + \cos x + C
$$

> ✅ *Elige $u$ de modo que su derivada se simplifique (por ejemplo, un polinomio).*

