# Jaccard

### Correcte definitie Jaccard

Aan de hand van deze utility matrix kunnen we weer een similarity matrix maken. Dit kunnen we helaas niet doen met cosine similarity omdat deze features geen numerieke betekenis hebben. Het zijn _categorische features_: de nummers geven aan of de film onder een bepaalde categorie (genre) valt of niet. Voor het bepalen van similiarities voor catagorische data zijn er een legioen aan mogelijke maten$^1$. Voor deze opdracht gebruiken we de [**Jaccard index**](https://en.wikipedia.org/wiki/Jaccard_index). Dit is een veelgebruikte maat die goed werkt voor binaire data en die bovendien eenvoudig te implementeren is.

Om de Jaccard index voor twee films ($A$ en $B$) te bereken moeten we drie waardes bepalen:

- **M11**: Het aantal features dat in de matrix voor zowel film $A$ als $B$ een $1$ bevat. Oftewel, het aantal genres waarin $A$ en $B$ overlappen:
- **M10**: Het aantal features dat in de matrix voor alléén film $A$ een $1$ bevat. Oftewel, het aantal genres dat *wel* op $A$ van toepassing is en *niet* op $B$.
- **M01**: Het aantal features dat in de matrix voor alléén film $B$ een $1$ bevat.

De berekening van de Jaccard index is vervolgens:

$$
\textrm{jaccard}(A, B)=\frac{\textrm{M11}}{\textrm{M10} + \textrm{M01} + \textrm{M11}}
$$

Of in set-notatie (als je daar bekend mee bent):

$$
\textrm{jaccard}(A, B)=\frac{|A \cap B|}{|A \cup B|}
$$

> Let op: Als A en B geen genres bevatten is $${\textrm{M10} + \textrm{M01} + \textrm{M11}} = 0$$. In dat geval zou je een deling door 0 krijgen. Hier moet je kiezen wat je doet. Wij kiezen in dat geval voor $$\textrm{jaccard}(A, B)=NaN$$

<p style="font-size:9pt;">
    1: Voor een overzicht kan je even naar <a href="https://pdfs.semanticscholar.org/c654/4a12fec2097bddc49adbb159426d9dc15d2c.pdf">[Boriah 2007]</a> kijken. Dit paper is vrij technisch, er wordt niet van je verwacht dat je alle details begrijpt, maar het geeft in ieder geval een indruk van de mogelijkheden.
</p>

Dit is de meest gangbare deifnitie, en ook zoals deze in het Wikipedia-artikel staat.

### Oude definitie Jaccard (alternatieve interpretatie)

In de uitleg in de notebook staat:

$$
\textrm{jaccard}(A, B)=\frac{\textrm{M11}}{\textrm{M10} + \textrm{M01} - \textrm{M11}}
$$

**Dit is incorrect.** Maar, je kan de de definities van M10 en M01 aanpassen op zo'n manier dat het wel werkt:

- **M10**: Het aantal features dat in de matrix voor film $A$ een $1$ bevat. (En de waarde voor $B$ maakt niet uit.)
- **M01**: Het aantal features dat in de matrix voor film $B$ een $1$ bevat. (En de waarde voor $A$ maakt niet uit.)

Dus door M10 en M01 anders te definiëren klopt de definitie uit de notebook wel weer. Deze definitie is niet gangbaar, maar kan wel makkelijker zijn om te implementeren.
