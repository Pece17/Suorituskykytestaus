# Mallipohja testiskenaariot ja testitapaukset


## Sis�llys

(Lis�� sis�llys.)


## Testauksen kohde

(Lyhyt kuvaus testattavasta j�rjestelm�st� ja toteutettavasta testauksesta.)


## Testiskenaariot

(Esimerkit testiskenaarioista � korvaa n�m� testattavan palvelun tiedoilla.)


### Koestus

| Nimi | Projektinimi_Koestus |
|-|-|
| Testityyppi | Koestus |
| Tarkoitus | Varmistetaan skriptien, testidatan ja testiymp�rist�n toimivuus |
| Asetukset | (Esimerkki Koestuksesta.)<br><br>- Loadgeneraattorit = ?<br>- Virtuaalik�ytt�j�t = ?<br>- K�ytt�j�n lis�ys = ?<br>- Ramp Up = ?<br>- Think Time = ?<br>- Pacing = ?<br>- Stage Duration = ?<br>- Ramp Down = ? |
| Testiskenaarion kuva | (Lis�� t�h�n graafi testiskenaariosta.) |
| Kokonaiskesto, arvioitu | ? |
| K�ytt�j�ryhm�(t) | (Lis�� t�h�n ryhm�t, joihin virtuaalik�ytt�ji� voidaan jakaa testitapauksien sis�ll� tai v�lill�.) |
| Lis�tietoja | Varsinaisia testiskenaarioita edelt�v� koestus. Voidaan k�ytt�� my�s j�rjestelm�n l�mmittelyyn esim. uudelleenk�ynnistyksen j�lkeen. |


### Kuormitustestaus

| Nimi | Projektinimi_Kuormitus |
|-|-|
| Testityyppi | Kuormitustestaus |
| Tarkoitus | Testataan j�rjestelm�� k�ytt�en odotetun mukaista k�ytt�kuormaa<br><br>(T�h�n kohtaan voi tarkentaa testin tavoitetta.)<br><br>Tavoite:<br><br>- Web-k�ytt�liittym� = ? sivupyynt��/s<br>- WS-rajapinta = ? kutsua/s |
| Asetukset | (Esimerkki Kuormitustestauksesta.)<br><br>Loadgeneraattorit = ?<br>- Virtuaalik�ytt�j�t = ?<br>- K�ytt�j�n lis�ys = ?<br>- Ramp Up = ?<br>- Think Time = ?<br>- Pacing = ?<br>- Stage Duration = ?<br>- Ramp Down = ? |
| Testiskenaarion kuva | (Lis�� t�h�n graafi testiskenaariosta.) |
| Kokonaiskesto, arvioitu | ? |
| K�ytt�j�ryhm�(t) | (Lis�� t�h�n ryhm�t, joihin virtuaalik�ytt�ji� voidaan jakaa testitapauksien sis�ll� tai v�lill�.) |
| Lis�tietoja | Kuormitetaan palvelua tuotannonkaltaisella kuormalla. Mik�li testauksessa ilmenee ongelmia, ne selvitet��n ennen jatkamista isompiin kuormiin. |


### Rasitustestaus

| Nimi | Projektinimi_Rasitus |
|-|-|
| Testityyppi | Rasitustestaus |
| Tarkoitus | Testataan j�rjestelm�� k�ytt�en odotettua k�ytt�j�m��r�� paljon suurempaa kuormaa<br><br>(T�h�n kohtaan voi tarkentaa testin tavoitetta.)<br><br>Tavoite:<br><br>- Web-k�ytt�liittym� = ? sivupyynt��/s<br>- WS-rajapinta = ? kutsua/s |
| Asetukset | (Esimerkki Rasitustestauksesta.)<br><br>Loadgeneraattorit = ?<br>- Virtuaalik�ytt�j�t = ?<br>- K�ytt�j�n lis�ys = ?<br>- Ramp Up = ?<br>- Think Time = ?<br>- Pacing = ?<br>- Stage Duration = ?<br>- Ramp Down = ? |
| Testiskenaarion kuva | (Lis�� t�h�n graafi testiskenaariosta.) |
| Kokonaiskesto, arvioitu | ? |
| K�ytt�j�ryhm�(t) | (Lis�� t�h�n ryhm�t, joihin virtuaalik�ytt�ji� voidaan jakaa testitapauksien sis�ll� tai v�lill�.) |
| Lis�tietoja | Kuormitetaan palvelua tuotantok�ytt�� suuremmalla kuormalla ongelmakohtien l�yt�miseksi. Mik�li testauksessa ilmenee ongelmia, ne selvitet��n ennen jatkamista isompiin kuormiin. |


