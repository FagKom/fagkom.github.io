---
title: "Filip Schjerven"
date: 2017-06-07
draft: false
oppgavetype: ["Matematikk", "Bacheloroppgave"]
fagfelt: ["Statistikk"]
tags: ["Prediktiv analyse"]
veileder: ["???"]
katex: true 
summary: "Predictive analysis of a Gaussian random field"
---

**Tittel:** Predictive analysis of a Gaussian random field

**Veileder:** [???]({{<ref "/veileder/???" >}}) 

**Sammendrag:** Spatial statistics refers to the application of statistical methods in a spatial setting. Statistics in itself is an extremely useful mathematical tool to quantify uncertainty. Uncertainty is something that we all face in a day to day basis in our daily lives, but perhaps even more so when viewing the world through scientific research. How can we know that our measurements, and thus how the world is described, are certain? In this sense, Cressie & Wikle refers to statistics as the "Science of Uncertainty". Statistics has many ways of dealing with uncertainty, and one of them is that is interprets uncertainty as a measure of variability. Other interpretations could also be used, like entropy. By modelling uncertainty via variability, one may model the total variability by the variability in measurements, in the model used, and due to the uncertainty of parameters in the model [4]. All this happens with the focus on acquiring information from the data that is modelled. In spatial statistics, all this happens in a spatial setting, i.e. the data that are to be analyzed by their topological, geometric or geographic attributes.

A typical model that’s used in spatial statistics is a Gaussian Random Field (GRF). Informally, a GRF is a collection of data interpreted as realizations of stochastic variables. These variables have been given a multivariate Gaussian joint probability function. The random field that it is ’attached’ to typically defines the relation between the variables in some quantifiable way. A typical example (that will also be used extensively) is spatial location. As the joint probability function is multivariate Gaussian, all subsets of variables that are included in the GRF is also multivariate Gaussian. Their attributes are still defined by the relation inherited from the random field. Due to the many useful properties of a multivariate Gaussian distributed variable, the GRF is a useful way to model data.

In order to model data in a easy to interpret way, a model for GRF is often used to describe the various parts of the model. An example that wil be used in this project is the Bayes hierarchical model (BHM). The exact formulation of a BHM is presented later, but summarized it consists of a 1) data model for specifying the data acquirement, 2) a process model for describing the latent process that is typically of interest and lastly, 3) prior model, detailling any parameter-priors that are used in the Bayesian setting. By distinguishing between the three, interpretability is made easy and one gets an intuitive way to understand the data acquirement and how it relates to the latent process.

As the latent process is typically of interest, making the correct data acquirement is crucial in order to achieve sufficient information from the data. In spatial statistics this is important, as the data must then be sampled at the correct locations relative to the model. A set of measurement-locations is called a sampling design, or simply design, in spatial setting. Choosing the correct sampling design may be crucial for achieving the desired information, and must be evaluated while adhering to possible limitations as cost and precision of measurements. Constructing sampling designs happens typically in two settings, retroactive design and proactive design. A retrospective design will focus on altering the existing design on the basis of obtained data, while a proactive design will focus on constructing the optimal design on the basis of prior data and estimate the unknown posterior data.

<iframe src="https://drive.google.com/file/d/1zYGT6rn4uRLo5bdYQA0S5W-nwTQxDN91/preview" width="700" height="980" allow="autoplay"></iframe>

