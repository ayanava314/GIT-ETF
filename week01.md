---
title: "Week 1: Preliminaries and Motivation"
layout: default
---

# Week 1: Preliminaries and Motivation

**Reading:**  
- I. Dolgachev: Lectures on Invariant Theory : Chapter 1

**Topics:**  
- What is ETF?


## Motivation

Let $$V$$ be a $$K$$-vector space where $$K$$ is algebraically closed.

### Frame
Let
$$
\mathrm{Fr}_n(V)
:= \left\{ (v_i)_{i=1}^{n} \in V^n \;\middle|\;
v_i \neq \lambda v_j \text{ for } i \neq j,\;
\operatorname{span}\{v_i\} = V
\right\}
$$
be called a **frame**.

---

We define actions of different groups on $$\mathrm{Fr}_n(V) \times \mathrm{Fr}_n(V^*)$$

### Group actions

- **Left action of $$\mathrm{GL}(V)$$:**
$$
M\big((v_i),(\phi_i)\big)
=
\big((Mv_i),\; (v \mapsto \phi_i(M^{-1}v))\big)
$$

- **Right action of $$(K^\times)^n \rtimes S_n$$**  
  (scaling and permuting frames):

  - Scaling:
  $$
  ((v_i),(\phi_i))\lambda_i
  =
  \big((\lambda_i v_i),\; (v \mapsto \phi_i(\lambda_i^{-1}v))\big)
  $$

  - Permutation:
  $$
  ((v_i),(\phi_i))\sigma
  =
  \big((v_{\sigma(i)}),(\phi_{\sigma(i)})\big)
  $$

---

### Definition ETB
Define
$$
\mathrm{ETB}_n(V)
\subset
\mathrm{GL}(V)\backslash
\big(\mathrm{Fr}_n(V)\times \mathrm{Fr}_n(V^*)\big)
/\big((K^\times)^n \rtimes S_n\big)
$$
to be the subspace consisting of points satisfying:

1. $$\phi_i(v_i) = 1 $$ (similar to unit norm)
2. $$\phi_i(v_j)\phi_j(v_i) = \frac{n-d}{d(n-1)}$$ for $$i \neq j $$
3. $$v_j = \frac{d}{n} \sum_\limits{i=1}^{n} \phi_i(v_j)\, v_i $$ (tightness)

---

### **Big Questions**

- What is $$\mathrm{ETB}_n(V)$$? Is it a variety?
- When is $$\dim \mathrm{ETB}_n(V) = 0$$?  
  In that case, what is the number of points
  $$ \#\mathrm{ETB}_n(V)$$?

---

### *Special Case*

Let $$K = \mathbb{C}$$ and
$$
\phi_i(v) = \langle v_i, v \rangle .
$$
Then $$(v_i)$$ is called an **ETF** (*Equiangular Tight Frame*).

The defining conditions become:

1. **Unit norm**
   $$
   \langle v_i, v_i \rangle = 1
   $$

2. **Equiangular**
   $$
   \big|\langle v_i, v_j \rangle\big|^2
   = \frac{n-d}{d(n-1)}
   $$

3. **Tight**
   $$
   v = \frac{d}{n} \sum_{i=1}^{n} \langle v_i, v \rangle v_i
   $$

---

## Comment Thread

This page corresponds to the GitHub Discussion or Issue for Week 1.
