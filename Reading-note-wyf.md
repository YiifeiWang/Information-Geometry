$$
\newcommand{\dm}{displaymath}
\newcommand{\p}{\partial}
\newcommand{\lp}{\left(}
\newcommand{\rp}{\right)}
\newcommand{\lb}{\left[}
\newcommand{\rb}{\right]}
\newcommand{\la}{\left\langle}
\newcommand{\ra}{\right\rangle}

\newcommand{\pp}[1]{\left(#1\right)}
\newcommand{\bb}[1]{\left[#1\right]}
\newcommand{\lra}[1]{\left\langle #1\right\rangle}
\newcommand{\lr}[1]{\left #1\right}
\newcommand{\norm}[1]{\left\| #1\right\|}
\newcommand{\lbb}[1]{\left\{\begin{aligned} #1\end{aligned}\right.}
\newcommand{\ldr}[1]{\left. #1\right|}
\newcommand{\bmbm}[1]{\begin{bmatrix} #1 \end{bmatrix}}
\newcommand{\bra}[1]{\left\langle #1\right|}
\newcommand{\ket}[1]{\left| #1\right\rangle}

\newcommand{\ac}{\operatorname{ac}}
\newcommand{\diag}{\operatorname{diag}}
\newcommand{\dist}{\operatorname{dis}}
\newcommand{\grad}{\operatorname{grad}}
\newcommand{\Dens}{\operatorname{Dens}}
\newcommand{\Diff}{\operatorname{Diff}}
\newcommand{\Exp}{\operatorname{Exp}}
\newcommand{\gl}{\operatorname{gl}}
\newcommand{\GL}{\operatorname{GL}}
\newcommand{\Hess}{\operatorname{Hess}}
\newcommand{\Hor}{\operatorname{Hor}}
\newcommand{\Id}{\operatorname{Id}}
\newcommand{\KL}{\operatorname{KL}}
\newcommand{\MMD}{\operatorname{MMD}}
\newcommand{\Prox}{\operatorname{Prox}}
\newcommand{\Proj}{\operatorname{Proj}}
\newcommand{\prox}{\operatorname{prox}}
\newcommand{\tr}{\operatorname{tr}}
\newcommand{\tsign}{\operatorname{sign}}
\newcommand{\Var}{\operatorname{Var}}
\newcommand{\Ver}{\operatorname{Ver}}
\newcommand{\vvec}{\operatorname{vec}}
$$





# Chapter 1

Coordinate system: P4

__Example__ Bregman divergence: P13 for a (strictly) convex $f(x)$, we define
$$
B(x,y) = f(x)-f(y)+\lra{\nabla f(y),x-y}
$$
It is easy to observe that
$$
B(y+dy,y)=(dy)^T\nabla^2f(y) dy+O(\|dy\|^3).
$$
The notation on the book is kind of strange because we usually assume that the second term in the divergence is fixed. Stil,l we can write that
$$
B(x,x+dx) = (dx)^T\nabla^2 f(x+dx)dx+O(\|dx\|^3)=(dx)^T\nabla^2 f(x)dx+O(\|dx\|^3)
$$


Example 1.3 is interesting.

Theorem 1.1 is interesting. 



# Chapter 7

Cramer-Rao theory



Questions:

1. P167 What is xxx-coordinate system?