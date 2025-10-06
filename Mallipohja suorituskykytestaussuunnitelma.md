# Mallipohja suorituskykytestaussuunnitelma

(Tämän mallipohjan voi kopioida projektin suorituskykytestaussuunnitelmaa tehdessä.)


## Testausvastaavat

- (Vastuuhenkilö)
- (Vastuuhenkilö)
- ...


## Linkit

(Kirjaa linkit ja korvaa placeholder-tekstit projektiin liittyvillä linkeillä.)

- Mallipohja testiskenaariot ja testitapaukset
- Suorituskykytestauksen palvelukuvaus
- Suorituskykytestauksen terminologia
- Järjestelmän yleiskuvaus / Palvelukuvaus
- Ympäristön arkkitehtuurikuvaus

(Mallissa olevat otsikot tulee muistaa käsitellä! Muista myös päivittää sisällysluettelo.)

(Toimittaessa ulkopuolisen toimijan kanssa tulee miettiä erikseen ko. testausprojektin kannalta esille tuotavia asioita (vastuut, dokumenttien sijainnit). Kirjaa dokumentteihin suojaus-taso.)


## Sisällys

(Tee sisällys.)


## Johdanto

Tässä dokumentissa kuvataan (testauksen kohde) tehtävän suorituskykytestauksen suunnitelma.

(Kerro tässä lyhyesti yleisellä tasolla taustatietoa testauksen kohteena olevasta järjestelmästä/sovelluksesta, testauksen syistä ja tavoitteista.)


## Suorituskykytestauksen yhteyshenkilöt

| Rooli | Vastuualue | Yhteyshenkilö |
|-|-|-|
| (Tilaaja, esim. projektipäällikkö) | (Liiketoiminnan edustaja) |  |
| (Tekninen projektipäällikkö) | (ICT-vastaava) |  |
| (Testausvastaava) | (Systeemitestaus) |  |
| (Suorituskykytestaaja) | (Testien suunnittelu ja toteutus) |  |
| (ICT-asiantuntija) | (Tietokanta) |  |
| (ICT-asiantuntija) | (Palvelimet) |  |
| (ICT-asiantuntija) | (Tietoliikenne) |  |
| (ICT-asiantuntija) | (Levylaitteet) |  |
| (ICT-asiantuntija) | (VMware) |  |


## Tehtävät ja aikataulut


### Raportointikäytännöt

Suorituskykytestaukseen käytetyt tunnit raportoidaan projektille: (Kirjaa tähän tunnus ja tehtävä.)


### Dokumentointi

Suorituskykytestaukseen liittyvä dokumentaatio on talletettu (minne?).

(Tai linkki toiseen, esim. projektin työtilaan, mikäli käytetään sitä.)


### Versiohallinta

Suorituskykytestausprojektin testausohjelmiston tiedostot talletetaan Suorituskykytestauksen versiohallintaan (tai jonnekin muualle).


### Aikataulu

| Tehtävät | Päivämäärät |
|-|-|
| 1. Aloituspalaveri tilaajan kanssa |  |
| 2. Testauksen suunnittelu sekä testidatan ja -ympäristön valmistelu |  |
| 3. Testien kehitys |  |
| 4. Testaukset |  |
| 5. Tulosten analysointi ja raportointi |  |


## Testauskohteet

Suorituskykytestauksen kohteena on (järjestelmän nimi/palvelu).


### Testauksen tavoite

(Esitä lyhyt yhteenveto tärkeimmistä tavoitteista.)

Testauksen tavoitteena on selvittää, millaisia kyselymääriä järjestelmä pystyy tällä hetkellä käsittelemään siten, että toimintojen vasteajat pysyvät kohtuullisina.

Testauksella selvitetään myös palvelun pullonkauloja ja analysoidaan nykykapasiteetin riittävyyttä oletettuja tuotannon kyselymääriä vasten.


### Ympäristö


#### Yleiskuvaus

(Järjestelmän kuvaus: missä ympäristössä testataan, mitä sovelluksia, komponentteja, yhteyksiä mukana. Jos testausympäristö poikkeaa lopullisesta tuotantoympäristöstä, kuvaa erot mahdollisuuksien mukaan ja arvioi miten eroavaisuus vaikuttaa testitulosten tulkitsemiseen ja tehtäviin johtopäätöksiin.)


#### Järjestelmäkuvaus

(Kuva ja selvitys järjestelmäympäristöstä ja testauksen kohteesta, tai esim. viittaus arkkitehtuuridokumenttiin.)


