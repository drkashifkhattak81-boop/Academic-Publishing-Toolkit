# ? LaTeX to Word (OMML / Alt+=) Math Cheat Sheet

> **The Ultimate Guide to Typing Lightning-Fast Native Equations in Microsoft Word**  
> *Forget clumsy equation builder mouse-clicks. Use Word's built-in linear math syntax (`Alt + =`) to typeset academic formulas in seconds.*

---

## ?? How to Use Word Linear Math Mode
1. In Microsoft Word, press **`Alt + =`** (Windows) or **`Ctrl + =`** (macOS) to open an equation block.
2. Type the shortcut command (e.g., `\alpha`, `x^2`, `\sqrt(x)`).
3. Press the **`Spacebar`** ? Word immediately converts your linear text into native rendered **OMML (Office Math Markup Language)**!

---

## ?? 1. Fractions, Roots & Powers

| Mathematical Meaning | Visual Preview | Word `Alt+=` Shortcut | Spacebar Trigger |
| :--- | :--- | :--- | :--- |
| **Fraction** | $\frac{a}{b}$ | `(a)/(b)` or `a/b` | Press `Space` after `/` |
| **Square Root** | $\sqrt{x}$ | `\sqrt(x)` | Press `Space` after `)` |
| **N-th Root** | $\sqrt[n]{x}$ | `\sqrt(n&x)` | Press `Space` after `)` |
| **Superscript / Power** | $x^2$ | `x^2` | Press `Space` after exponent |
| **Subscript / Index** | $x_i$ | `x_i` | Press `Space` after subscript |
| **Combined Sub/Super** | $x_i^2$ | `x_i^2` | Press `Space` after power |
| **Double Subscript** | $x_{i,j}$ | `x_(i,j)` | Press `Space` after `)` |

---

## ??? 2. Greek Letters

| Symbol | LaTeX / Word Input | Symbol | LaTeX / Word Input | Symbol | LaTeX / Word Input |
| :---: | :--- | :---: | :--- | :---: | :--- |
| $\alpha$ | `\alpha` + `Space` | $\theta$ | `\theta` + `Space` | $\tau$ | `\tau` + `Space` |
| $\beta$ | `\beta` + `Space` | $\vartheta$ | `\vartheta` + `Space` | $\upsilon$ | `\upsilon` + `Space` |
| $\gamma$ | `\gamma` + `Space` | $\iota$ | `\iota` + `Space` | $\phi$ | `\phi` + `Space` |
| $\delta$ | `\delta` + `Space` | $\kappa$ | `\kappa` + `Space` | $\varphi$ | `\varphi` + `Space` |
| $\epsilon$ | `\epsilon` + `Space` | $\lambda$ | `\lambda` + `Space` | $\chi$ | `\chi` + `Space` |
| $\varepsilon$ | `\varepsilon` + `Space`| $\mu$ | `\mu` + `Space` | $\psi$ | `\psi` + `Space` |
| $\zeta$ | `\zeta` + `Space` | $\nu$ | `\nu` + `Space` | $\omega$ | `\omega` + `Space` |
| $\eta$ | `\eta` + `Space` | $\xi$ | `\xi` + `Space` | $\Delta$ | `\Delta` + `Space` |
| $\Gamma$ | `\Gamma` + `Space` | $\Theta$ | `\Theta` + `Space` | $\Omega$ | `\Omega` + `Space` |
| $\Lambda$ | `\Lambda` + `Space` | $\Sigma$ | `\Sigma` + `Space` | $\Phi$ | `\Phi` + `Space` |

---

## ?? 3. Calculus, Integrals & Limits

| Operation | LaTeX / Word Syntax | Result / Explanation |
| :--- | :--- | :--- |
| **Definite Integral** | `\int_a^b (f(x)dx)` + `Space` | Integral with limits from $a$ to $b$ |
| **Indefinite Integral**| `\int f(x)dx` + `Space` | Standard single integral $\int$ |
| **Double Integral** | `\iint` + `Space` | Surface integral $\iint$ |
| **Contour Integral** | `\oint` + `Space` | Closed line loop integral $\oint$ |
| **Partial Derivative** | `(\partial y)/(\partial x)` + `Space` | Fraction with $\frac{\partial y}{\partial x}$ |
| **Limit with Subscript**| `\lim_(x\to\infty)` + `Space` | $\lim_{x \to \infty}$ with limit below operator |
| **Derivative Prime** | `f'(x)` or `f''(x)` | First and second derivative prime notation |

