# Interval

## Interval Tak Tentu

Interval tak tentu mempunyai persamaan

$$
\begin{aligned}
    \int ax^n dx &= \frac{a}{n+1} x^{n+1} + C \\
    \int a dx &= ax + C
\end{aligned}
$$

??? summary "Rumus Cepat"

    Jika \( \int ax^{a-1} dx \), maka nilainya akan \( x^a + C \)

### Contoh

#### Persamaan 1

$$
\begin{aligned}
    \int 4x^3 dx &= \frac{4}{3+1} x^{3+1} + C \\
    &= \frac{4}{4} x^4 + C \\
    &= x^4 + C
\end{aligned}
$$

#### Persamaan 2

$$
\begin{aligned}
    \int 12x^4 dx &= \frac{12}{4+1} x^{4+1} + C \\
    &= \frac{12}{5} x^5 + C
\end{aligned}
$$

#### Persamaan 3 - Pangkat Negatif

$$
\begin{aligned}
    \int 5x^{-3} dx &= \frac{5}{-3+1} x^{-3+1} + C \\
    &= \frac{5}{-2} x^{-2} + C \\
    &= -\frac{5}{2x^2} + C
\end{aligned}
$$

#### Persamaan 4 - X Dalam Pecahan

$$
\begin{aligned}
    \int \frac{5}{x^4} dx &= \int 5x^{-4} dx \\
    &= \frac{5}{-4+1} x^{-4+1} + C \\
    &= \frac{5}{-3} x^{-3} + C \\
    &= -\frac{5}{3x^3} + C
\end{aligned}
$$

#### Persamaan 5 - Akar Pangkat

$$
\begin{aligned}
    \int \sqrt{x^3} dx &= \int x^{\frac{3}{2}} dx \\
    &= \frac{1}{\frac{3}{2} +1} x^{\frac{3}{2} +1} + C \\
    &= \frac{2}{5} x^{\frac{5}{2}} + C \\
    &= \frac{2}{5} \sqrt{x^5} + C
\end{aligned}
$$

#### Persamaan 6 - Polinomial

$$
\begin{aligned}
    \int &( 6x^5 - 12x^4 + 36x^3 - 6x^2 + 3x - 50 ) dx \\
    &= \frac{6}{6} x^6 - \frac{12}{5} x^5 + \frac{36}{4} x^4 - \frac{6}{3} x^3 + \frac{3}{2} x^2 - 50x + C \\
    &= x^6 - \frac{12}{5} x^5 + 9x^4 - 2x^3 + \frac{3}{2} x^2 - 50x + C
\end{aligned}
$$

## Integral Tentu

Interval tentu mempunyai persamaan

$$
\begin{aligned}
    \int_a^b f(x) dx &= \left[ F(x) \right]_a^b \\
    &= F(b) - F(a) 
\end{aligned}
$$

### Contoh

#### Persamaan 1

$$
\begin{aligned}
    \int_1^2 3x^2 dx &= \left[ x^3 \right]_1^2 \\
    &= 2^3 - 1^3 \\
    &= 8 - 1 = 7
\end{aligned}
$$

#### Persamaan 2 - Polinomial

$$
\begin{aligned}
    \int_2^3 &( 4x^3 - 3x^2 - 2x + 4 ) dx \\
    &= \left[ x^4 - x^3 - x^2 + 4x \right]_2^3 \\
    &= \left( 3^4 - 3^3 - 3^2 + 4(3) \right) - \left( 2^4 - 2^3 - 3^2 + 4(3) \right) \\
    &= ( 81 - 27 - 9 + 12 ) - ( 16 - 8 - 4 + 12 ) \\
    &= 57 - 16 = 41
\end{aligned}
$$

## Integral Subtitusi

### Contoh

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