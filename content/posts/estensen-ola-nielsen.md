---
title: "Ola Nielsen Estensen"
date: 2019-05-01
draft: false
oppgavetype: ["Masteroppgave", "Fysikk"]
fagfelt: [""]
tags: [""]
veileder: ["Jeroen Danon"]
math: true
summary: "Controlling nuclear field gradients in triple quantum dot by Landau-Zener sweeps"
---

**Tittel:** Controlling nuclear field gradients in triple quantum dot by Landau-Zener sweeps

**Veileder:** [Jeroen Danon]({{<ref "/veileder/jeroen-danon">}}) 

**Sammendrag:** Trippel-spin kvanteprikker i GaAs har tidligere blitt foreslått som kandidat til kvante bit. Begrensningene til slike systemer følger av den hyperfine interaksjonen mellom elektronene og atomkjernene i vertsmaterialet, som forårsaker tap av fasen til elektronenes kvantetilstand og dermed tap av informasjon. Det effektive feltet atomkjernene utøver på elektronene vil svinge tilfeldig som gjør det vanskelige å kompensere for. I denne avhandlingen vil vi se på muligheten for å begrense størrelsen på disse svingningene gjennom Landau-Zener overganger mellom tilstanden $|0\rangle$ og $|Q_{3/2}\rangle$, som vil forårsake forandring av spin-retningen til atomkjernene.

En Hubbard Hamilton-funksjon vil bli brukt og leder til stabilitets-diagram for ladning over de tre prikkene. Dette diagrammet viser de mulige overgangene mellom elektron konfigurasjoner på prikkene som funksjon av det elektroniske potensialet man setter over hver av dem. Ved hjelp av dette diagrammet kan man begrense de mulige tilstandene til systemet ved å tilpasse potensialene. Vi vil bruke konfigurasjonene $(2, 0, 1)$, $(1, 1, 1)$ og $(1, 0, 2)$ som deretter angir de mulige tilstandene. Disse tilstandene kan deles inn i forskjellige grupper med forskjellige spin-tall $S_z$ og vi vil bruke tilstandene som tilhører $S_z = 1/2$ og $S_z = 3/2.$ Dette vil utgjøre totalt seks tilstander.

Egentilstandene til systemet kan bli funnet ved hjelp av numeriske metoder og vårt valg av logiske tilstander ${|0\rangle, |1\rangle}$ vil utgjøre de to laveste tilstandene med $S_z = 1/2.$ På grunn av forskjellen i Zeeman-energi mellom $|0\rangle$ og $|Q_{3/2}\rangle$ kan man oppnå et krysningspunkt i energiene deres ved å justere et ytre magnetisk felt. Dette krysningspunktet kan brukes i Landau-Zener overganger for å endre orientering til elektronets spin, som igjen vil resultere i en endring i atomkjernenes spin.

Det effektive magnetiske feltet som utøves på elektronene vil påvirke krysningspunktet til energiene. Dette feltet er igjen påvirket av spin-tilstanden til atomkjernene og dette fører sammen til en tilbakekoblingsprosess. For å simulere effecten av denne prosessen anvender vi den numerisk beregnede $|0\rangle$ og drar nytte av smarte metoder for å sveipe gjennom krysningspunktet. Dette vil vi vise har en effekt på svingningene til det effektive feltet fra atomkjernenes spin som indikerer at en slik metode kan anvendes for å minske effekten av den hyperfine interaksjonen. Slik redusering er fundamentalt for å anvende slike systemer som kvante bit.

Vi presenterer også et analytisk uttrykk for $|0\rangle$ funnet gjennom perturbasjonsteori som gjelder for alle, hvis man antar fravær av hyperfin interaksjon. Dette er et første steg i analytisk forståelse av tids dynamikken til polariseringen som følge av Landau-Zener overganger.

<iframe src="https://drive.google.com/file/d/1Xbne-5MxBCXpM6HExlcklBQ3y1MzuXZ6/preview" width="700" height="980" allow="autoplay"></iframe>