# Groepsopdracht

## Doel

Yelp gaat een persoonlijke landingspagina maken voor ingelogde gebruikers. Op deze pagina wil Yelp een lijst met 20 aanbevelingen zetten. Het doel van Yelp is eenvoudig: gebruikers bij zich houden. Yelp weet uit ervaring dat goede aanbevelingen daarbij kunnen helpen. Mits ze aan twee eigenschappen voldoen:

- Je moet bedrijven aanbevelen die de gebruiker daadwerkelijk interesant vindt.
- Je moet een gevariëerd aanbod aanbevelen (dus, bijvoorbeeld, niet alléén maar 20 doe-het-zelf zaken, of 20 verschillende filialen van dezelfde hamburgerketen).

Jullie doel is onderzoeken welke strategiën hiervoor het meest geschikt zijn. Je gaat verschillende prototype recommender systems bouwen en testen welke aanpak het beste werkt. Hiervoor ga je gebruik maken van een bestaande Yelp dataset.

## Dataset

De dataset staat hier beschreven:

[Yelp dataset documentatie](https://www.yelp.com/dataset/documentation/main)

Deze dataset is enorm. Om het iets behapbaarder te maken hebben we een variant van de dataset gegenereerd waarin we de data per stad hebben opgeslitst. Je kan je met deze data dus in eerste instantie focussen op een kleinere stad voor je het voor de hele wereld gaat testen. Je kan deze set hier downloaden:

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

Het project bestaat uit drie fases:

- Analyse: Hoe ziet de data er uit? Welke features heb je? Hoe zijn deze gecodeerd? Hoe zijn de reviews verdeeld? Hoe dicht is de data? Hoe goed verwacht je dat bepaalde algoritmes gaan werken?
- Implementatie: Hierin ga je de algoritmes uitprogrammeren.
- Evaluatie: Welke algoritme werkt het beste? Voor welk deel van de data? Wat zijn de optimale parameters? Sluit dit aan bij je verwachtingen in de analyse? Waarom (niet)?

Voor elke fase schrijf je een kort verslag en aan het einde van het project geef je een eindpresentatie van 15 minuten waarin je laat zien wat je gedaan hebt. **Voor elk verslag krijg je een [concrete lijst met vragen](#verslagen) die je moet beantwoorden. Kijk daar dus eerst goed naar voor je aan de slag gaat met programmeren.**

Je hebt effectief maar twee weken hiervoor (de eerste en laatste week zijn maar halve weken). Dit betekent dat je niet veel tijd hebt voor elke fase. Dus we hanteren een strakke planning.

## Organisatie

- Elke week is er een deadline voor een deelverslag.
- Iedere groep heeft wordt ingedeeld bij een eigen assistent. Deze assistent kan je helpen met technische problemen. **Je wordt verwacht minstens één keer per week een half uur met de assistent af te spreken.** Zelfs als je geen concrete vragen hebt.
- Er is een tussenbespreking met de docent voor het vak, waarin je laat zien wat je tot dan toe gedaan hebt.
- Er is een eindpresentatie. Dit is een kleinschalige presentatie. Hierin presenteer je met je groepje de conclusies aan de docent en je assistent.

## Beoordeling

Je cijfer wordt gevormd op basis van:

- de drie tussenverslagen
- de eindpresentatie

Verder verwachten we dat je:

- elke week minstens één keer een half uur met de assistent afspreekt (waarbij iedereen uit de groep aanwezig is)
- een tussenbespreking met de docent hebt gehad (waarbij iedereen uit de groep aanwezig is)
- aan het einde van het project de code inlevert (dit is alleen ter verificatie, hier wordt je niet op beoordeeld)

Je krijgt als groep een gezamelijk cijfer. We verwachten dat iedereen een gelijkwaardige bijdrage levert.

## Planning

Het schema voor de komende 3 weken ziet er als volg uit:

|                      | ma         | di                  | wo                      | do          | vr                      |
| -------------------- | ---------- | ------------------- | ----------------------- | ----------- | ----------------------- |
| deel 1 (6 - 8 mei)   | *geen les* | *geen les*          |                         |             | deadline verslag deel 1 |
| deel 2 (11 - 15 mei) |            | tussenbesprekingen  | tussenbesprekingen      |             | deadline verslag deel 2 |
| deel 3 (18 - 20 mei) |            | eindpresentaties    | eindpresentaties        | *geen les*  | *geen les*              |
|                      |            |                     | deadline verslag deel 3 |             |                         |

Voor de tussenbesprekingen en eindpresentaties krijg je een link waarmee je zelf een geschikt moment kan inplannen. Voor het plannen van de meetings met de assistent kan je Ed gebruiken.

## Verslagen

- [Verslag deel 1](/groepsproject/verslag-1)
- [Verslag deel 2](/groepsproject/verslag-2)
- [Verslag deel 3](/groepsproject/verslag-3)
