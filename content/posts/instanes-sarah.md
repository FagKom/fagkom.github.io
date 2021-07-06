---
title: "Sarah May Instanes"
date: 2021-05-20
draft: false
oppgavetype: ["Matematikk", "Bacheloroppgave"]
fagfelt: ["Analyse"]
tags: ["Kompleks analyse"]
veileder: ["Sigrid Grepstad", "Ole Fredrik Brevig"]
katex: true 
summary: "Faktorisering i Hardy-rom"
---

**Tittel:** Faktorisering i Hardy rom

**Veileder:** [Sigrid Grepstad]({{<ref "/veileder/sigrid-grepstad" >}}), [Ole Fredrik Brevig]({{<ref "/veileder/ole-fredrik-brevig">}}) 

**Sammendrag:** I denne oppgaven skal vi se nærmere på noen viktige analytiske funksjoner, nemlig de funksjonene som ligger i Hardy-rommet. For en gitt $0 < p \leq \infty$ består
Hardy-rommet, som vi betegner som $H^p$, av analytiske funksjoner på enhetsdisken med begrenset Hardy-norm. Denne normen er gitt ved

$$\Vert f\Vert_ {H^p} = \lim_ {r\rightarrow 1^-}\left(\frac{1}{2\pi}\int_0^{2\pi}\vert f(re^{i\theta})\vert^p d\theta \right)^{\frac{1}{p}}$$

dersom $0 < p < \infty$, og ved

$$\Vert f \Vert_ {H^\infty} = \lim_{r\rightarrow 1^-}\underset{0\leq \theta \leq 2\pi}{max}\vert f(re^{i\theta})\vert$$

hvis $p = \infty$. Merk at for $0 < p < 1$ er ikke $\Vert f\Vert_{H^p}$ en faktisk norm, men en kvasinorm. Det betyr at i stedet for den vanlige trekantulikheten har vi at

$$\Vert f+g\Vert_ {H^p} \leq 2^{\frac{1}{p}-1}\left(\Vert f\Vert_ {H^p}+\Vert g\Vert_ {H^p}\right)$$

I denne oppgaven ønsker vi å faktorisere ut nullpunktene til en funksjon i Hardy-rommet ved hjelp av et Blaschke-produkt. Et Blaschke-produkt er en funksjon på formen

$$B(z) = z^m \prod_{n=0}^{\infty}\frac{\vert a_n\vert}{a_n}\frac{a_n-z}{1-\overline{a_n}z}$$

der $m$ er et ikke negativt-heltall, $\\{a_ n\\} _{n\geq 0}$ er en følge slik at $0 < \vert a_n\vert < 1$ for alle $n$ og $\sum_{n=0}^{\infty}(1 -\vert a_n\vert) < \infty$. Vi skal senere se at $\vert B(z)\vert < 1$ på enhetsdisken, og at $\vert B(e^{i\theta})\vert = 1$ nesten overalt.

<iframe src="https://drive.google.com/file/d/1MQMvJXYge7eNym8Uc8HIvBSRHYzn-eAj/preview" width="700" height="980" allow="autoplay"></iframe>

