---
title: "Filip Schjerven"
date: 2020-06-01
draft: false
oppgavetype: ["Masteroppgave", "Matematikk"]
fagfelt: ["Statistikk"]
tags: [""]
veileder: ["Ingelin Steinsland","Frank Lindseth"]
math: true
summary: "Prediction models for hypertension using the HUNT Study data"
---

**Tittel:** Prediction models for hypertension using the HUNT Study data

**Veileder:** [Ingelin Steinsland]({{<ref "/veileder/ingelin-steinsland">}}), [Frank Lindseth]({{<ref "/veileder/frank-lindseth">}}) 

**Sammendrag:** I denne oppgaven sammenlignes forskjellige modellfamiliers evne til å predikere 11-års risikoen for binær hypertensjon status, ved bruk av data fra helseundersøkelsen i Trøndelag, HUNT. Modellfamiliene som ble valgt var logistisk regresjon, nevrale netverk og random forest. Målet for hver enkelt modell var å predikere risikoen for hypertensjon ved HUNT-3 studien for individer som var friske ved HUNT-2, ved bruk av målinger tatt i HUNT-2.

Til å begynne med ble det gjennomført et litteraturstudie for å få oversikt over forskningen på risiko modeller for hypertensjon. Det var ikke mulig å fastslå at en av modellfamiliene skulle være bedre enn de andre basert på litteraturstudiet.

Etter å ha identifisert de relevante attributtene i litteraturstudiet, ble et subsett av relevante data valgt ut fra det tilgjengelige HUNT datasettet. The endelige datasettet hadde $n = 18249$ individer og $p = 19$ attributter. En utforskende analyse av datasettet viste at 'Systolisk blodtrykk', 'Diastolisk blodtrykk' og 'Alder' var de attributtene som var mest korrelerte med hypertensjon-status ved HUNT-3. 'Kolesterol', 'Familiehistorie med hypertensjon' og fysiske attributter som 'Midjemål' var også verdt å nevne. 

Et repetert trening og testing oppsett ble brukt for å produsere fordelinger av ytelsesmål for de tre modellfamiliene. I tillegg ble Framingham modellen evaluert på et subsett av data hvor attributtene passet og var tilgjengelig. Alle modellene ble evaluert med området under Receiver-Operator-kurven og Precision-Recall-kurven, samt et modifisert Brier mål og et mål kalt Tjur’s R2.

Vi konkluderer med at ytelsen var mer påvirket av variabiliteten i datasettet enn valget av modellfamilie, ettersom det var større forskjell innad i fordelingene enn mellom modellfamilier. Resultatene antyder at hvis det er noen ikke-lineære effekter, så har de lite ekstra prediktiv kraft sammenlignet med lineære. Videre ble et subsett av attributtene identifisert som særdeles viktige vha. viktighetsmål. En gjentagelse av analysen med dette subsettet i logistisk regresjon og random forest ga ytelsesmål som var like gode som ved bruk av alle attributtene for disse modellfamiliene.

Resultatene fra alle modellfamiliene og attributsettene brukt var sammenlignbare med det som Framingham modellen oppnådde og til den relevante litteraturen. Til slutt, ved å ta hensyn til egenskaper til modellene, så ble den logistiske modellfa-
milien som bruker 'Systolisk blodtrykk', 'Diastolisk blodtrykk', 'Alder', 'Midjemål' og 'Familiehistorie med hypertensjon' som attributter, tilpasset med regularisering, uten
balansert tapsfunksjon, foreslått som det optimale modelloppsett for problemet. For videre arbeid ble det foreslått å analysere subsett av data hvor modellene predikerte store feil eller var uenige på tvers av modellfamilier, i tillegg til å gjennomføre en subjektivitets-analyse av litteraturen som omhandler hypertensjon risiko modeller.

<iframe src="https://drive.google.com/file/d/1Wtjx9uXNLZ5G8z945cKxPo9REpfKnn8E/preview" width="700" height="980" allow="autoplay"></iframe>