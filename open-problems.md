---
layout: page
title: Open problems
permalink: /open-problems/
---

A selection of open problems that I find particularly interesting.

#### Computing tetra- and cactus-decompositions
{: #computing-decompositions }

<div class="problem-section" markdown="1">

<figure class="problem-figure">
  <img src="{{ '/assets/img/cactus-decomposition.png' | relative_url }}"
       width="1750" height="789"
       alt="A graph in black, with blue bags and a red decomposition cactus.">
  <figcaption>
    A cactus-decomposition of a 2-connected graph.
  </figcaption>
</figure>

The classical Tutte-decomposition can be computed in linear time. Can its extensions to higher connectivity also be computed efficiently? Below, *n* and *m* denote the numbers of vertices and edges, respectively.

> **Conjecture (tetra-decomposition).** There is an algorithm that computes the tetra-separation decomposition of any finite 4-connected graph in time *O*(*n* + *m*).

See [Conjecture 1.4 in my paper with Jan Kurkofka, *A Tutte-type canonical decomposition of 3- and 4-connected graphs*](https://arxiv.org/abs/2504.00760), SODA 2026.

For every *k*, our approximate cactus-decomposition represents all *k*-separations of a *k*-connected graph up to an error bounded in terms of *k*.

> **Question (cactus-decomposition).** For fixed parameters, can the approximate cactus-decomposition from [our paper](https://arxiv.org/abs/2611.01772) be computed in linear time?

See Conjecture 1.3 in my paper with Romain Bourneuf, Johannes Carmesin and Jan Kurkofka, [*An approximate cactus-decomposition for vertex-connectivity*](https://arxiv.org/abs/2611.01772).

</div>

#### Colouring 2-complexes in 3-space
{: #colouring-2-complexes }

<div class="problem-section" markdown="1">

<figure class="problem-figure">
  <img src="{{ '/assets/img/2-complex.svg' | relative_url }}"
       width="400" height="370"
       alt="A tetrahedron with its inner chamber subdivided, and edges coloured red, blue and green.">
</figure>

> **Question.** Can the edges of every finite simplicial 2-complex embedded in ℝ<sup>3</sup> be coloured with three colours so that every triangular face has edges of at least two colours?

**Known bounds.** Four colours always suffice, and some embedded simplicial 2-complexes cannot be coloured with two colours without a monochromatic face. Hence the smallest number of colours that works for all such complexes is either three or four.

See [Question 8.1 in my paper *Colouring the 1-skeleton of d-dimensional triangulations*](https://igt.centre-mersenne.org/item/10.5802/igt.13.pdf#page=23), Innovations in Graph Theory **2** (2025), 275–299.

</div>

#### Shallow hitting sets and polychromatic colourings for squares
{: #squares }

<div class="problem-section" markdown="1">

<figure class="problem-figure">
  <img src="{{ '/assets/img/squares.svg' | relative_url }}"
       width="440" height="300"
       alt="Points coloured with three colours and four axis-aligned squares, each containing five points and all three colours.">
</figure>

All squares below are axis-aligned and may have arbitrary side lengths.

> **Question (shallow hitting sets).** Is there an absolute constant *t* such that, for every finite *P* ⊆ ℝ<sup>2</sup> and every integer *m* ≥ 1, there is a subset *S* ⊆ *P* for which every square containing exactly *m* points of *P* contains at least one and at most *t* points of *S*?

> **Question (polychromatic colourings).** Is there an absolute constant *C* such that, for every finite *P* ⊆ ℝ<sup>2</sup> and every integer *k* ≥ 2, the points of *P* can be coloured with *k* colours so that every square containing at least *Ck* points of *P* contains all *k* colours?

A positive answer to the first question would imply a positive answer to the second.

See [Table 1 and Section 5 of my paper with Torsten Ueckerdt, *Polychromatic Colorings of Geometric Hypergraphs via Shallow Hitting Sets*](https://drops.dagstuhl.de/storage/00lipics/lipics-vol293-socg2024/LIPIcs.SoCG.2024.74/LIPIcs.SoCG.2024.74.pdf#page=12), SoCG 2024, **293**, 74:1–74:14.

</div>