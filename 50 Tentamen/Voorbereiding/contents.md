# Tentamen

Het tentamen vindt plaats op donderdag 29 april. Het gaat om een take-home tentamen. Het tentamen zal om 15:00 uur worden verzonden. En je moet je antwoorden uiterlijk om 17:00 inleveren.

Je zal het tentmaen vanaf precies 14:55 hier kunnen downloaden.

De stof voor het tentamen bestaat uit alles wat je tot nu toe voor dit vak hebt geleerd:

- De inhoud van de opdrachten die je hebt gemaakt. Kijk vooral goed de open vragen uit deze opdrachten nog eens door!
- De bijbehorende instructievideo's:
    - [Introductie](/lectures/introductie)
    - [Collaborative Filtering (deel 1/2)](/lectures/collaborative-filtering-1)
    - [Collaborative Filtering (deel 2/2)](/lectures/collaborative-filtering-2)
    - [Evaluatie](/lectures/evaluatie)
- De gastcolleges:
    - [Daan Odijk](/lectures/daan-odijk)
    - [Anne Schuth](/lectures/anne schuth)
    - [David Graus](/lectures/david-graus-2021)
    - [Brammert Ottens](/lectures/brammert-ottens-2021)
    - [Felicia Loacherbach](/lectures/felicia-loecherbach-2021)

# Voorbeeldvragen
Het tentamen bestaat enkel uit vragen over concepten, waarbij we jouw inzicht in de materie testen. Er is geen code op het tentamen. Je zult daarom pandas, DataFrames en Series ook niet tegenkomen.

Je zal voor dit tentament twee praktijk voorbeelden gaan bespreken. Je gaat voor die praktijk voorbeelden bespreken hoe je daar een recommender system voor zou kunnen maken en waar je aan moet denken als je dat doet. Het doel is dat je laat zien dat je de kennis die je hebt opgedaan kan toepassen op een nieuw situatie.

Je haalt een voldoende voor het tentamen als je laat zien dat je de relevante informatie uit de colleges en opdrachten weet te gebruiken in je antwoorden, en onwaarheden en irrelevante zijsporen weet te vermijden.

## Voorbeeld

Neem bijvoorbeeld de data van een boekwinkel. Deze bevat twee tabellen:

De eerste tabel is *books.csv*, een tablel met 10.000 boeken. Dit zijn de eerste 5 rijen:

 id  | book_id | books_count | isbn      | authors                     | original_publication_year | title                                                    | language_code | average_rating | ratings_count |
|-----|---------|-------------|-----------|-----------------------------|---------------------------|----------------------------------------------------------|---------------|----------------|---------------|
|   1 | 2767052 |         272 | 439023483 | Suzanne Collins             |                      2008 | The Hunger Games (The Hunger Games, #1)                  | eng           |           4.34 |       4780653 |
|   2 |       3 |         491 | 439554934 | J.K. Rowling, Mary GrandPré |                      1997 | Harry Potter and the Sorcerer's Stone (Harry Potter, #1) | eng           |           4.44 |       4602479 |
|   3 |   41865 |         226 | 316015849 | Stephenie Meyer             |                      2005 | Twilight (Twilight, #1)                                  | en-US         |           3.57 |       3866839 |
|   4 |    2657 |         487 |  61120081 | Harper Lee                  |                      1960 | To Kill a Mockingbird                                    | eng           |           4.25 |       3198671 |
|   5 |    4671 |        1356 | 743273567 | F. Scott Fitzgerald         |                      1925 | The Great Gatsby                                         | eng           |           3.89 |       2683664 |
| ... | ...     | ...         | ...       | ...                         | ...                       | ...                                                      | ...           | ...            | ...           |
|     |         |             |           |                             |                           |                                                          |               |                |               |

De tweede tabel is *ratings.csv*, een tablel met 980.000 ratings. Dit zijn de eerste 5 rijen:

| book_id | user_id | rating |
|---------|---------|--------|
|       1 |     314 |      5 |
|       1 |     439 |      3 |
|       1 |     588 |      5 |
|       1 |    1169 |      4 |
|       1 |    1185 |      4 |
| ...     | ...     | ...    |


Beschrijf aan de hand van een aantal vragen hoe je hier een recommender system van zou kunnen maken:

- Hoe zou je een *collaborative filtering* recommender system kunnen maken voor deze data? Geef hierbij genoeg technisch detail:
    - Leg voor elke feature in de tabel uit in hoeverre de deze uit de data bruikbaar is voor zo'n systeem.
        - Leg uit of bepaalde features nog voorbewerkt moeten worden voordat ze bruikbaar zijn.
        - Leg uit welke similarity maat (of maten) je zou gebruiken.
        - Leg uit hoe het systeem uiteindelijk aan de hand van voorspelde rating aan een aanbeveling komt.
    - Hoe zou je een *content-based* recommender system kunnen maken voor deze data? Geef ook hier weer genoeg technisch detail:
        - Leg voor elke feauture in de tabel uit in hoeverre de features uit de data bruikbaar zijn voor zo'n systeem.
        - Leg uit of bepaalde features nog voorbewerkt moeten worden voordat ze bruikbaar zijn.
        - Leg uit welk soort algoritme je gebruikt om tot een aanbeveling te komen.
        - Leg uit, indien van toepassing, welke similarity maat (of maten) je zou gebruiken.
    - Van welke methode verwacht je dat betere voorspellingen, collaborative filtering of content-based filtering?

Naast dit type vragen kan je ook nog een aantal vragen verwachten over de gastcolleges.
