+++
title =  "Denne nettsiden"
Summary = """\
    Her skriver jeg litt om prosessen med å lage denne nettsiden.\
    Den er laget ved hjelp av hugo og stylet med tailwindcss. Siden\
    publiseres til github pages. Kontaktskjemaet drives av et google-regneark.\
"""
github_url = "https://github.com/kongpottifar/kongpottifar.github.io"
+++

For en som ikke har veldig mye erfaring med html eller css var det å lage en
nettside noe som i beste fall virket som en affære med bratt læringskurve.
Tidligere forsøk på å lage noe noenlunde presentabelt i html har endt i tekst
og bilder akkurat der de ikke skulle være og en heller tvilsom
brukeropplevelse. Og mye frustrasjon. Jeg hadde imidlertid et behov for å lage
en side hvor jeg kunne presentere prosjektene mine for potensielle
arbeidsgivere, så det var bare å brette opp ermene.

Planen var å lage en statisk side som skulle publiseres på github pages. Valget
falt på rammeverket [hugo](https://gohugo.io) for å generere sidene. En fordel
med dette er at man kan  skrive innholdet i markdown. Etter å ha lest en del
positiv omtale av [tailwindcss](https://tailwindcss.com), tenkte jeg å prøve
det ut på dette prosjektet. Og det ble en absolutt behagelig opplevelse. Hugo
generer sidene utrolig kjapt, så man kan se endringene i nesten sanntid. Dette
gjør det til en lek å plassere elementer på siden med tailwind. Når siden skal
publiseres er det bare å pushe til github, og med github actions konfigurert
blir siden kompilert og publisert automatisk. 

Jeg ville også ha et kontaktskjema på siden. Det ble løst med å bruke et google app-script som oppdaterer et google-regneark.

