---
title: "Didrik Fosse"
date: 2017-06-01
draft: false
oppgavetype: ["Bacheloroppgave","Matematikk"]
fagfelt: ["Algebra"]
tags: ["Representasjonsteori"]
veileder: ["Øyvind Solberg"]
math: true 
summary: "Finding homomorphisms between representations of a quiver"
---

**Tittel:** Finding homomorphisms between representations of a quiver

**Veileder:** [Øyvind Solberg]({{< ref "/veileder/øyvind-solberg">}}) 

**Sammendrag:** Representation theory of finite dimensional algebras is an important branch of algebra, with a wide array of results that can be used in many different parts of mathematics. Calculating with concrete values in representation theory is usually straight forward in terms of computations, but it can be both time consuming and painstaking. This makes computers a perfect tool for the task. The mathematical software tool GAP contains a package called QPA (Quivers and Path Algebras), which is designed to be used as a computational tool in representation theory of finite dimensional algebras.

In this paper, I will look at the QPA function **BasisOfHom( R1, R2 )**. It takes as input **R1** and **R2**, which are two representations of the same quiver, and computes a basis for the vector space of homomorphisms from R1 to R2. I will begin by giving some necessary definitions. Then I will show the linear algebra behind the problem of finding a basis for the vector space of homomorphisms between two representations, and I will explain how the algorithm **BasisOfHom** actually computes this. I have included an example to help illustrate the process. Finally, I have done some preliminary work on how to create an algorithm that computes a basis for the space of homomorphisms from an arbitrary chain complex of representations to a finite chain complex of representations. Please note that all vectors in this text are row vectors.

<iframe src="https://drive.google.com/file/d/1dkeH6ihfnVElbllE3988bGCnaS0soIOE/preview" width="700" height="900" allow="autoplay"></iframe>

