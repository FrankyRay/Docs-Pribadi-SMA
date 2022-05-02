---
title: [MTK] Polinomial
---

## Polinomial

Polinomial adalah bentuk aljabar yang terdiri dari beberapa suku dan memuat satu variable berpangkat positif

Bentuk umum polinomial berderajat \(n\) dengan variabel \(x\) dapat ditulis seperti ini:

$$
a_n x^n + a_{n-1} x^{n-1} + \dots + a_2 x^2 + a_1 x + a_0
$$

Keterangan:  
- \(n\) = Bilangan Bulat Positif  
- \(a_n\), \(\dots\), \(a_1\) = Koefisien  
- \(a_0\) = Konstanta

??? summary "Contoh Polinomial"

    === "Polinomial"

        - \(3x^5 + \frac {2}{3} x^2 - 6x + 7\)
        - \(2x^3 + 6x^2 - 2x + 1\)
        - \(\frac {1}{3} x^6 - 2x^3 \tan \frac {\pi}{4} + \frac {x}{2} + 7\)

    === "Bukan Polinomial"
        - \(7x^3 + 6x^2 + \frac {3}{x} + x^{-2}\)
        
            Bukan polinomial karena adanya {==\(x\) berpangkat negatif==}  
            \(\frac {3}{x} = 3x^{-1}\) 

        - \(5x^7 + 3x^2 + 7 \sqrt{x}\)

            Bukan polinomial karena adanya {==\(x\) tidak berpangkat bulat, melainkan pecahan==}  
            \(7 \sqrt{x} = 7 x^{\frac {1}{2}}\)

        - \(3x^5 - x^2 + 2 \tan x + 1\)

            Bukan polinomial karena {==\(x\) berada dalam trigonometri (dalam \(\tan\))==}  
            \(2 \tan x\)

## Operasi Polinomial

Contoh Soal:  
Diketahui \(p(x) = 5x^4 + 3x^3 - 5x^2 + 6\) dan \(q(x) = 4x^3 - 2x^2\)

Tentukanlah:

1. \(p(x) + q(x)\)
2. \(p(x) - q(x)\)
3. \(p(x) \times q(x)\)

Jawab:

1. Penjumlahan

    $$
    \begin{aligned} 
    p(x) + q(x) &= 5x^4 + 3x^3 - 5x^2 + 6 + 4x^3 - 2x^2 \\
    &= 5x^4 + 7x^3 - 7x^2 + 6 \\
    \end{aligned}
    $$

2. Pengurangan

    $$
    \begin{aligned}
    p(x) + q(x) &= 5x^4 + 3x^3 - 5x^2 + 6 - (4x^3 - 2x^2) \\
    &= 5x^4 + 3x^3 - 5x^2 + 6 - 4x^3 + 2x^2 \\
    &= 5x^4 - x^3 - 3x^2 + 6
    \end{aligned}
    $$

3. Perkalian

    $$
    \begin{aligned}
    p(x) \times q(x) &= \left(5x^4 + 3x^3 - 5x^2 + 6\right) \cdot \left(4x^3 - 2x^2\right)\\
    &= 20x^7 - 10x^6 + 12x^6 - 6x^5 - 20x^5 + 10x^4 + 24x^3 - 12x^2\\
    &= 20x^7 + 2x^6 - 26x^5 + 10x^4 + 24x^3 - 12x^2
    \end{aligned}
    $$


