---
title: "Emma Sofie Skarstein"
date: 2020-07-01
draft: false
oppgavetype: ["Masteroppgave", "Matematikk"]
fagfelt: ["Statistikk"]
# tags: [""]
veileder: ["Robert Brian OHara"]
math: true
summary: "Accounting for spatial bias in citizen science observations of Norwegian freshwater fish by using an effort spatial field"
---

**Tittel:** Accounting for spatial bias in citizen science observations of Norwegian freshwater fish by using an effort spatial field

**Veileder:** [Robert Brian O'Hara]({{<ref "/veileder/robert-brian-Ohara">}}) 

**Sammendrag:** Modellbasert dataintegrasjon gir et lovende rammeverk for konstruksjon av artsfordelingsmodeller ved bruk av folkeforsknings-data sammen med strukturerte data fra undersøkelser, men en vanlig utfordring er hvordan man skal forholde seg til romlige skjevheter i folkeforsknings-dataene i slike modeller.

Jeg implementerer en integrert artsfordelingsmodell ved å bruke to datasett med observasjoner av ferskvannsfisk i Norge: et strukturert datasett, og et folkeforskningsdatasett. Det antas en log-Gaussisk Cox-prosess for den underliggende fordelingen til dataene. I tillegg antas det individuelle observasjonsprosesser for hvert datasett, men med felles miljømessige kovariater og et felles romlig felt. Observasjonsprosessen for folkeforsknings-dataene blir også gitt et eget romlig felt som estimeres fra folkeforsknings-data alene. Dette lar oss estimere den romlige skjevheten til disse observasjonene.

Ved å sammenligne dette estimerte separate romlige feltet på tvers av fire forskjellige arter av ferskvannsfisk, ser vi at selv i fiskearter med svært forskjellige fordelinger, er det romlige feltet veldig likt. Når vi sammenligner varianter av integrerte modeller med en modell basert kun på undersøkelses-datasettet, yter de integrerte modellene konsekvent bedre enn modellen med bare ett datasett.

All inferens er utført med metodikken “Integrated nested Laplace approximation” (INLA), som gir god fleksibilitet og effektiv utregning.

<iframe src="https://drive.google.com/file/d/1cbdFpobY8sDLraTiFPg-KMJvQKG9PSOf/preview" width="700" height="980" allow="autoplay"></iframe>