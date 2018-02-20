---
layout: post
title:  "An Introduction to Chaotic Dynamical Systems"
category: book-reviews
tags: physics
published: true
permalink: /:categories/:title
description: This is a book on dynamical systems by Robert L. Devaney.
---

You can get a copy of the book [here](http://zangeneh.iut.ac.ir/sites/zangeneh.iut.ac.ir/files//files_course/robert_l.devaneyan_introductiponto_chaotic_dynamical_system.pdf) or search for a better copy at [libgen].

*What is in this book?* The author believes that most of the important ideas and techniques in nonlinear dynamics can be introduced in the setting of the real line or the circle. So, in the first chapter, the focus has been to introduce ideas like structural stability, topological conjugacy, the shift map and homoclinic points in the context of one-dimensional dynamical systems. The second chapter is a study of higher-dimensional dynamical systems while the third chapter describes some works on the complex analytic maps.

## **Chapter one: One-Dimensional dynamics**

# **Preliminaries from Calculus:** 

**Definition:** Function $$f$$ is of class $$C^r$$ on $$I$$ if $$f^{(r)}(x)$$ exists and is continuous at all $$x \in I$$.

**Definition:** Function $$f: X \to Y$$ is a *homeomorphism* if $$f$$ is a bijection (one-to-one and onto) and both $$f$$ and $$f^{-1}$$ are continuous.

**Definition:** Function $$f(x)$$ is a $$C^r$$-*diffeomorphism* if both $$f(x)$$ and $$f^{-1}(x)$$ are $$C^r$$-homeomorphisms.

**Mean Value Theorem** If $$f:[a,b]\to \mathbb{R}$$ is $$C^1$$, then there exists $$c \in [a,b]$$ such that $$f(b)-f(a) = f'(c)(b-a)$$.

**Intermediate Value Theorem** If $$f:[a,b]\to \mathbb{R}$$ is continuous and $$f(a) = u$$ and $$f(b) = v$$, then for any $$z \in [u,v]$$, there $$c\in [a,b]$$ such that $$f(c) = z$$.

**Implicit Function Theorem** Suppose $$G: \mathbb{R}^2 \to \mathbb{R}$$ is a $$C^1$$ function, i.e., both the partial derivatives exist and are continuous. Suppose further that $$G(x_0,y_0) = 0$$ and $$\frac{\partial G}{\partial y}(x_0,y_0) \ne 0$$. Then there exist open intervals $$I$$ about $$x_0$$ and $$J$$ about $$y_0$$ and a $$C^1$$ function $$p$$ satisfying $$p(x_0) = y_0$$ and $$G(x, p(x)) = 0$$ for all $$x \in I$$.

**A special case of Brouwer Fixed Point Theorem** Let $$I = [a,b]$$ be and interval and let $$f:I \to I$$ be continuous. Then $$f$$ has at least one fixed point in $$I$$.

**A special case of the Contraction Mapping Theorem** Let $$f:I \to I$$ and assume that $$\|f'(x)\| < 1$$ for all $$x \in I$$. Then there exists a unique fixed point for $$f$$ in $$I$$. Moreover, $$\|f(x)-f(y)\| < \|x-y\|$$.

**Definition** A subset $$U$$ of $$S$$ is dense in $$S$$ if the closure of $$U$$ (denoted $$\bar U$$) is equal to $$S$$.


[jekyll-docs]: https://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/
[cmi]: https://www.cmi.ac.in
[google]: https://www.google.com
[gmail]: https://www.gmail.com
[govind]: https://www.cmi.ac.in/~govind
[libgen]: http://libgen.io

<script type="text/javascript" async
  src="https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.2/MathJax.js?config=TeX-MML-AM_CHTML">
</script>
