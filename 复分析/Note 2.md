# Vectors and Moduli

It is natural to connect a complex number $z=x+yi$ with a point $(x,y)$ or a vector from origin to the point $(x,y)$.
Easily see that addition in $\mathbb{C}$ can be represented as vector addition.

$$
z_1+z_2=(x_1+x_2)+i(y_1+y_2)
$$

corresponds to the point or vector $(x_1+x_2,y_1+y_2)$.

![1](image/Note2/1712545253304.png =x150)


Let's define the *modulus*.

Modulus or absolute value of $z=x+iy$ is the nonnegative real number

$$
|z| = \sqrt{x^2+y^2}.
$$

This represents the distance between origin to the point $(x,y)$ geometrically.

**One interesting example:**
equation $|z-1+3i|=2$ is a circle whose center is $z_0=(1,-3)$ with radius $r = 2$.

# Complex Conjugates

Conjugates for $z=x+iy$ is defined as

$$
\bar z=x-iy
$$

Check that $\bar{\bar z} = z$ and $|\bar z|=|z|$.

Some properties:

1. $\overline{z_1+z_2} = \overline{z_1} +\overline{z_2}$,
2. $\overline{z_1-z_2} = \overline{z_1} -\overline{z_2}$,
3. $\overline{z_1z_2} = \overline{z_1}\overline{z_2}$,
4. $\overline{\frac{z_1}{z_2}} = \frac{\overline{z_1}}{\overline{z_2}},\quad z_2\neq 0$.

And some further properties:

$$
{\rm Re}\;z = \frac{z+\overline{z}}{2}\quad {\rm and} \quad {\rm Im}\;z = \frac{z-\overline{z}}{2}.
$$

$$
z\overline{z} = |z|^2.
$$
