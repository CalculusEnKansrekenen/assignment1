---
title: Assignment 1
author: Hendrik Werner s4549775
date: \today
fontsize: 12pt
geometry: margin=5em
---

# 6
## a
$\begin{aligned}
	f(x) &= 0\\
	x - x^3 &= 0\\
	x(1 - x^2) &= 0\\
	1 - x^2 &= 0 & x_0 &= 0\\
	1 &= x^2\\
	x_{1,2} &= \sqrt{x}\\
	x_1 &= 1 & x_2 &= -1\\
\end{aligned}$

$f(x) = 0$ for $x \in \{-1, 0, 1\}$.

## b
We can use the zero points (aka roots) we found in 6a. They tell us at which points we need to sample $f(x)$:

$\begin{aligned}
	f(-2) &= -2 - (-2)^3 &&= -2 + 8\\
	&&&= 6 &>0\\
	f(-\frac{1}{2}) &= -\frac{1}{2} - (-\frac{1}{2})^3 &&= -\frac{1}{2} + \frac{1}{8} &<0\\
	f(\frac{1}{2}) &= \frac{1}{2} - (\frac{1}{2})^3 &&= \frac{1}{2} - \frac{1}{8} &>0\\
	f(2) &= 2 - 2^3 &&= 2 - 8\\
	&&&= -6 &<0
\end{aligned}$

From this we can see that $f(x) > 0$, for $x \in (-\infty, -1) \cup (0, 1)$.

# 7
First we determine the values for $y$ just outside of the interval:

$\begin{aligned}
	x &= 0: & y &= a + (b - a) * 0\\
	&&&= a\\
	x &= 1: & y &= a + (b - a) * 1\\
	&&&= b\\
\end{aligned}$

For $a$ and $b$, we can distinguish 2 cases:

* $a > b$: $y \in (b, a)$
* $b > a$: $y \in (a, b)$

# 8
A function is called even if $f(x) = f(-x)$, and odd if $f(-x) = -f(x)$.

## a
* even?

  $\begin{aligned}
  	f(x) &\stackrel{?}{=} f(-x)\\
  	3x - x^3 &\stackrel{?}{=} -3x - (-x)^3\\
  	&\neq -3x + x^3\\
  \end{aligned}$
* odd?

  $\begin{aligned}
  	f(-x) &\stackrel{?}{=} -f(x)\\
  	-3x - (-x)^3 &\stackrel{?}{=} -(3x - x^3)\\
  	-3x + x^3 &= -3x + x^3\\
  \end{aligned}$

$f(x) = 3x - x^3$ is odd.

## b
* even?

  $\begin{aligned}
  	f(x) &\stackrel{?}{=} f(-x)\\
  	\sqrt[3]{(1 - x)^2} + \sqrt[3]{(1 + x)^2} &\stackrel{?}{=} \sqrt[3]{(1 - (-x))^2} + \sqrt[3]{(1 + (-x))^2}\\
  	\sqrt[3]{(1 - x)^2} + \sqrt[3]{(1 + x)^2} &= \sqrt[3]{(1 + x)^2} + \sqrt[3]{(1 -x)^2}\\
  \end{aligned}$

$f(x) = \sqrt[3]{(1 - x)^2} + \sqrt[3]{(1 + x)^2}$ is even.

# 9
# 10
# 11