### Kest�vyystestaus

| Nimi | Projektinimi_Kestavyys |
|-|-|
| Testityyppi | Kest�vyystestaus |
| Tarkoitus | Testataan j�rjestelm�� odotetun kaltaisella k�ytt�kuormalla pitk�n aikaa<br><br>(T�h�n kohtaan voi tarkentaa testin tavoitetta.)<br><br>Tavoite:<br><br>- Web-k�ytt�liittym� = ? sivupyynt��/s<br>- WS-rajapinta = ? kutsua/s |
| Asetukset | (Esimerkki Kest�vyystestauksesta.)<br><br>Loadgeneraattorit = ?<br>- Virtuaalik�ytt�j�t = ?<br>- K�ytt�j�n lis�ys = ?<br>- Ramp Up = ?<br>- Think Time = ?<br>- Pacing = ?<br>- Stage Duration = ?<br>- Ramp Down = ? |
| Testiskenaarion kuva | (Lis�� t�h�n graafi testiskenaariosta.) |
| Kokonaiskesto, arvioitu | ? |
| K�ytt�j�ryhm�(t) | (Lis�� t�h�n ryhm�t, joihin virtuaalik�ytt�ji� voidaan jakaa testitapauksien sis�ll� tai v�lill�.) |
| Lis�tietoja | Kuormitetaan palvelua tuotannonkaltaisella kuormalla pitk�n aikaa. Mik�li testauksessa ilmenee ongelmia, ne selvitet��n ennen jatkamista isompiin kuormiin. |


## Testitapaukset

(Testitapaukset kuvataan siten, ett� ne voidaan kuvauksen perusteella toteuttaa testiv�lineeseen ja k�ytt�� testitulosten tulkinnan apuna.

On huomioitava, ett� suorituskykytestauksen testitapauksella tarkoitetaan testiin valittua k�ytt�j�n teht�v�ketjua j�rjestelm�ss�. Valittu testitapaus ei v�ltt�m�tt� vastaa sis�ll�lt��n j�rjestelm�n kuvattuja testitapauksia, vaan se saattaa sis�lt�� yhden tai useamman j�rjestelm�n testitapauksen. T�st� syyst� testitapaukset kuvataan tarkasti t�h�n dokumenttiin. Mik�li voidaan k�ytt�� jo olemassa olevia testitapauskuvauksia, riitt�� maininta k�ytetyst� testitapauskuvauksesta, ja sen versiosta.

Testiskenaariot ja testitapaukset -dokumentti on tarpeen niin vaatiessa p�ivittyv� lopputuote. Jokaisen suorituskykytestikierroksen kohdalla on tarkasteltava sen p�ivitystarve.)


### Testien aloituskohdan URL

- https://testattavanpalvelunlinkki.fi

(Esimerkit testitapauksista, korvaa n�m� testattavan palvelun tiedoilla.)

| Testitapaus | Testauksen kohde | Tiedostonimi | Kuvaus | URL / Kommentti |
|-|-|-|-|-|
| TT001 |  |  |  |  |
| TT002 |  |  |  |  |
| TT003 |  |  |  |  |
| TT004 |  |  |  |  |