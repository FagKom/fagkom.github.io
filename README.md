# Linjeforeningen Deltas oppgavearkiv

Velkommen! Delta er linjeforeningen for matematikk og fysikk på NTNU, så i dette arkivet finner du mange spennende bachelor og masteroppgaver skrevet av studenter som har vært innom oss i Delta. Komiteen med ansvaret for å opprettholde dette arkivet heter FagKom, derav navnet. 

## Bidra med din oppgave

Har du vært aktiv i Delta før? Eller kanskje bare vært innom kontoret en gang eller to? Kanskje vært med på fadderuka? Uansett ønsker vi gjerne å ha din oppgave i arkivet! Vi skal prøve å forklare så godt vi kan, men om det er noen spørsmål er det bare å sende mail til [arkivets opprettholder](mailto:torgeiraamboe@gmail.com). 

### Lagring
Det første du trenger å gjøre er å velge et sted å lagre oppgaven slik at den er tilgjengelig for alle Hvis oppgaven er en masteroppgave har du sikkert allereder godtatt at denlegges ut på ntnu.open, noe som fungerer perfekt som en lagringsplass. 

Den andre muligheten er Google drive, og med denne kommer to undermuligheter. Du kan
1) sende oppgaven på epost til [Deltas fagsjef](mailto:delta.fagsjef@gmail.com) slik at hen kan legge oppgaven på Deltas drive, eller
2) legge den på din egen drive. 

I det første tilfellet vil du få tilbake en link fra FagSjef når oppgaven er lagt i arkivet. I det andre tilfellet lager du selv en link ved å dele filen (husk å skru på at alle med link kan se filen!). 

### Filopretting 

For å opprette en side i arkivet med riktig informasjon trenger vi at du fyller ut litt diverse selv. Måten vi har satt opp arkivet på er at hver oppgave inneholder informajon om 
 - Forfatter
 - Oppgavens navn
 - Oppgavetype (bachelor, master, matematikk, fysikk)
 - Oppgavens fagfelt
 - Noen tags som beskriver litt hva oppgaven handler om
 - Veileder

Denne informasjonen skrives inn i en såkalt markdown fil (.md). Du kan opprette en slik fil selv ved å opprette en ren tekst fil (.txt) og endre filnavn, eller ved å kopiere filen "0-template.md" som du kan finne øverst i mappen /contents/posts. Filens navn kan du gjerne kalle "etternavn-fornavn.md" (ikke bruk æ, ø, å). Dersom du har både en bachelor og en masteroppgave i arkivet kan du kalle den andre "etternavn-fornavn-2.md". Dersom du kopierte malfilen vil det allerede være en del tekst i filen, hvis du opprettet en tom fil, kopier følgende kode inn i filen din. 

```
---
title: "Navn"
date: yyyy-mm-dd
draft: true
oppgavetype: ["", ""]
fagfelt: [""]
tags: [""]
veileder: [""]
math: true 
summary: "Oppgavens tittel"
---

**Tittel:** Oppgavens tittel

**Veileder:** [Oppgavens veileder]({{<ref "/veileder/oppgavens-veileder">}}) 

**Sammendrag:** Oppgavens sammendrag

<iframe src="link" width="700" height="980" allow="autoplay"></iframe>
```

Alt som står mellom de to linjene med "---" er såkalt formateriale, og alt som står etter er det som kommer til å faktisk vises på nettsiden. Fyll inn formaterialet med din oppgaves informasjon. Tittel skal fylles ut med oppgavens forfatter, da dette ikke betyr oppgavetittel med nettsidens tittel. Oppgavens tittel skriver du inn i feltet "summary".  Med dato menes datoen du leverte oppgaven. Hvis du ikke husker presist, så sett 1. juni det året du leverte. Siden kommer ikke til å registrere fler en 5 tags, så dersom du legger inn flere vil de 5 første bli brukt på nettsiden. variabelen "math" bestemmer om siden kompilerer LaTeXkode eller ikke, så dersom du har TeX i sammendraget ditt må denne være satt til "true" for at dette skal kompileres. Desverre kompileres ikke TeX i feltet "summary" der du skriver oppgavetittelen. Ok, mye info her nå men her er et eksempel på hvordan det kan se ut til slutt:

```
---
title: "Torgeir Aambø"
date: 2021-06-01
draft: false
oppgavetype: ["Masteroppgave","Matematikk"]
fagfelt: ["Topologi"]
tags: ["Homotopiteori", "Algebraisk topologi"]
veileder: ["Gereon Quick"]
math: true
summary: "On formal DG-algebras"
---
```

Neste skritt er å fylle inn det som faktisk skal stå på nettsiden. Vi har gjort det enkelt med å kun ha fire elementer
 - Oppgavens tittel
 - Veileder
 - Sammendrag
 - Pdf

Tittel og sammendrag fylles inn på den kanoniske måten, mens for veileder må du passe på at det fylles inn på følgende måte:
```
**Veileder:** [Gereon Quick]({{<ref "/veileder/gereon-quick">}}) 
```
Sammendraget burde være det samme sammendraget eller "abstract" du har i oppgaven din. Hvis den kun er på engelsk i oppgaven kan du oversette den dersom du ønsker dette. 

Den siste delen, altså kodeblokken
```
<iframe src="link" width="700" height="980" allow="autoplay"></iframe>
```
er den kodeblokken som viser frem pdfen på nettsiden. Dersom du har oppgaven din på ntnu.open kan du åpne filen, kopiere nettsideadressen og bytte ut ordet ''link'' i koden over med nettsideadressen. Altså noe slikt:
```
<iframe src="https://ntnuopen.ntnu.no/ntnu-xmlui/bitstream/handle/11250/2622842/no.ntnu%3ainspera%3a2452886.pdf?sequence=1&isAllowed=y" width="700" height="980" allow="autoplay"></iframe>
```
Dersom du har lagt oppgaven i en Google drive, så kopierer du linken og setter inn på samme måte. Mest sannsynlig vil siste del av Google drive linken være "/view", men sørg for å bytte ut dette med "/preview" når du har limt inn nettsideadressen i kodeblokken, altså noe slikt:
```
<iframe src="https://drive.google.com/file/d/1g0kyS0_3GzxuCHEbwgcsGewTtEoS1-WJ/preview" width="700" height="980" allow="autoplay"></iframe>
```

Dette burde være alt som trengs for å opprette en side på riktig måte i arkivet! Bra jobba :)

### Pull request

Neste skritt er å legge den nye .md filen din inn i det faktiske arkivet. Dette gjør du ved å opprette en pullrequest, altså på "vanlig Githubmåte". 

**Todo: Full inn mer info her...**
