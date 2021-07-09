---
title: "Andreas Matre"
date: 2020-05-20
draft: false
oppgavetype: ["Matematikk", "Bacheloroppgave"]
fagfelt: ["Statistikk"]
tags: [""]
veileder: ["Geir-Arne Fuglestad"]
katex: true 
summary: "Linear regression for survey data"
---

**Tittel:** Linear regression for survey data

**Veileder:** [Geir-Arne Fuglestad]({{<ref "/veileder/geir-arne-fuglestad" >}}) 

**Sammendrag:** In this thesis we discuss how to do linear regression when the data is collected using a complex sampling design. We use a different paradigm from classical regression, where we assume an infinite population and that the response observed for each individual is random. Here, we instead acknowledge that the population is finite and assume the value of each individual is fixed and the randomness arises from which individuals are included in the sample. The major issues are accounting for different sampling designs to prevent bias and incorrect uncertainty estimates.

We explain three different sampling techniques: the first sampling technique we look at is a Simple Random Sample. First, we choose the size of the sample. Then we let each possible subset of the population, of that sample size, have the same probability of being chosen as the sample. A Simple Random Sample has the advantage that all the sampled units are independent. The second sampling technique we look at is stratification. Here we split the population into a partition and sample independently from each subset. This allows us to get independent regression lines from each subset. The third sampling technique we look at is clustering. Here we again split the population into a partition, but instead of sampling from all subsets of the partition we instead sample only from some of the subsets, chosen by taking a sample of the subsets. Clustering is used to reduce costs when doing surveys. Often the clusters are geographical areas, which means that sampling only inside some subsets allow us to save travel time. When performing large surveys, these techniques are usually combined into what is called a complex survey. For example, by first doing stratification on the whole population and then using clustering inside each subset.

If the sampling units inside the strata are similar, then stratification will reduce the uncertainty compared to a SRS of the same size. With clustering, however, we usually get larger uncertainty, as units inside clusters are usually more similar than units across clusters. This causes the sample to carry less information than a non clustered sample. This leads to hypothesis tests regarding the regression line having less power and the prediction intervals to become larger. The non-linear nature of the regression coefficients means that estimating their variance becomes complicated. We therefore show an approximation technique called linearization.

<iframe src="https://drive.google.com/file/d/12e3Kz59OXMKZWKTyuiDZp0mCRxwO6UyX/preview" width="700" height="980" allow="autoplay"></iframe>

