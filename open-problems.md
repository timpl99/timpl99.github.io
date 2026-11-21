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

The classical Tutte-decomposition can be computed in linear time. Can its extensions to higher connectivity also be computed efficiently?

> **Conjecture (tetra-decomposition).** There is an algorithm that computes the tetra-separation decomposition of any finite 4-connected graph in linear time.

See Conjecture 1.4 in my paper with Jan Kurkofka, *A Tutte-type canonical decomposition of 3- and 4-connected graphs* (<a href="https://arxiv.org/abs/2504.00760" class="link">arXiv</a>), SODA 2026.

For every *k*, our approximate cactus-decomposition represents all *k*-separations of a *k*-connected graph up to an error bounded in terms of *k*.

> **Question (cactus-decomposition).** For fixed *k*, can the approximate cactus-decomposition for *k*-connected graphs from our paper be computed in linear time?

See Conjecture 1.3 in my paper with Romain Bourneuf, Johannes Carmesin and Jan Kurkofka, *An approximate cactus-decomposition for vertex-connectivity* (<a href="https://arxiv.org/abs/2611.01772" class="link">arXiv</a>).

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

See Question 8.1 in my paper *Colouring the 1-skeleton of d-dimensional triangulations* (<a href="https://doi.org/10.5802/igt.13" class="link">journal version</a>), Innovations in Graph Theory **2** (2025), 275–299.

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

See Table 1 and Section 5 in my paper with Torsten Ueckerdt, *Polychromatic Colorings of Geometric Hypergraphs via Shallow Hitting Sets* (<a href="https://doi.org/10.4230/LIPIcs.SoCG.2024.74" class="link">conference version</a>), SoCG 2024, **293**, 74:1–74:14.

</div>

<h3 id="solved-problems" class="fw-bold border-bottom pb-3 mb-5">Solved problems</h3>

#### Shallow hitting edge sets in regular hypergraphs
{: #shallow-hitting-edge-sets }

<div class="problem-section" markdown="1">

A set of edges of a hypergraph is a *t*-shallow hitting edge set if every vertex belongs to at least one and at most *t* of the selected edges.

> **Question.** Is there an absolute constant *C* such that, for every integer *r* ≥ 2, every finite *r*-uniform regular hypergraph has a (*C* log *r*)-shallow hitting edge set?

In our paper, we proved a logarithmic lower bound and a linear upper bound for the smallest guaranteed shallowness.

See Section 5 in my paper with Torsten Ueckerdt, *Shallow Hitting Edge Sets in Uniform Hypergraphs* (<a href="https://arxiv.org/abs/2307.05757" class="link">arXiv</a>).

<strong class="text-danger">Solved (2026).</strong> Noga Alon, Penny Haxell, Aleksa Milojević and Jacques Verstraëte proved the following.

> **Theorem.** For every integer *r* ≥ 2, every finite *r*-uniform regular hypergraph has a (100 log *r*)-shallow hitting edge set.

Together with our lower bound, this establishes that the optimal guaranteed shallowness has order Θ(log *r*).

See Theorem 1.2 in *Spanning subhypergraphs with degree constraints* (<a href="https://arxiv.org/abs/2609.13002" class="link">arXiv</a>).

</div>