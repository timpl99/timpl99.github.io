---
layout: page
title: Open problems
permalink: /open-problems/
---

A selection of open problems that I find particularly interesting.

#### Colouring 2-complexes in 3-space
{: #colouring-2-complexes }

> **Question.** Can the edges of every finite simplicial 2-complex embedded in ℝ<sup>3</sup> be coloured with three colours so that every triangular face has edges of at least two colours?

**Known bounds.** Four colours always suffice, and some embedded simplicial 2-complexes cannot be coloured with two colours without a monochromatic face. Hence the smallest number of colours that works for all such complexes is either three or four.

See [Question 8.1 in my paper *Colouring the 1-skeleton of d-dimensional triangulations*](https://igt.centre-mersenne.org/item/10.5802/igt.13.pdf#page=23), Innovations in Graph Theory **2** (2025), 275–299.

<figure class="my-4 text-center">
  <img src="{{ '/assets/img/2-complex.svg' | relative_url }}"
       class="img-fluid d-block mx-auto"
       width="440" height="407"
       alt="A subdivided tetrahedron with red, blue and green."
       style="width: 100%; max-width: 440px; height: auto;">
</figure>

#### Shallow hitting sets and polychromatic colourings for squares
{: #squares }

Let *P* be a finite set of points in the plane. All squares below are axis-aligned and may have arbitrary side lengths.

> **Question (shallow hitting sets).** Is there an absolute constant *t* such that, for every *P* and every integer *m* ≥ 1, there is a subset *S* ⊆ *P* for which every square containing exactly *m* points of *P* contains at least one and at most *t* points of *S*?

> **Question (polychromatic colourings).** Is there an absolute constant *C* such that, for every *P* and every integer *k* ≥ 2, the points of *P* can be coloured with *k* colours so that every square containing at least *Ck* points of *P* contains all *k* colours?

A positive answer to the first question would imply a positive answer to the second.

See [Table 1 and Section 5 of my paper with Torsten Ueckerdt, *Polychromatic Colorings of Geometric Hypergraphs via Shallow Hitting Sets*](https://drops.dagstuhl.de/storage/00lipics/lipics-vol293-socg2024/LIPIcs.SoCG.2024.74/LIPIcs.SoCG.2024.74.pdf#page=12), SoCG 2024, **293**, 74:1–74:14.


<figure class="my-4 text-center">
  <img src="{{ '/assets/img/squares.svg' | relative_url }}"
       class="img-fluid d-block mx-auto"
       width="440" height="300"
       alt="polychromatic colouring of axis-aligned squares">
</figure>