#### Testauksen kohteena olevat palvelimet ja niiden valvonta

(Listaa palvelimet, joihin testi kohdistuu ja niistä valvottavat asiat.)


### Rajaukset ja rajoitteet

(Kuvaa testiympäristöön tai testaukseen liittyviä rajauksia tai rajoitteita (esim. puuttuva integraatio toiseen järjestelmään), jotka on hyvä huomioida testien toteutuksessa tai tulosten tulkinnassa.)


## Testauksen toteutus


### Palvelukuvaus

Suorituskykytestauspalvelun sisältö on kuvattu erillisessä Suorituskykytestauksen palvelukuvauksessa.


### Testaustyypit

Suorituskykytestauksen yleiset käytettävät testaustyypit on kuvattu erillisessä Suorituskykytestauksen palvelukuvauksessa.

| Testaustyyppi | Valittu testaukseen (X) |
|-|-|
| Kuormitustestaus | X |
| Rasitustestaus |  |
| Kestävyystestaus |  |
| Virhetilannetestaus |  |


## Käyttäjämäärät ja suorituskykyvaatimukset


### Käyttäjämäärät


#### Järjestelmän käyttäjämäärä ja käyttäjäprofiilit

(Kuvaa järjestelmän käyttäjämäärä sillä tasolla kun se on tiedossa. Uudesta järjestelmästä kuvaa arvio tulevasta tuotantokuormasta. Kuvaa käyttäjäprofiilit yleisellä tasolla.

Avustavia kysymyksiä:

- Mikä on järjestelmän käyttö-/palveluaika (esim. klo 8–16 tai 24/7)?
- Paljonko järjestelmällä on käyttäjiä (yhteensä ja yhtäaikaisia, jos tiedossa)?
- Millaisia käyttäjäryhmiä järjestelmällä on?
- Käyttäjäryhmien prosenttiosuudet?
- Mitä tietoa käyttäjien käyttäytymisestä on saatavilla (esim. think timet, sivulatausmäärät)?
- Mikä on järjestelmän keskimääräinen kuorma/h?
- Millaisia ruuhkahuippuja (kuorma/h) on tiedossa/oletettavissa?)


### Suorituskykyvaatimukset

(Kuvaa järjestelmälle asetetut suorituskykyvaatimukset. Tilaajan / järjestelmän omistajan tulee määritellä vaatimukset. Mikäli suorituskykyvaatimukset on kuvattu erillisessä dokumentissa, voit viitata ko. dokumenttiin.

Avustavia kysymyksiä:

- Millaisia vaatimuksia suorituskyvylle on?
- Kuinka monta yhtäaikaista käyttäjää sovelluksen tulisi pystyä palvelemaan / kuinka monta sivulatausta esim. tunnissa?
- Vasteaikavaatimukset?
- Mikäli sovellus on tuotannossa, onko valvontadataa nykykäytöstä (käyttäjäprofiilit ja latausmäärät))


#### Testeissä käytettävät kuormat

(Kuvaa testeissä käytettävät kuormat edellisten tietojen pohjalta. Valittuun kuormaan vaikuttavat järjestelmän arvioitu tuotantokuorma ja oletettavat ruuhkahuiput. Keskeisiä elementtejä ovat valittu virtuaalinen käyttäjämäärä ja käyttäjän odotteluajat (think timet), jotta haluttu kuorma saavutetaan.

Avustavia kysymyksiä:

- Millaisia tavoitteita testeille on (esim. ruuhkahuippujen testaus, kriisitilanteet, maksimi-kuormankesto yms.)
- Millaista kuormaa järjestelmän tulisi kestää?
- Onko nähtävissä, että käyttäjämäärä tulee kasvamaan jatkossa?)

Testeissä käytettävät kuormat löytyvät sivulta/dokumentista Mallipohja testiskenaariot ja testitapaukset.


## Testitapaukset


### Testitapaukset

(Kuvaa päätasolla testiin valittavat testitapaukset. Pyri valitsemaan riittävän yksinkertaiset, järjestelmän todellista käyttöä edustavat testitapaukset (esim. yleisimmät testitapaukset, riittävällä testidatalla varioituna). Testauksen tavoite määrittelee valittavat testitapaukset.)

Testitapaukset löytyvät sivulta/dokumentista Mallipohja testiskenaariot ja testitapaukset.


### Testidata

(Kuvaa päätasolla tarvittava testidata. Esim. millaista testidataa tarvitaan ja kuinka paljon: käyttäjätunnukset, haettava / syötettävä data.)

