# Reference

This notes are based on the book [Complex variables and applications](https://people.math.sc.edu/girardi/m7034/book/ChurchillBrown8ed.pdf) written by Brown and Churchill. More information can be found by clicking the url.

# Complex Numbers

A complex number is a point expressed as a pair $z=(x,y)$ of real numbers interpreted in the complex plane. $(x,y)$ is the rectangular coordinates with real numbers $x$ are points on the real line.

Denote $x$, $y$ as *real and imaginary parts* of $z$:

$$
x = {\rm Re}\;z,\quad y = {\rm Im}\;z.
$$

**Remark:** Easily seeing that real number $\mathbb{R}$ is a subset of complex number $\mathbb{C}$.
Form $(0,y)$ are pure imaginary numbers when $y\neq0$.

## Operations

Two complex numbers $z_1=(x_1,y_1)$, $z_2=(x_2,y_2)$ are equal *iff* $x_1=x_2,\; y_1=y_2$.

Sum $z_1+z_2$ and product $z_1z_2$ defined by:

$$
\begin{align*}
(x_1,y_1) +(x_2,y_2) &=(x_1+x_2,y_1+y_2),\\
(x_1,y_1)(x_2,y_2)&=(x_1x_2-y_1y_2,y_1x_2+x_1y_2).
\end{align*}
$$

Seeing that complex number is a extension of the real number in some degree.
$z=(x,y)$ can be written by $z = (x,0)+(0,y)$.

### Definition of $i$

Define the imaginary indentity (I think that maybe?) to be pure imaginary number $(0,1)$.
Naturally add to expression

$$
z= x+iy.
$$

So $i^2 = -1$.

## Algebraic Properties

Complex numbers have various properties which are the same as for real numbers.
**The commutative laws**

$$
z_1+z_2 = z_2+z_1,\quad z_1z_2=z_2z_1.
$$

**The associative laws**

$$
(z_1+z_2)+z_3=z_1+(z_2+z_3),\quad (z_1z_2)z_3=z_1(z_2z_3).
$$

**The distributive law**

$$
(z_1+z_2)z=z_1z+z_2z.
$$

These all are easy to check.

We have the **additive identity** $0=(0,0)$ and the **multiplicative identity** $1=(1,0)$.
Especially, there exists an **additive inverse** $-z$.
While the multiplicative inverse is not so obvious, and not defined when $z=0$.

**Remark:** if $z_1z_2 = 0$, so at least one of them is zero.
And subtraction (减法) and division (除法) are defined in terms of additive and multiplicative inverses.
Especially,

$$
\frac{z_1}{z_2} = \frac{(x_1+iy_1)(x_2-iy_2)}{(x_2+iy_2)(x_2-iy_2)}.
$$