---

## ?? 4. Summations, Products & Operators

| Operation | Word `Alt+=` Code | Note |
| :--- | :--- | :--- |
| **Summation with Bounds** | `\sum_(i=1)^n (x_i)` + `Space` | $\sum_{i=1}^{n} x_i$ with proper stacked bounds |
| **Product Operator** | `\prod_(i=1)^N` + `Space` | Stacked capital product $\prod_{i=1}^N$ |
| **Gradient / Del** | `\nabla` + `Space` | Nabla vector operator $\nabla$ |
| **Infinity** | `\infty` + `Space` | $\infty$ symbol |
| **Plus-Minus** | `\pm` + `Space` | $\pm$ symbol |
| **Proportional To** | `\propto` + `Space` | $\propto$ relation |
| **Approx. Equal** | `\approx` + `Space` | $\approx$ relation |
| **Equivalent / Defined**| `\equiv` + `Space` | $\equiv$ relation |

---

## ?? 5. Vectors, Accents & Annotations

| Mathematical Type | Word Shortcut | How to Trigger in Word |
| :--- | :--- | :--- |
| **Vector Arrow** | `x\vec` + `Space` + `Space` | Type `x\vec` then press Space twice: $\vec{x}$ |
| **Hat / Estimator** | `x\hat` + `Space` + `Space` | Type `x\hat` then press Space twice: $\hat{x}$ |
| **Bar / Average** | `x\bar` + `Space` + `Space` | Type `x\bar` then press Space twice: $\bar{x}$ |
| **Tilde** | `x\tilde` + `Space` + `Space` | Type `x\tilde` then press Space twice: $\tilde{x}$ |
| **Time Derivative Dot**| `x\dot` + `Space` + `Space` | Type `x\dot` then press Space twice: $\dot{x}$ |
| **Second Derivative** | `x\ddot` + `Space` + `Space` | Type `x\ddot` then press Space twice: $\ddot{x}$ |
| **Bold Matrix/Vector** | Select variable $\rightarrow$ `Ctrl + B` | Renders upright bold $\mathbf{W}$ |

---

## ?? 6. Matrices & Systems of Equations

### $2 \times 2$ Matrix in Word:
Type:
```text
[\matrix(a&b@c&d)]
```
Then press **`Spacebar`** twice!
* Use `&` to separate columns.
* Use `@` to separate rows.
* Word builds a pristine native matrix with dynamic scaling square brackets:
  $$\begin{bmatrix} a & b \\ c & d \end{bmatrix}$$

### $3 \times 3$ Identity Matrix:
```text
[\matrix(1&0&0@0&1&0@0&0&1)]
```

### Piecewise Function (Cases):
```text
f(x)={\eqarray(x^2,&x>=0@-x,&x<0)
```
Press `Space` to build a clean two-branch piecewise bracket!

---

## ?? 7. Equation Numbering Right-Aligned Trick in Word
In IEEE and Elsevier papers, equations must be centered with numbers aligned on the far right: `(1)`.

**The Shortcut:**
1. Type your equation inside `Alt+=`: `E=mc^2`
2. Type **`#(1)`** directly after the formula.
3. Press **`Enter`**.
4. Word automatically shifts `E=mc^2` to the exact center of the line and pushes `(1)` to the right margin!

---

## ? Tired of Retyping Complex Formulas?

Converting an entire LaTeX paper with 50+ nested equations into native Word OMML can take **days of tedious manual typing**.

[![Convert LaTeX to OMML Online](https://img.shields.io/badge/Automate_With-ManuscriptOS_Math_Synthesizer-7c3aed?style=for-the-badge&logo=mathworks)](https://manuscriptos.io/?utm_source=github&utm_medium=lead_magnet&utm_campaign=academic_publishing_toolkit)

Use **[ManuscriptOS Math Synthesizer](https://manuscriptos.io/?utm_source=github&utm_medium=lead_magnet&utm_campaign=academic_publishing_toolkit)** to:
* Convert raw LaTeX math blocks (`\begin{equation}...\end{equation}`) into 100% native Word OMML.
* Preserve inline math (`$...$`) and display equations without raster image blurriness.
* One-click copy/paste into Microsoft Word (.docx)!