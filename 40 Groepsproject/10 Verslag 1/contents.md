# Deel 1: Analyse en Implementatie
Lees deze lijst met vragen goed door voor je aan de slag gaat. Lever je antwoorden (als .pdf) onderaan deze pagina in. **Eén submit per groep.**

**Deadline: maandag 17 mei**

Houd de volgende indeling aan voor het verslag. Zorg ervoor dat je verhaal in ieder geval de genoemde vragen beantwoordt.

### 1.0 Taakverdeling \[max 150 woorden\]
Wie doet wat?

Wees precies voor deze week en schets in grote lijnen de taakverdeling. Deel de groep bij voorkeur op in twee subgroepjes die beide een prototype-algoritme uitwerken. Bedenk dat er veel verschillende taken zijn: Er moet veel geschreven, geprogrammeerd en uitgezocht worden. Zorg ervoor dat het voor iedereen duidelijk is wie wat doet.


### 1.1 Beschrijving \[max 300 woorden\]

**(a)**
Hoe ziet de review data er uit? Welke features?

**(b)**
Hoe ziet de user data er uit? Welke features?

**(c)**
Hoe ziet de business data er uit? Welke features? Zijn er features die hetzelfde zijn voor alle businesses? Zijn er features die verschillen per business?

### 1.2 Visualisatie \[max 300 woorden\]

**(a)**
Hoe zijn de reviews verdeeld? Maak plots en leg ze uit.

**(b)**
Hoe zijn de features van de user data verdeeld? Maak plots en leg ze uit.

**(c)**
Hoe zijn de features van de business data verdeeld? Maak plots en leg ze uit.

### 1.3 Implementatie algoritmes \[max 1500 woorden\]
Beschrijf het algoritme. Documenteer voor elk algoritme het volgende:

**(a)**
Geef een kort intuitieve uitleg. Beantoord hierbij o.a.: Welke type algoritme is het (content based, collaborative filtering, iets heel anders...)? Welke aspecten (tabellen/features) van de data gebruikt het? Wat doet het algoritme ongeveer?
\[max 150 woorden\]

**(b)**
Geef een gedetaileerde beschrijving van het algoritme. Het liefst met peudocode. Je kan een voorbeeld vinden van pseudocode in deze uitleg van het K-nearest-neighbor algoritme: [knn](https://towardsdatascience.com/k-nearest-neighbours-introduction-to-machine-learning-algorithms-18e7ce3d802a). Dit is uiteraard niet jullie algoritme, maar geeft een idee van hoe goede pseudocode er uitziet.

Gebruik geen verwijzingen naar de programeertaal en/of libraries die je hebt gebruikt. Dit helpt de lezer niet bij het begrijpen van het algoritme.

De beschrijving van de algoritmes moet zodanig zijn dat een ervaren programmeur in staat is om het te implementeren.

**(c)**
Wat zijn technische moeilijkheden om rekening mee te houden? Gebruikt je algorithme bijhvoorbeeld features die niet altijd aanwezig zijn? Of, gebruik je bijvoorbeeld je NLP technieken gebruiken die niet altijd betrouwbaar zijn?

**(d)**
Zijn er randgevallen waar je rekening mee moet houden? In welke stappen van de bovenstaande pseudode is dat? Hoe los je die gevallen op?

**(e)**
Wat zijn de parameters van je algoritme? Hoe beïnvloeden deze parameters het algoritme? (Dit hoef je nu nog niet te testen, maar schrijf op wat je kan beredeneren.)

Bijvoorbeeld: "Dit algoritme heeft treshold X. Als ik deze treshold een hogere waarde geef dan gaat het aantal false negatives naar beneden, maar dit gaat ten koste van..., want..."

**(f)**
Waren er problemen met het implementeren?

Dus niet: "Ik vond het moeilijk om functie X te debuggen."
Maar wel: "Voor aanpak X was de data niet geschikt, want..., dus zijn we op aanpak Y overgestapt."


### 2.2 Evaluatie (projectie) \[max 600 woorden\]
Van welk algoritme verwacht je betere resultaten? Beargumenteer dit aan de hand van de volgende vragen. Dit mag heel kort zijn (in het volgende verslag ga je dit uitgebreider beschrijven).

**(a)**
Beschrijf hoe de verdeling van de data van invloed is op elke algoritme. Zouden bijvoorbeeld, een hogere dichtheid van ratings of bepaalde features tot beter performance kunnen leiden?

**(b)**
Zijn er specifieke subsets (e.g., steden, bedrijfcategoriën, gebruikerprofielen, etc..) waarvoor je verwacht dat een van je algoritmes beter (of juist slechter) werkt?

**(c)**
Voor je content based algoritme, welke features denk je dat het nuttigste kunnen zijn? Waarom?

**(d)**
Hoe ga je testen of het werkt? Welke evaluatietechnieken ga je gebruiken? Hoe sluiten die aan bij de doelen van Yelp ([/groepsproject#doel](lees die nog even goed na))?

**(e)**
Zijn er dingen die je zou willen testen maar waarbij het testen om technische/praktische redenen niet mogelijk is?

## Submit

Lever hier je verslag in. Zet de namen van alle groepsleden op het verslag. Laat één persoon uit de groep het document inleveren namens de hele groep.
