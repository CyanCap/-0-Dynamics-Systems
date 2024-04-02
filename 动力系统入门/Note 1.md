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
F(x,t+s) = F(\varphi^t(x),s),\quad or\quad \varphi^{s+t}(x) = \varphi^s\left(\varphi^t(x)\right).
$$
Check that transformations $\varphi^t$ form a semi-group which maybe has no inverse for noninverible system.
While for a invertible discrete system each $\varphi^t$ has inverse and forms a cyclic group 
$$
\left\{ F^n = (\varphi^1)^n \; | \; n \in \mathbb{Z}\right\}.
$$
And invertible continuous system determines a group $\left\{\varphi^t\right\}_{t\in\mathbb{R}}$.

# Flows and Vector Fields

Very exciting definitions and results (maybe only to me) of the foundations.

