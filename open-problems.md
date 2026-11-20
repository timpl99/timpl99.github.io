---
layout: page
title: Open problems
permalink: /open-problems/
---

A selection of open problems that I find particularly interesting.

#### Computing cactus-decompositions
{: #computing-decompositions }

<div class="row g-4 align-items-center mb-5" markdown="1">
<div class="col-lg-7" markdown="1">

The classical Tutte-decomposition can be computed in linear time. Can its extensions to higher connectivity also be computed efficiently? Below, *n* and *m* denote the numbers of vertices and edges, respectively.

> **Conjecture (tetra-decomposition).** There is an algorithm that computes the tetra-separation decomposition of any finite 4-connected graph in time *O*(*n* + *m*).

See [Conjecture 1.4 in my paper with Jan Kurkofka, *A Tutte-type canonical decomposition of 3- and 4-connected graphs*](https://arxiv.org/abs/2504.00760), SODA 2026.

For every *k*, our approximate cactus-decomposition represents all *k*-separations of a *k*-connected graph up to an error bounded in terms of *k*.

> **Conjecture (cactus-decomposition).** There exist computable functions *f* and *η* and an algorithm that, given integers *q*, *k* and a finite (*q*, *k* − 1)-unbreakable graph, constructs in time *f*(*q*, *k*)(*n* + *m*) a cactus-decomposition displaying separations of order at most *k*, such that every separation of order at most *k* is within edit-distance *η*(*q*, *k*) of a displayed separation.

Here, a graph is *(*q*, *k* − 1)-unbreakable* if every separation of order at most *k* − 1 has at most *q* vertices on one side outside the separator. This includes all *k*-connected graphs when *q* = 0.

See [Conjecture 1.3 in my paper with Romain Bourneuf, Johannes Carmesin and Jan Kurkofka, *An approximate cactus-decomposition for vertex-connectivity*](https://arxiv.org/abs/2611.01772).

<div class="col-lg-5">
  <figure class="mb-0 text-center">
    <object
      data="{{ '/assets/img/cactus-decomposition.pdf' | relative_url }}#view=Fit&toolbar=0&navpanes=0"
      type="application/pdf"
      class="d-block mx-auto"
      style="width: 100%; max-width: 440px; height: 340px;">
      <a href="{{ '/assets/img/cactus-decomposition.pdf' | relative_url }}">
        View the cactus-decomposition figure (PDF)
      </a>
    </object>
  </figure>
</div>

#### Colouring 2-complexes in 3-space
{: #colouring-2-complexes }

<div class="row g-4 align-items-center mb-5" markdown="1">
<div class="col-lg-7" markdown="1">

> **Question.** Can the edges of every finite simplicial 2-complex embedded in ℝ<sup>3</sup> be coloured with three colours so that every triangular face has edges of at least two colours?

**Known bounds.** Four colours always suffice, and some embedded simplicial 2-complexes cannot be coloured with two colours without a monochromatic face. Hence the smallest number of colours that works for all such complexes is either three or four.

See [Question 8.1 in my paper *Colouring the 1-skeleton of d-dimensional triangulations*](https://igt.centre-mersenne.org/item/10.5802/igt.13.pdf#page=23), Innovations in Graph Theory **2** (2025), 275–299.

</div>
<div class="col-lg-5">
  <figure class="mb-0 text-center">
    <img src="{{ '/assets/img/2-complex.svg' | relative_url }}"
         class="img-fluid d-block mx-auto"
         width="440" height="407"
         alt="A subdivided tetrahedron with red, blue and green edges."
         style="width: 100%; max-width: 440px; height: auto;">
  </figure>
</div>
</div>

#### Shallow hitting sets and polychromatic colourings for squares
{: #squares }

<div class="row g-4 align-items-center mb-5" markdown="1">
<div class="col-lg-7" markdown="1">

All squares below are axis-aligned and may have arbitrary side lengths.

> **Question (shallow hitting sets).** Is there an absolute constant *t* such that, for every finite *P* ⊆ ℝ<sup>2</sup> and every integer *m* ≥ 1, there is a subset *S* ⊆ *P* for which every square containing exactly *m* points of *P* contains at least one and at most *t* points of *S*?

> **Question (polychromatic colourings).** Is there an absolute constant *C* such that, for every finite *P* ⊆ ℝ<sup>2</sup> and every integer *k* ≥ 2, the points of *P* can be coloured with *k* colours so that every square containing at least *Ck* points of *P* contains all *k* colours?

A positive answer to the first question would imply a positive answer to the second.

See [Table 1 and Section 5 of my paper with Torsten Ueckerdt, *Polychromatic Colorings of Geometric Hypergraphs via Shallow Hitting Sets*](https://drops.dagstuhl.de/storage/00lipics/lipics-vol293-socg2024/LIPIcs.SoCG.2024.74/LIPIcs.SoCG.2024.74.pdf#page=12), SoCG 2024, **293**, 74:1–74:14.

</div>
<div class="col-lg-5">
  <figure class="mb-0 text-center">
    <img src="{{ '/assets/img/squares.svg' | relative_url }}"
         class="img-fluid d-block mx-auto"
         width="440" height="300"
         alt="Polychromatic colouring of points with respect to axis-aligned squares."
         style="width: 100%; max-width: 440px; height: auto;">
  </figure>
</div>
</div>
