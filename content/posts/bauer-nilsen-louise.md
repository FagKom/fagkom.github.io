---
title: "Louise Bauer-Nilsen"
date: 2020-05-20
draft: false
oppgavetype: ["Bacheloroppgave", "Matematikk"]
fagfelt: ["Statistikk"]
tags: ["Flernivåmodeller"]
veileder: ["Geir-Arne Fuglstad"]
math: true
summary: "Analysing nested data with multilevel models"
---

**Tittel:** Analysing nested data with multilevel models

**Veileder:** [Geir-Arne Fuglstad]({{<ref "/veileder/geir-arne-fuglstad">}})

**Sammendrag:** For å analysere nestede datasett bruker vi metoden for flernivåmodellering. Med nestede datasett mener vi at vi har en naturlig gruppering i datasettet. Ved å bruke flernivåmodellering til å analysere dataen kan vi få innsikt i variasjon mellom og innad i grupper og forskjellen i variabilitet for de forskjellige flernivåmodellene. Vi bruker R-pakken lme4 og bruker funksjonen lmer() for å tilpasse de forskjellige flernivåmodellene. For de forskjellige modellene lar vi enten skjæringspunktet eller stigningstall variere. Dette gir oss tre forskjellige modeller, modellen med varierende skjæringspunkt, modellen med varierende stigningstall, og til sist, modellen hvor vi lar både stigningstall og skjæringspunkt variere. På modellene kan vi også legge til prediktorer på de forskjellige nivåene. Vi bruker et eksempel på radondata der vi vil måle radonnivåene i amerikanske hjem, dataen er strukturert slik at vi har husholdninger inni de forskjellige fylkene. Vi tilpasser dataene våre og kan se, etter modell sjekking, at en mer komplisert modell vil forbedre tilpasningen, og vi kan også observere variansen i de forskjellige nivåene.

<iframe src="https://drive.google.com/file/d/1aG-_RceeJCOBucyU9ppapjIW-I8iw9Pc/preview" width="700" height="980" allow="autoplay"></iframe>