---
title: "Camera Models"
date: 2022-12-11 02:03:00 +0800
categories: [Machine Vision]
tags: []
header-includes:
   - \usepackage{amsmath}
---

## Introduction
We can represent a world object as a combination of the multiple world points which are connected to each other. Also, image of this object can be viewed as a combination of the image points. A camera is nothing more than a projecting device which project world points into image points. Therfore, image capturing process can be defined mathematically and relation between world and image points can be formulated. This is done by defining image and world points and modelling a camera mathematically.

## World and Image Points

A point is represented with a 3 dimensional vector in world and 2 dimensional vector in image according to Euclidean geometry.

$$p_{world} = \begin{bmatrix}
x \\
y \\
z \\

\end{bmatrix}$$

$$
p_{image} = \begin{bmatrix}
m \\
n \\

\end{bmatrix}$$


These definitions are done according to Euclidian geometry, but is Euclidiean geometry is enough for modeling this whole image capturing process and camera modelling? 

No, it is not.

<!-- ![Railroad](/assets/railroad.png "railroad") -->

<!-- <p align="center" width="100%">
    <img width="33%" src=/assets/railroad.png>
</p> -->
{% include elements/figure.html image="/assets/railroad.png" caption="railroad" %}

<!-- $$
\begin{align*}
  \left( x \right. 
        \\
        \left. y \right. 
        \\
        \left. z \right )
\end{align*}
$$

$$
\displaystyle
\left( \sum_{k=1}^n a_k b_k \right)^2
\leq
\left( \sum_{k=1}^n a_k^2 \right)
\left( \sum_{k=1}^n b_k^2 \right)
$$ -->