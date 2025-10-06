# Mallipohja testiskenaariot ja testitapaukset


## Sisällys

(Lisää sisällys.)


## Testauksen kohde

(Lyhyt kuvaus testattavasta järjestelmästä ja toteutettavasta testauksesta.)


## Testiskenaariot

(Esimerkit testiskenaarioista – korvaa nämä testattavan palvelun tiedoilla.)


### Koestus

| Nimi | Projektinimi_Koestus |
|-|-|
| Testityyppi | Koestus |
| Tarkoitus | Varmistetaan skriptien, testidatan ja testiympäristön toimivuus |
| Asetukset | (Esimerkki Koestuksesta.)<br><br>- Loadgeneraattorit = ?<br>- Virtuaalikäyttäjät = ?<br>- Käyttäjän lisäys = ?<br>- Ramp Up = ?<br>- Think Time = ?<br>- Pacing = ?<br>- Stage Duration = ?<br>- Ramp Down = ? |
| Testiskenaarion kuva | (Lisää tähän graafi testiskenaariosta.) |
| Kokonaiskesto, arvioitu | ? |
| Käyttäjäryhmä(t) | (Lisää tähän ryhmät, joihin virtuaalikäyttäjiä voidaan jakaa testitapauksien sisällä tai välillä.) |
| Lisätietoja | Varsinaisia testiskenaarioita edeltävä koestus. Voidaan käyttää myös järjestelmän lämmittelyyn esim. uudelleenkäynnistyksen jälkeen. |


### Kuormitustestaus

| Nimi | Projektinimi_Kuormitus |
|-|-|
| Testityyppi | Kuormitustestaus |
| Tarkoitus | Testataan järjestelmää käyttäen odotetun mukaista käyttökuormaa<br><br>(Tähän kohtaan voi tarkentaa testin tavoitetta.)<br><br>Tavoite:<br><br>- Web-käyttöliittymä = ? sivupyyntöä/s<br>- WS-rajapinta = ? kutsua/s |
| Asetukset | (Esimerkki Kuormitustestauksesta.)<br><br>Loadgeneraattorit = ?<br>- Virtuaalikäyttäjät = ?<br>- Käyttäjän lisäys = ?<br>- Ramp Up = ?<br>- Think Time = ?<br>- Pacing = ?<br>- Stage Duration = ?<br>- Ramp Down = ? |
| Testiskenaarion kuva | (Lisää tähän graafi testiskenaariosta.) |
| Kokonaiskesto, arvioitu | ? |
| Käyttäjäryhmä(t) | (Lisää tähän ryhmät, joihin virtuaalikäyttäjiä voidaan jakaa testitapauksien sisällä tai välillä.) |
| Lisätietoja | Kuormitetaan palvelua tuotannonkaltaisella kuormalla. Mikäli testauksessa ilmenee ongelmia, ne selvitetään ennen jatkamista isompiin kuormiin. |


### Rasitustestaus

| Nimi | Projektinimi_Rasitus |
|-|-|
| Testityyppi | Rasitustestaus |
| Tarkoitus | Testataan järjestelmää käyttäen odotettua käyttäjämäärää paljon suurempaa kuormaa<br><br>(Tähän kohtaan voi tarkentaa testin tavoitetta.)<br><br>Tavoite:<br><br>- Web-käyttöliittymä = ? sivupyyntöä/s<br>- WS-rajapinta = ? kutsua/s |
| Asetukset | (Esimerkki Rasitustestauksesta.)<br><br>Loadgeneraattorit = ?<br>- Virtuaalikäyttäjät = ?<br>- Käyttäjän lisäys = ?<br>- Ramp Up = ?<br>- Think Time = ?<br>- Pacing = ?<br>- Stage Duration = ?<br>- Ramp Down = ? |
| Testiskenaarion kuva | (Lisää tähän graafi testiskenaariosta.) |
| Kokonaiskesto, arvioitu | ? |
| Käyttäjäryhmä(t) | (Lisää tähän ryhmät, joihin virtuaalikäyttäjiä voidaan jakaa testitapauksien sisällä tai välillä.) |
| Lisätietoja | Kuormitetaan palvelua tuotantokäyttöä suuremmalla kuormalla ongelmakohtien löytämiseksi. Mikäli testauksessa ilmenee ongelmia, ne selvitetään ennen jatkamista isompiin kuormiin. |


### Kestävyystestaus

| Nimi | Projektinimi_Kestavyys |
|-|-|
| Testityyppi | Kestävyystestaus |
| Tarkoitus | Testataan järjestelmää odotetun kaltaisella käyttökuormalla pitkän aikaa<br><br>(Tähän kohtaan voi tarkentaa testin tavoitetta.)<br><br>Tavoite:<br><br>- Web-käyttöliittymä = ? sivupyyntöä/s<br>- WS-rajapinta = ? kutsua/s |
| Asetukset | (Esimerkki Kestävyystestauksesta.)<br><br>Loadgeneraattorit = ?<br>- Virtuaalikäyttäjät = ?<br>- Käyttäjän lisäys = ?<br>- Ramp Up = ?<br>- Think Time = ?<br>- Pacing = ?<br>- Stage Duration = ?<br>- Ramp Down = ? |
| Testiskenaarion kuva | (Lisää tähän graafi testiskenaariosta.) |
| Kokonaiskesto, arvioitu | ? |
| Käyttäjäryhmä(t) | (Lisää tähän ryhmät, joihin virtuaalikäyttäjiä voidaan jakaa testitapauksien sisällä tai välillä.) |
| Lisätietoja | Kuormitetaan palvelua tuotannonkaltaisella kuormalla pitkän aikaa. Mikäli testauksessa ilmenee ongelmia, ne selvitetään ennen jatkamista isompiin kuormiin. |


## Testitapaukset

(Testitapaukset kuvataan siten, että ne voidaan kuvauksen perusteella toteuttaa testivälineeseen ja käyttää testitulosten tulkinnan apuna.

On huomioitava, että suorituskykytestauksen testitapauksella tarkoitetaan testiin valittua käyttäjän tehtäväketjua järjestelmässä. Valittu testitapaus ei välttämättä vastaa sisällöltään järjestelmän kuvattuja testitapauksia, vaan se saattaa sisältää yhden tai useamman järjestelmän testitapauksen. Tästä syystä testitapaukset kuvataan tarkasti tähän dokumenttiin. Mikäli voidaan käyttää jo olemassa olevia testitapauskuvauksia, riittää maininta käytetystä testitapauskuvauksesta, ja sen versiosta.

Testiskenaariot ja testitapaukset -dokumentti on tarpeen niin vaatiessa päivittyvä lopputuote. Jokaisen suorituskykytestikierroksen kohdalla on tarkasteltava sen päivitystarve.)


### Testien aloituskohdan URL

- https://testattavanpalvelunlinkki.fi

(Esimerkit testitapauksista, korvaa nämä testattavan palvelun tiedoilla.)

| Testitapaus | Testauksen kohde | Tiedostonimi | Kuvaus | URL / Kommentti |
|-|-|-|-|-|
| TT001 |  |  |  |  |
| TT002 |  |  |  |  |
| TT003 |  |  |  |  |
| TT004 |  |  |  |  |