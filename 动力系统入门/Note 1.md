# Reference

This notes are based on the book Introduction to the Modern Theory of Dynamical Systems written by Anatole Katok.

# A Very Brief Introduction

Some principles defined in the book are the following:

1. **A phase space $X$** stores the possible states of the system as "points" or elements.
2. **Time $T$** to be continuous or discrete. It extend to future (noninvertible) or both past and future (invertible). And time can easily map to real numbers or integer numbers.
3. **The time-evolution law**. A rule that allows us to determine the state at each moment of time $t$ from its states at all previous times.

In this note, time-evolution law will not change along the time. So any state will be determined by the initial position and the length of the evolution i.e. state will be represented by $F(x,t)$.

Fixing $t$, transformation

$$
\varphi^t:x\mapsto F(x,t)
$$

maps to phase space itself.
We have

$$
F(x,t+s) = F(\varphi^t(x),s),\quad or\quad \varphi^{s+t}(x) = \varphi^s\left(\varphi^t(x) \right).
$$

Check that transformations $\varphi^t$ form a semi-group which maybe has no inverse for noninverible system.
While for a invertible discrete system each $\varphi^t$ has inverse and forms a cyclic group

$$
\{ F^n = (\varphi^1)^n \; | \; n \in \mathbb{Z}\}.
$$

And invertible continuous system determines a group $\{\varphi^t\}_{t\in\mathbb{R}}$.

# Flows and Vector Fields

Very exciting definitions and results (maybe only to me) of the foundations.

In some degrees, if time is discrete the dynamical systme will be more easier to be decribes.
This may be simply because we count time (1s, 2s,$\cdots$) and it is intuitive.
Now assume a smooth m-dimensional manifold $M$. We fix a initial state $x\in M$ and vary $t$ then get a parameterized smooth curve on $M$.

But here comes a problem, we cannot consider global properties of a manifold at once.
So we should work in different local charts (coordinate) $(s_i^{t_1+t_2})\in U$ for time $t_1,t_2$ to be small enough.
$U$ is the coordinate neighborhood.

Take every tangent vector at point $x$.
Then every $x$ maps to this tangent vector could form a vector field or tangent bundle.
m real-valued functions $(v_i)$ are determined as a map from $U$ to $\mathbb{R}$.
Every vector field locally is represented as

$$
\sum^m_{i=1}v_i(s_1,\dots,s_n)\frac{\partial}{\partial s_i}.
$$

Then the evolution is obtained by solving ODE:

$$
\frac{d s_i}{d t} = v_i(s_1,\dots,s_m),
$$

with initial conditions $s_i(0)=s_i^0$ for the initial point $x$.

That promise that we can work for any transformation $\varphi^t$.
If the solutions exist for the previous equation for all time $t$, then we call the vector field is complete.

We define a flow as a one-parameter group of diffeomorphisms of $M$ to be $\{\varphi^t\}$.
