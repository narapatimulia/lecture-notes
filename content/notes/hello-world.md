---
title: "hello-world"
date: 2023-09-18T10:43:00+07:00
authors: ['Mulia Narapati']
tags: ['xx1000']
draft: false
math: true
url: "0048"
---
{{< toc >}}

## link
+[Github](https://github.com)
+[Google](https://google.com)
+[pahe](https://pahe.li)
+[Instagram](https://instagram.com)


## image
![](https://staticg.sportskeeda.com/editor/2022/06/b4bf5-16556383242694-1920.jpg)


## yt
{{< youtube 745zY1Dvjag >}}


## Animation with SVG
{{< html >}}
<svg width="200" height="200" xmlns="http://www.w3.org/2000/svg">
  <!-- Rectangle with animation -->
  <rect x="10" y="10" width="50" height="50" fill="blue">
    <animate attributeName="width" from="50" to="150" dur="2s" begin="0s" repeatCount="indefinite" />
    <animate attributeName="height" from="50" to="150" dur="2s" begin="0s" repeatCount="indefinite" />
    <animate attributeName="fill" values="blue;red;green;blue" dur="4s" begin="0s" repeatCount="indefinite" />
  </rect>
</svg>
{{< /html >}}


## Complex SVG with Styled Rect
{{< html >}}
<svg width="400" height="300" xmlns="http://www.w3.org/2000/svg">
  <!-- Rectangle with gradients -->
  <defs>
    <linearGradient id="grad1" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:rgb(255,0,0);stop-opacity:1" />
      <stop offset="100%" style="stop-color:rgb(0,0,255);stop-opacity:1" />
    </linearGradient>
  </defs>

  <rect x="20" y="20" width="200" height="100" fill="url(#grad1)" stroke="green" stroke-width="3" />

  <!-- Text element -->
  <text x="30" y="160" font-family="Arial" font-size="24" fill="black">Complex SVG</text>

  <!-- Circle with animation -->
  <circle cx="250" cy="150" r="20" fill="orange">
    <animate attributeName="r" from="20" to="50" dur="2s" begin="0s" repeatCount="indefinite" />
  </circle>
</svg>
{{< /html >}}



## Jadwal
No | Tanggal | Renggiat | Ingfo
:-: | :- | -: | :-:
1 | 22 Jun | Garjas | -
2 | 15 Jul | U Te Es | $\frac{x}{y}$
3 | 17 Aug | Praktikum di Sosmed | [Instagram](https://instagram.com)
4 | 3 Sep  | U A S | -
5 | 24 Oct | Remedial | **nothing.**


## list
+ Nama Kota
  - Semarang
  - Bogor
  - Timika 
+ NIT
+ Hobi


## equation
$$
\mathbf{M} = 
\left[
\begin{matrix}
1 & 2 & 3 & 4 & 5 \newLine
6 & 7 & 8 & 9 & 10 \newLine
1 & 2 & y^2 & z & x\newLine
\end{matrix}
\right
]
$$

$$
x_{1,2} = \frac{-b \pm \sqrt{b^2 -4ac}}{2a}
$$

$$\tag{23}
y = ax^2 + bx +c
$$