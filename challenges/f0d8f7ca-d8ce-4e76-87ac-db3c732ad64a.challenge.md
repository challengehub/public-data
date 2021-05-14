---
extra_resources: {}
topics: []
editor_id: github.NanoScaleDesign
modified: 2021-05-14T06:48:08.801141321Z
affiliated_institute:
  url: https://www.kyushu-u.ac.jp
  en_name: Kyushu University
  name: 九州大学
version: '1.0'
title_id: basic-limits-of-complex-functions-and-their-properties-limz-ei-pi4-of-z1z
language: en
id: f0d8f7ca-d8ce-4e76-87ac-db3c732ad64a
translations: {}
title: Basic limits of complex functions and their properties - lim(z->e^i pi/4) of
  (z+(1/z))

---

## Comments

Theorum 2.2 (page 117) in the textbook listed below states:

Suppose that `$f$` and `$g$` are complex functions. If `$\lim _{z \rightarrow z_{0}} f(z)=L$` and `$\lim _{z \rightarrow z_{0}} g(z)=M,$` then
- `$\lim _{z \rightarrow z_{0}} c f(z)=c L$`, where `$c$` is a complex constant
- `$\lim _{z \rightarrow z_{0}}(f(z) \pm g(z))=L \pm M$`
- `$\lim _{z \rightarrow z_{0}} f(z) \cdot g(z)=L \cdot M,$` and
- `$\lim _{z \rightarrow z_{0}} \frac{f(z)}{g(z)}=\frac{L}{M},$` provided `$M \neq 0$`

While the basic limits on page 117 state:

- `$\lim _{z \rightarrow z_{0}} c=c$`, where `$c$` is a complex constant
- `$\lim _{z \rightarrow z_{0}} z=z_{0}$`

These basic limits and properties can be used to quickly ascertain limits of a function. For example,

`$$\lim _{z \rightarrow i} z^{2}=\lim _{z \rightarrow i} z \cdot z=\left(\lim _{z \rightarrow i} z\right) \cdot\left(\lim _{z \rightarrow i} z\right)=i \cdot i=-1$$`

Please see the further, more detailed examples in the book.


## Challenge
Compute the given complex limit using the above theorum and basic limits:

`$\displaystyle{\lim_{z \to e^{i\frac\pi4}}}    \left( z + \frac1z\right)$`



## Resources
- [YouTube lecture (W2L2)](https://www.youtube.com/watch?v=pNwYdyIfTt4&list=PLi7yHjesblV0sSfZzWdSUXGO683n_nJdQ&index=7)
- https://www.youtube.com/watch?v=HT5aZUqO6Kg
- Chapter 2 of *A first course in complex analysis with applications* by D. Zill and P. Shanahan


## Solution Form
Your answer will be in the form `$\alpha+i \beta$`.
For a simple check of your answer, calculate and enter `$$\alpha+10\beta$$`
and compare your solution with your partner in class.
