# Exponential Form

The following parts remain the propoties of complex number.
These do not make the complex number abstract going into algebra fields. 
But still very important for further discussion.

Let $r$ and $\theta$ be polar coordinates of point $(x,y)$, which corresponds to a nonzero complex number $z = x+iy$. 
Then $z$ can be written as 
$$
z=r(\cos\theta + i \sin\theta).
$$
If $z=0$ then there is no $\theta$ well-defined. Actually it only needs $r=0$, such that $\theta$ can be any values which is not allowed.

$\theta$ is called an *argument* of $z$, and the set of all such values is denoted by arg$z$. The *principal value* Arg$z$ of arg$z$ is that unique value $\Theta$ such that $-\pi<\Theta\leq\pi$.
$$
{\rm arg} z = {\rm Arg} z+2n\pi\qquad (n=0,\pm 1,\pm 2,\cdots).
$$


$e^{i\theta}$ or exp($i\theta$) is defined by *Euler's formula*:
$$
e^{i\theta} = \cos \theta +i\sin\theta.
$$
So the *exponential form*:
$$
z=r(\cos\theta + i \sin\theta) = r e^{i\theta}.
$$

**Remark:** exponential form does represent the "vector" of complex number. It can appear to everywhere to build a polar coordinates.

# Products and Powers in Exponential Form

Easily, 
$$
z_1 z_2 = (r_1 r_2)e^{i(\theta_1 +\theta_2)},\\
\frac{z_1}{z_2} = \frac{r_1}{r_2}e^{i(\theta_1 - \theta_2)}.
$$

And the inverse of any nonzero complex number $z$ is 
$$
z^{-1} = \frac{1}{z} = \frac{1 e^{i0}}{re^{i\theta}} = \frac{1}{r}e^{i(0-\theta)} = \frac{1}{r}e^{-i\theta}.
$$

Then the powers in exponential form is 
$$
z^n = r^n e^{in\theta},\quad n\geq 0,
$$
can be proved using mathematical induction.
If $n = -1,-2,\cdots$,
$$
\begin{align*}
z^n &={(z^{-1})}^m\quad {\rm where}\quad m = -n = 1,2,\cdots\\
&=\left[\frac{1}{r}e^{i(-\theta)}\right]^m = \left(\frac{1}{r}\right)^m e^{im(-\theta)}=\left(\frac{1}{r}\right)^{-n}e^{i(-n)(-\theta)} = r^n e^{in\theta}.
\end{align*}
$$
So expression holds for all integral powers.