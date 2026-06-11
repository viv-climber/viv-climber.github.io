---
layout: post
title: "A functional equation"
category: algebra
---

## Problem
Find every function $f$ from $\R \gt 0$ to $\R \gt 0$
$\frac{f(x^2) + f(y^2)}{f(w)^2 + f(z)^2} = frac{x^2 + y^2}{w^2 + z^2}$
where $x \times y = w \times z$
...

## Solution
First, we notince three things: 
1) we have a very restraining condition $xy = wz$
2) There are two forms in which $f$ is shown: $f(x^2)$ and $f(x)^2$
3) We have squares everywhere.

Our first motivation should be to see what happens when $P(x, x, x, x)$, which shows us that $f(x^2) = f(x)^2$. When we see this, we should automatically realize that since the function is to $\R \gt 0$ this means $f(1) = 1$.

Now, just to make the equation easier to work with we will put $P(\sqrt(x), \sqrt(y), \sqrt(w), \sqrt(z))$, obtaining
$\frac{f(x) + f(y)}{f(w) + f(z)} = frac{x + y}{w + z}$

We would like to have an expression in which we have only one variable, and we can operate with it to get to the result. Luckily, this can be done with $P(1,x^2, x, x)$, which when expanding tells us that $f(x)$ is either $x$ or $1/x$. Careful here! We have not finished yet. In fact there are infinitely many functions that follow this. When this happens, we probably want to show that if for an $f$, $f(a) = a$ there's no $b$ such that $f(b) = b$. How do we do this? When something like this appears, we can try contradiction, and here it works. Let's assume by sake of contradiction that those $a$ and $b$ exist where neither of them is $1$, then, 
...

## Remarks

...
