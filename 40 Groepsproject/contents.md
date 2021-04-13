# Groepsopdracht

## Doel

Yelp gaat een persoonlijke landingspagina maken voor ingelogde gebruikers. Op deze pagina wil Yelp een lijst met 20 aanbevelingen zetten. Het doel van Yelp is eenvoudig: gebruikers bij zich houden. Yelp weet uit ervaring dat goede aanbevelingen daarbij kunnen helpen. Mits ze aan twee eigenschappen voldoen:

- Je moet bedrijven aanbevelen die de gebruiker daadwerkelijk interesant vindt.
- Je moet een gevariëerd aanbod aanbevelen (dus, bijvoorbeeld, niet alléén maar 20 doe-het-zelf zaken, of 20 verschillende filialen van dezelfde hamburgerketen).

Jullie doel is onderzoeken welke strategiën hiervoor het meest geschikt zijn. Je gaat verschillende prototype recommender systems bouwen en testen welke aanpak het beste werkt. Hiervoor ga je gebruik maken van een bestaande Yelp dataset.

## Dataset

De dataset staat hier beschreven:

[Yelp dataset documentatie](https://www.yelp.com/dataset/documentation/main)

Deze dataset is enorm. Om het iets behapbaarder te maken hebben we een variant van de dataset gegenereerd waarin we de data per stad hebben opgesplitst. Je kan je met deze data dus in eerste instantie focussen op een kleinere stad voor je het voor de hele wereld gaat testen. Je kan deze set hier downloaden:

[Yelp opgesplitste dataset download (4.5GB)](https://surfdrive.surf.nl/files/index.php/s/d9QtNlGNbYuUnpT/download)

## Opzet

Je gaat met je groep minstens twee verschillende algoritmes uitproberen. Het handigste is om je groepje op te splitsen in twee subgroepen die beide een algoritme implementeren (je moet elkaar daarbij wel helpen natuurlijk).

Je bent heel vrij in de concrete invulling. Er zijn wel een paar minimale eisen waaraan je project moet voldoen:

- Minstens één van de twee algoritmes moet een content-based filtering algoritme zijn.
- Je moet minstens 2 verschillende evaluatiematen gebruiken voor het vergelijken van de algoritmes.
- Er moet één techniek zijn die we nog niet gebruikt hebben bij de opdrachten. Dit kan van alles zijn. Bijvoorbeeld:
    - Een similarity-maat die we nog niet hebben gebruikt.
    - Een evaluatiemaat die we nog niet hebben gezien.
    - Een ander soort algoritme (werken met clustering, matrix factorization, knn).
    - etc.

Het project bestaat uit twee fases:

- Fase 1 - Analyse & Implementatie: Hoe ziet de data er uit? Welke features heb je? Hoe zijn deze gecodeerd? Hoe zijn de reviews verdeeld? Hoe dicht is de data? Hoe goed verwacht je dat bepaalde algoritmes gaan werken? Vervolgens ga je de algoritmes uitprogrammeren.
- Fase 2 - Evaluatie: Welke algoritme werkt het beste? Voor welk deel van de data? Wat zijn de optimale parameters? Sluit dit aan bij je verwachtingen in de analyse? Waarom (niet)?

Voor beide fases schrijf je een kort verslag en geef je een korte presentatie van maximaal 15 minuten waarin je laat zien wat je gedaan hebt. **Voor elk verslag krijg je een [concrete lijst met vragen](#verslagen) die je moet beantwoorden. Kijk daar dus eerst goed naar voor je aan de slag gaat met programmeren.**

Je hebt effectief maar twee weken hiervoor, dus we hanteren een strakke planning.

## Organisatie

- In beide weken is er een deadline voor een deelverslag.
- Iedere groep wordt ingedeeld bij een eigen tutor. Deze tutor kan je helpen met het voorgeven van het project. **Je wordt verwacht minstens één keer per week een half uur met je tutor af te spreken.** Zelfs als je geen concrete vragen hebt.
- Er zijn twee presentaties: een tussenpresentatie en eindpresentatie. Hierin laat je aan ons (de doceent en je tutor) en een paar ander groepjes zien wat je de respectievelijke fases hebt gedaan.

## Beoordeling

Je cijfer wordt gevormd op basis van:

- de twee verslagen
- de eindpresentatie

Verder verwachten we dat je:

- elke week minstens één keer een half uur met je tutor afspreekt (waarbij iedereen uit de groep aanwezig is)
- een tussenpresentatie hebt gegeven
- aan het einde van het project de code inlevert (dit is alleen ter verificatie, hier wordt je niet op beoordeeld)

Je krijgt als groep een gezamelijk cijfer. We verwachten dat iedereen een gelijkwaardige bijdrage levert.

## Planning

Het schema voor de laatste 3 weken ziet er als volg uit:

|                         |     | ma                            | di                  | wo                      | do          | vr                          |
| ----------------------- | --- | ----------------------------- | ------------------- | ----------------------- | ----------- | --------------------------- |
| week 16, 19 - 23 april | [Teams maken](/groepsproject/verslag-1)| ||||| **deadline team-aanmelding**|
| ... |||||||
| ... |||||||
| week 19, 10 - 14 mei    | Fase 1 - Analyse & Implementatie](/groepsproject/verslag-1) |                              |         |     |               | |
| week 20, 17 - 21 mei    | Fase 2 - Evaluatie](/groepsproject/verslag-1) | **deadline verslag deel 1**  | tussenpresentaties | tussenpresentaties |  | **deadline verslag deel 2** |
| week 21, 24 - 28 mei    |     |                               | eindpresentaties    |                         |             | eindpresentaties            |

De laatste week is alleen gereserveerd voor eindpresentaties. Hierin kan je niet meer werken aan het project. Dit moet vrijdag 21 mei ingeleverd zijn.
<!-- Voor de tussenbesprekingen en eindpresentaties krijg je een link waarmee je zelf een geschikt moment kan inplannen. Voor het plannen van de meetings met de assistent kan je Ed gebruiken. -->

## Verslagen

- [Teams maken](/groepsproject/verslag-1)
- [Fase 1](/groepsproject/verslag-1)
- [Fase 2](/groepsproject/verslag-2)
<!-- - [Verslag deel 2](/groepsproject/verslag-2) -->
