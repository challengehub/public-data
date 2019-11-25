---
affiliated_institute:
  en_name: Kyushu University
  name: "\u4E5D\u5DDE\u5927\u5B66"
  url: https://www.kyushu-u.ac.jp
editor_id: github.cbal-brezina
extra_resources: {}
id: fc0a8c58-bc75-42a6-9c5d-cfefe7ff32ac
language: en
modified: '2019-11-26T07:19:29.412017Z'
title: LAF - Vector spaces
title_id: laf-vector-spaces
topics: []
translations: {}
version: '1.0'
---

## Intro

After 23 classes on linear algebra, can you answer the question: What is **vector**? If not, do not despair. In this challenge we will look for the answer together. We introduce the notion of **vector space** and **subspace**. We look at many examples of vector spaces/subspaces and learn some basic properties. This will help us to understand the real power of linear algebra - the *abstract approach* and to answer what is *vector*.

## Terminology

- axiom
- addition
- scalar multiplication
- vector space
- vectors
- zero vector
- linear combination
- subspace
- trivial subspace

 

## Theorems

- subspace test (Theorem 6.2 in textbook)


## Key points


- notion of vector space
- notion of subspace




## Challenge

1. Let `$V$` be a vector space, `$\bf u$` a vector in `$V$`, and `$c$` scalar. Show the following.

   a) `$0{\bf u} = {\bf 0}$`
   
   b) `$(-1){\bf u} = - {\bf u}$`
   
   c) If `$c{\bf u} = {\bf 0}$`, then `$c= 0$` or `${\bf u} = {\bf 0}$`.
 
2. Determine whther the given set, together with the specified operations of addition and scalar multiplication, is a vector space. If it is not, list all of the axioms that fail to hold.

    a) The set of all vectors in `$\mathbb R^2$` of the form `$\left[\begin{array}{c} x \\ x \end{array}\right]$`, with the usual vector addition and scalar multiplication.
    
    b) The set of all `$2\times 2$`matrices of the form `$\left[\begin{array}{cc} a& b \\ c&d \end{array}\right]$`, where `$ad = 0$`, with the usual matrix addition and scalar multiplication.



3. Let `$\mathcal C$` be the set of all continuous real-valued functions defined on `$\mathbb R$` and let `$\mathcal D$` be the set of all differentiable real-valued functions defined on `$\mathbb R$`. Show that `$\mathcal C$` and `$\mathcal D$`  are subspaces of `$\mathcal F$`, the vector space of all real-valued functions defined on `$\mathbb R$`. 

4.  a) Show that the set `$W$` of all vectors of the form `$\left[\begin{array}{r} a \\ - a \\ b \\ -b\end{array}\right]$` is a subpsace of `$\mathbb R^4$`.

    b) Show that the set `$W$` of all polynomials of the form `$a - ax + bx^2 - bx^3$` is a subpsace of `$\mathcal P_3$`.
    
    c) Show that the set `$W$` of all matrices of the form `$\left[\begin{array}{rr} a & - a \\ b & -b\end{array}\right]$` is a subpsace of `$M_{22}$`.


5. Let `$W$` be the set of all `$2\times 2$` matrices with determinant equal to `$0$`. Is `$W$` a subspace of `$M_{22}$`?


6. Use subspace test (Theorem 6.2 in textbook) to determine whether `$W$` is a subspace of `$V$`.

    a) `$V = \mathbb R^3$`, `$W = \left\{ \left[\begin{array}{c} a \\ b\\ |a| \end{array}\right]\right\}$`
    
    b) `$V = \mathcal P_2$`, `$W = \{a + bx + cx^2: abc = 0 \}$`


## Resources

- Check textbook

- [Abstract vector spaces by  3blue1brown](https://youtu.be/TgKwz5Ikpc8)
 



- Explore the Internet

## Tips


- You learn more from trying and failing than from an immediate explanation.

- Find and solve as many exercises as YOU need to become proficient.

- Required minimum must be set, however it is a waste of time for everybody if you do not aim higher.






