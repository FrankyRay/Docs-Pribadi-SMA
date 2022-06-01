# MathJax Section

## Trial and Error

\( \int (x-3)(x^2 - 6x + 1)^{-3} dx \)

**Persamaan:**

$$
\begin{align}
    \int &(x-3)(x^2 - 6x + 1)^{-3} dx = \int (x^2 - 6x + 1)^{-3}(x-3) dx
\end{align}
$$

**Misalkan:**

$$
\begin{align}
    u &= x^2 - 6x + 1 \\
    du &= (2x - 6) dx \\
    du &= 2 (x - 3) dx \rightarrow (x-3) dx = \frac{1}{2} du
\end{align}
$$

**Maka:**

$$
\begin{align}
    \int &(x^2 - 6x + 1)^{-3}(x-3) \\
    &= \int u^{-3} \times \frac{1}{2} du \\
    &= \frac{1}{2} \int u^{-3} du \\
    &= \frac{1}{2} \times \frac{1}{-2} u^{-2} + C \rightarrow u = x^2 - 6x + 1 \\
    &= \frac{1}{-4} (x^2 - 6x + 1)^{-2} + C \\
    &= - \frac{1}{4 (x^2 - 6x + 1)^{-2}} + C
\end{align}
$$

## Link Docs

- [MathJax basic tutorial and quick reference](https://math.meta.stackexchange.com/questions/5020/mathjax-basic-tutorial-and-quick-reference)
- [MathJax - Tex : Quick Reference Guide](https://www.sqlpac.com/en/documents/mathjax-tex-practical-handbook-quick-reference.html)

## Library

### Aligned Equation

$$
\begin{aligned}
    \int &( 6x^5 - 12x^4 + 36x^3 - 6x^2 + 3x - 50 ) dx \\ 
    &= \frac{6}{6} x^6 - \frac{12}{5} x^5 + \frac{36}{4} x^4 - \frac{6}{3} x^3 + \frac{3}{2} x^2 - 50x + C \\
    &= x^6 - \frac{12}{5} x^5 + 9x^4 - 2x^3 + \frac{3}{2} x^2 - 50x + C
\end{aligned}
$$
