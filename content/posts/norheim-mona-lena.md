---
title: "Mona-Lena Norheim"
date: 2019-07-01
draft: false
oppgavetype: ["Masteroppgave", "Matematikk"]
fagfelt: ["DNA"]
tags: ["MATLAB"]
veileder: ["Knut-Andreas Lie", "Olav Møyner"]
math: false
summary: "Investigating iterative solvers of Poisson-type equations discretized by the Two-Point Flux-Approximation scheme"
---

**Tittel:** Investigating iterative solvers of Poisson-type equations discretized by the Two-Point Flux-Approximation scheme

**Veileder:** [Knut-Andreas Lie]({{<ref "/veileder/knut-andreas-lie">}}), [Olav Møyner]({{<ref "/veileder/olav-møyner">}}) 

**Sammendrag:** In this thesis we investigate alternative iterative solvers to MATLAB’s in-built direct solver ```mldivide``` for Poisson-type problems. The solvers are tested on two models used for the purpose of benchmark studies for field development optimization: Olympus and SPE10 [5] [6]. It is found that the iterative solvers, in general, perform better than ```mldivide``` for large, computationaly heavy systems. It is evident that the use of algebraic multigrid (AMG) as a preconditioner improves convergence dramatically. Among the tested iterative solvers it is Krylov solvers BiCGstab and BiCGstab(l) combined with the smoother ILU(0) and the coarsening strategy smoothed aggregation that performed overall best.

<iframe src="https://drive.google.com/file/d/1c9u5kZ_rsP_OFgmstk9aNCSFJWWrM2Iv/preview" width="700" height="980" allow="autoplay"></iframe>