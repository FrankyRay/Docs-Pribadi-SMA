---
hide:
  - navigation
---

# Kisi-Kisi PAT Matematika

!!! note "Soal"

    Dokumen lengkap berisi soal-soalnya ada [di sini](https://drive.google.com/file/d/1skDFu8cL1gvFdY9Rvwtd4Yk-szzKKWc_/view)

## 1. Limit

### Soal 1a

$$
\begin{aligned}
    \lim_{x \rightarrow 2} \frac{\sqrt{2+x^2}}{2x-1} &= \frac{\sqrt{2+(2)^2}}{2(2)-1} \rightarrow \text{Cara Subtitusi} \\
    &= \frac{\sqrt{2+4}}{4-1} \\
    &= \frac{\sqrt{6}}{3}
\end{aligned}
$$

### Soal 1b

$$
\begin{aligned}
    \lim_{x \rightarrow 3} \frac{x^2-2x-15}{x+3} &= \frac{(x-5)(x+3)}{(x+3)}
    &= x-5 \\
    &= 3-5 = -2
\end{aligned}
$$

### Soal 1c

$$
\begin{aligned}
    \lim_{x \rightarrow 4} \frac{3x^2-14x+8}{x^2-3x-4} &= \frac{(3x-2)(x-4)}{(x+1)(x-4)} \rightarrow \text{Cara Faktor} \\
    &= \frac{3x-2}{x+1} \\
    &= \frac{3(4)-2}{4+1} \\
    &= \frac{10}{5} = 2
\end{aligned}
$$

### Soal 1d

$$
\begin{aligned}
    \lim_{x \rightarrow 3} \frac{x^2-9}{x^2-5x+6} &= \frac{(x-3)(x+3)}{(x-3)(x-2)} \rightarrow \text{Cara Faktor} \\
    &= \frac{x+3}{x-2} \\
    &= \frac{3+3}{3-2} \\
    &= \frac{6}{1} = 6
\end{aligned}
$$

### Soal 1e

$$
\begin{aligned}
    \lim_{x \rightarrow 4} \frac{x-4}{\sqrt{x^2-16}} &= \frac{x-4}{\sqrt{x^2-16}} \times \frac{\sqrt{x^2-16}}{\sqrt{x^2-16}} \rightarrow \text{Cara Rasional Akar} \\
    &= \frac{(x-4)(\sqrt{x^2-16})}{x^2-16} \\
    &= \frac{(x-4)(\sqrt{x^2-16})}{(x-4)(x+4)} \\
    &= \frac{\sqrt{x^2-16}}{x+4} \\
    &= \frac{\sqrt{(4)^2-16}}{4+4} \\
    &= \frac{\sqrt{16-16}}{8} \\
    &= \frac{0}{8} = 0
\end{aligned}
$$

### Soal 1f

$$
\begin{aligned}
    \lim_{x \rightarrow 1} \frac{x-1}{\sqrt{x^2+3}-2} &= \frac{x-1}{\sqrt{x^2+3}-2} \times \frac{\sqrt{x^2+3}+2}{\sqrt{x^2+3}+2} \rightarrow \text{Cara Rasional Akar} \\
    &= \frac{(x-1)(\sqrt{x^2+3}+2)}{(x^2+3)-4} \\
    &= \frac{(x-1)(\sqrt{x^2+3}+2)}{x^2-1} \\
    &= \frac{(x-1)(\sqrt{x^2+3}+2)}{(x-1)(x+1)} \\
    &= \frac{\sqrt{x^2+3}+2}{x+1} \\
    &= \frac{\sqrt{(1)^2+3}+2}{(1)+1} \\
    &= \frac{2+2}{2} \\
    &= \frac{4}{2} = 2
\end{aligned}
$$

### Soal 1g

$$
\begin{aligned}
    \lim_{x \rightarrow \infty} \frac{4x^2-2x+1}{4x^2+2} &= \lim_{x \rightarrow \infty} \frac{4x^2}{4x^2} \quad \text{(Ambil pangkat tertinggi)} \\
    &= \frac{\frac{4x^2}{x^2}}{\frac{4x^2}{x^2}} \\
    &= \frac{4}{4} = 1
\end{aligned}
$$

### Soal 1h

$$
\begin{aligned}
    \lim_{x \rightarrow \infty} \frac{3x^2-2x-1}{3x^2+6x-1} &= \lim_{x \rightarrow \infty} \frac{3x^2}{3x^2} \\
    &= \frac{\frac{3x^2}{x^2}}{\frac{3x^2}{x^2}} \\
    &= \frac{3}{3} = 1
\end{aligned}
$$

### Soal 1i

!!! danger ""

    Untuk soal ini, susah bet dah

## 2. Fungsi Turunan

### Soal 2a

$$
\begin{aligned}
    f(x)  &= \frac{1}{2}x^4 + \frac{2}{3}x^3 - 4x + 1 \\
    f'(x) &= 4 \times \frac{1}{2}x^3 + 3 \times \frac{2}{3}x^2 - 4 \\
    f'(x) &= 2x^3 + 2x^2 - 4
\end{aligned}
$$

### Soal 2b

$$
\begin{aligned}
    f(x)  &= 2x^3 + 3x^2 - x + 2 \\
    f'(x)  &= 6x^2 + 6x - 1
\end{aligned}
$$

### Soal 2c

**Soal:** \( f(x) = (5x+2)(2x^3-7) \)

**Misal:**

$$
\begin{aligned}
    u &= 5x + 2   &&\rightarrow u' = 5 \\
    v &= 2x^3 - 7 &&\rightarrow v' = 6x^2
\end{aligned}
$$

**Maka:**

$$
\begin{aligned}
    f'(x) &= u'v + uv' \\
    &= (5)(2x^3-7) + (5x+2)(6x^2) \\
    &= 10x^3 -35 +30x^3 + 12x^2 \\
    &= 40x^3 + 12x^2 -35
\end{aligned}
$$

### Soal 2d

$$
\begin{aligned}
    f(x)  &= (4x^2-7)^4 \\
    f'(x) &= 4 \times (4x^2-7)^3 \times 8x \\
    f'(x) &= (24x)(4x^2-7)^3
\end{aligned}
$$

## 3. Persamaan Garis Singgung

**Diketahui:**  
- \( y = x^3 + 4x^2 + 5x + 8 \)
- Titik singgung \((1, 18)\)  
**Ditanya:** Persamaan garis singgung?  
**Jawab:**

1. Cari Gradien

    $$
    \begin{aligned}
        m &= f'(x) \\
        &= 3x^2 + 8x + 5 \rightarrow x = 1 \\
        &= 3(1)^2 + 8(1) + 5 \\
        &= 3 + 8 + 5 \\
        &= 16
    \end{aligned}
    $$

2. Cari Persamaan Garis Singgung 

$$
\begin{aligned}
    y - y_1 &= m (x-x_1) \\
    y - 18 &= 16 (x-1) \\
    y - 18 &= 16x - 16 \\
    y &= 16x + 2 \\
\end{aligned}
$$

## 4. Interval Fungsi Turun

### Soal 4a

$$
\begin{aligned}
    f(x)  &= x^3 + 6x^2 - 36x + 20 \\
    f'(x) &= 3x^2 + 12x - 36
\end{aligned}
$$

**Sehingga:**

$$
\begin{aligned}
    f'(x) &< 0 \\
    3x^2 + 12x - 36 &< 0 \\
    3 (x^2 + 4x - 12) &< 0 \\
    (x + 6)(x - 2) &< 0
\end{aligned}
$$

**Maka:** \( -6 < x < 2 \)


### Soal 4b

$$
\begin{aligned}
    f(x)  &= x^3 + 6x^2 - 15x + 3 \\
    f'(x) &= 3x^2 + 12x - 36
\end{aligned}
$$

**Sehingga:**

$$
\begin{aligned}
    f'(x) &< 0 \\
    3x^2 + 12x - 15 &< 0 \\
    3 (x^2 + 4x - 5) &< 0 \\
    (x + 5)(x - 1) &< 0
\end{aligned}
$$

**Maka:** \( -5 < x < 1 \)

## 5. Interval Fungsi Naik

### Soal 5a

$$
\begin{aligned}
    f(x)  &= x^3 + 6x^2 - 36x + 20 \\
    f'(x) &= 3x^2 + 12x - 36
\end{aligned}
$$

**Sehingga:**

$$
\begin{aligned}
    f'(x) &< 0 \\
    3x^2 + 12x - 36 &< 0 \\
    3 (x^2 + 4x - 12) &< 0 \\
    (x + 6)(x - 2) &< 0
\end{aligned}
$$

**Maka:** \( x < 16 \) atau \( x > 2 \)


### Soal 5b

$$
\begin{aligned}
    f(x)  &= x^3 + 6x^2 - 15x + 3 \\
    f'(x) &= 3x^2 + 12x - 36
\end{aligned}
$$

**Sehingga:**

$$
\begin{aligned}
    f'(x) &< 0 \\
    3x^2 + 12x - 15 &< 0 \\
    3 (x^2 + 4x - 5) &< 0 \\
    (x + 5)(x - 1) &< 0
\end{aligned}
$$

**Maka:** \( x < 5 \) atau \( x > 1 \)

## 6. Nilai Minimum

**Diketahui:**  
- \( f(x) = -x^3 + 12x + 3 \)  
- Interval \( -1 \le x \le 3 \)  
**Ditanya:** Nilai Minimum?  
**Jawab:** 

$$
\begin{aligned}
    f'(x) = -3x^2 + 12 &= 0 \\
    -3 (x^2 - 4) &= 0 \\
    (x^2 - 4) &= 0 \\
    (x-2)(x+2) &= 0 \rightarrow x = \{ -2, 2 \}
\end{aligned}
$$

Nilai \(x\) terendah yang berada di interval \( -1 \le x \le 3 \) adalah 2  
**Maka:**

$$
\begin{aligned}
    f(2) &= -x^3 + 12x + 3 \\
    &= -(2)^3 + 12(2) + 3 \\
    &= -8 + 24 + 3 \\
    &= 19
\end{aligned}
$$

## 7. Nilai Maksimum

**Diketahui:** \( f(x) = -2x^2 - 2x + 13 \)   
**Ditanya:** Nilai Maksimum?  
**Jawab:** 

$$
\begin{aligned}
    f'(x) = -4x - 2 &= 0 \\
    -4x &= 2 \\
    x &= \frac{2}{-4} = - \frac{1}{2}
\end{aligned}
$$

**Maka:**

$$
\begin{aligned}
    f(\frac{1}{2}) &= -2x^2 - 2x + 13 \\
    &= -2(\frac{1}{2})^2 - 2(\frac{1}{2}) + 13 \\
    &= \frac{1}{2} - 1 + 13 \\
    &= \frac{11}{2} = 11.5 \\
\end{aligned}
$$

## Soal 8

!!! danger ""

    Sama, ini ga gw kerjain, pusing :(

## 9. Integral Tak Tentu and Subtitusi

### Soal 9a

\( \int (3x^2 + 2x - 2) dx = x^3 + x^2 - 2x + C \)

### Soal 9b

\( \int (2x^3 + 2x^2 - 4) dx = \frac{1}{2}x^4 + \frac{2}{3}x^3 - 4x + C \)