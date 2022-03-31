---
title: "Trygve Poppe Oldervoll"
date: 2020-05-20
draft: false
oppgavetype: ["Bacheloroppgave", "Matematikk"]
fagfelt: ["Topologi"]
tags: ["Symplektisk topologi", "Differensialtopologi"]
veileder: ["Glen Matthew Wilson"]
katex: true
summary: "The Arnold conjecture"
---

**Tittel:** The Arnold conjecture - An introduction to symplectic topology

**Veileder:** 
[Glen Matthew Wilson]({{<ref "/veileder/glen-matthew-wilson">}})

**Sammendrag:** Many problems in mathematics boil down to finding fixed points of certain maps. Therefore we are always interested in tools for finding, or just guaranteeing the existence of such points. To this end we have many important results like Banach’s, and Brouwer’s fixed point theorems. In the case of differential topology, the most standard tool to study fixed points is the Lefschetz fixed point theorem. It states that if $f : M\longrightarrow M$ is a smooth map of the smooth manifold $M$,
$$\Gamma_f = \Sigma_{x\in Fix(f)}i(x, f)$$ 
where $i(x, f)$ is the index of the fixed point, and $\Gamma f$ is the Lefschetz number of $f$. The Lefschetz number can be computed as the alternating sum of traces of the matrix representations of $f_\ast$ on the rational homology spaces. In particular, if $f$ is homotopic to the identity, the formula above becomes
$$\Gamma_f = \Gamma_{id} = \Chi(M)=\Sigma_{k=0}^n(-1)^k b_k$$
where $b_k$ are the Betti numbers of $M$, and $\dim M = n$. This is very useful, but if all we care about is the number of fixed points, the best we can do is give the lower bound
$$\Gamma_f \neq 0 \implies \# Fix(f)\geq 1.$$

Under what circumstances can we do better? One important special case of smooth maps of manifolds are symplectomorphisms. This special class of diffeomorphisms arise naturally as the time evolutions and symmetries of Hamiltonian systems in physics, and are at the core of the field of symplectic topology. So what can we say about the number of fixed points of symplectomorphisms? Quite a lot actually, especially under some mild extra conditions. Our hopes are summarized in the following conjecture by Vladimir Arnold.

**Conjecture 1.1 (Arnold).** If $\psi : M \longrightarrow M$ is a Hamiltonian symplectomorphism of a symplectic manifold $(M, \omega)$, then $\psi$ must have at least as many fixed points as a function on $M$ must have critical points. If all the fixed points of $\psi$ are nondegenerate, $\psi$ must have at least as many fixed points as a Morse function on $M$ must have critical points.


<iframe src="https://drive.google.com/file/d/1HHI7EfRvawcuq9W_ODW_hWFPYkv5OJ9J/preview" width="700" height="980" allow="autoplay"></iframe>