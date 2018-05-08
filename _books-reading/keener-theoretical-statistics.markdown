---
layout: post
title:  "Theoretical Statistics: Topics for a Core Course."
category: book-reviews
tags: statistics
published: true
permalink: /:categories/:title
description: This is a book on statistics.
---

You can get a copy of the book at [libgen].

*What is in this book?* ??.

## **Chapter 01: Probability and Measure**

# **Measures:** 

A measure $$\mu$$ on a set $$\chi$$ assigns a non-negative value $$\mu(A)$$ to many (but not necessarily all) subsets of $$\chi$$, e.g., counting measure and Lebesgue measure. The theory of measure is fundamentally linked to basic questions about integration.

It is often impossible to assign measures to all subsets of $$\chi$$. Instead, the domain of a measure $$\mu$$ will be a sigma field.

**Definition:** A collection $${\cal A}$$ of subsets of a set $$\chi$$ is a $$\sigma$$-field (or a $$\sigma$$-algebra) if: (a) $$\chi, \Phi \in \mathcal{A}$$, (b) If $$A \in \mathcal{A}$$, then $$A^c = \chi - A \in \mathcal{A}$$, (c) If $$A_1, A_2, \ldots \in \mathcal{A}$$, then $$\bigcup_{i=1}^{\infty} A_i \in \mathcal{A}$$.

**Definition:** A function $$\mu$$ on a $$\sigma$$-field $$\mathcal{A}$$ of $$\chi$$ is a measure if: (a) For every $$A \in \mathcal{A}$$, $$ 0 \leq \mu(A) \leq \infty$$; that is, $$\mu: \mathcal{A} \to [0,\infty]$$. (b) If $$A_1, A_2, \ldots $$ are pairwise disjoint elements of $$\mathcal{A}$$, then $$\mu \left(\bigcup_{i=1}^{\infty} A_i \right) = \sum_{i=1}^{\infty} \mu(A_i)$$.

(**Why ??**) One useful consequence of the second part is that if $$B_1 \subset B_2 \ldots $$ are measurable sets with union $$B = \cup B_i$$ called the limit of the sequence, then $$\mu(B) = \lim_{n \to \infty} \mu(B_n)$$. This can be viewed as a continuity property of the measure.

**Notation** If $$\mathcal{A}$$ is a $$\sigma$$-field of $$\chi$$, the pair $$(\chi, \mathcal{A})$$ is called a *measurable space* and if $$\mu$$ is a measure on $$\mathcal{A}$$, the triple $$(\chi,\mathcal{A},\mu)$$ is called a *measure space*.

A measure $$\mu$$ is *finite* if $$\mu(\chi)<\infty$$ and $$\sigma$$-finite if there exist sets $$A_1, A_2, \ldots$$ in $$\mathcal{A}$$ with $$\mu(A_i) < \infty $$ and $$\big

## **Chapter 02: Exponential Families**

## **Chapter 03: Risk, Sufficiency, Completeness and Ancillarity**

## **Chapter 04: Unbiased Estimation**

## **Chapter 05: Curved Exponential Families**

## **Chapter 06: Conditional Distributions**

## **Chapter 07: Bayesian Estimation**

## **Chapter 08: Large-Sample Theory**

## **Chapter 09: Estimating Equations and Maximum Likelihood**

## **Chapter 10: Equivariant Estimation**

## **Chapter 11: Empirical Bayes and Shrinkage Estimators**

## **Chapter 12: Hypothesis Testing**

## **Chapter 13: Optimal Tests in Higher Dimensions**

## **Chapter 14: General Linear Model**

## **Chapter 15: Bayesian Inference: Models and Computation**

## **Chapter 16: Asymptotic Optimality**

## **Chapter 17: Large-Sample Theory for Likelihood Ratio Tests**

## **Chapter 18: Nonparametric Regression**

## **Chapter 19: Bootstrap Methods**

## **Chapter 20: Sequential Methods**

## **Appendices:**

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
