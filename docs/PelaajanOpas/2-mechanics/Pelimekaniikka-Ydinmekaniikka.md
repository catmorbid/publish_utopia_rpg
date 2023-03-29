---
share: true
---
# Ydinmekaniikka

Kun pelaajat haluavat tehdä uhkarohkeita, tai vaikeita asioita, tai joutuvat tilanteisiin, joissa epäonnistumisella on merkittävä seuraukset, tai kohtaavat epätavallisia ongelmia, on yleistä, ratkaista ongelmatilanteet **Testillä**, jossa otetaan huomioon hahmon eri piirteet, sekä ripaus satunnaisuutta. Roolipeleissä yleisin menetelmä satunnaislukujen generointiin ovat **nopat**, ja näin se menee tässäkin pelissä. Yleisin pelissä käytetty *testi* on nimeltään **Taitotesti**, jossa siis testataan hahmon tilanteen vaatimaa taitoa. Esimerkiksi liikunnallinen toiminta voisi vaatia *Urheilu*-taidon testausta, mutta sosiaalinen tilanne puolestaan tarvitsisi *Vaikuttamista*.

Pelaaja ei yleisesti ottaen voi vaikuttaa siihen milloin noppia heitetään, tai mitkä piirteet testiin huomioidaan, vaan tämä kaikki Pelinjohtajan päätettävissä. Joskus tilanne voidaan ratkaista erilaisia taitoja tai kykyjä käyttäen, mutta tämä on aina pelinjohtajan päätettävissä.

## Nopat

Pelissä käytetään erilaisia noppia ratkaisemaan ongelmatilanteita. Tarvitset kohtalaisen läjän kaikkia niinsanottuja standardi noppia.

**10-sivuiset nopat**, eli **d10** ovat yleisimpiä pelissä käytettyjä noppia, sillä niitä käytetään pääasiassa erilaisten **testien** ratkomiseen.

Lisäksi on 12-sivuisia (**d12**), 8-sivuisia (**d8**), 6-sivuisia (**d6**) ja neljäsivuisia (**d4**) noppia, jotka kuuluvat vakiokalustoon.

3-sivuisen nopan (**d3**) saat heittämällä d6, ja lukemalla tuloksen seuraavasti:

| D6  | D3 Lukema |
| --- | --------- |
| 1-2 | 1         |
| 3-4 | 2         |
| 5-6 | 3         |

2-sivuisia noppia (**d2**) saat heittämällä mitä tahansa normaalia noppaa:
- pariton luku = 1
- parillinen luku = 2.

## Taitotestit

Useimmiten ratkaisutapa on **Taitotesti**, jossa siis testataan *hahmon* taitoa pelitilanteesta riippuvaan vaikeusasteeseen nähden. Pelaaja ottaa yhtä monta **10-sivuista noppaa (d10)**, kuin hänen asiaankuuluva **Taitonsa**, ja heittää kaikki nopat samalla kertaa. Nopat viskottuaan, pelaaja valitsee suurimman noppatuloksen, ja lisää tähän lukemaan tilanteeseen sopivan **Kyvyn** osoittaman lukeman.

Jos jokin nopista näyttää `0`, niin noppa on **Kriittinen Noppa**, ja sen seurauksensa se **räjähtää:** Tällöin heität nopan uudestaan, ja lisäät lukuun 10, ja jos heität vielä uuden kriittisen, niin noppa räjähtää uudestaan. Jos onnistut Kriittisellä nopalla, niin toiminto on [[#Kriittinen onnistuminen]].

**Esimerkkejä räjähtävistä nopista**
- Heität 3, 10 ja 8. 10 räjähtää, heität 5. Tulos on 3, 15 ja 8.
- Heitä 8, 10, 10, 3. Heität kympit uudestaan ja saat 10 ja 3. Heität uudestaan ja saat 7. Lopputulos on 8, 27, 13, 3.

Tähän päälle voidaan lätkiä erilaisia **olosuhdemuuttujia**, eli tilannekohtaisia **etuja** ja **haittoja**, tai esim. hahmon varusteista suotavia etuja.

Jos pelaajalla ei ole taitoa laisinkaan, pelinjohtaja voi joko todeta, että hommaa menee pieleen, tai antaa pelaajan heittää kahta noppaa, josta hän joutuu valitsemaan *huonomman* tuloksen. Nopat voivat tästä huolimatta räjähtää, mutta tästä voi hyötyä vain jos saa kriittisnopat tuplana.


> **Pahan Pekan tarina...**
>
> Paha Pekka istuu kantabaarissaan jauhamassa paskaa muutaman motoristin kanssa, kun yhtäkkiä alkaa aikamoinen sanaharkka, ja yksi motoristeista solvaakin Pekkaa pahanpäiväisesti. Pelinjohtaja vaatii Pekan pelaajalta **Taitotestiä**, jossa mitataan Pekan **Itsekuria**. Pekalla ei ole taitoa lainkaan. Pelinjohtaja antaa Pekan silti heittää kahta noppaa: Pekka saa 10, 4, joista joutuu valitsemaan huonoimman, eli 4. Tähän päälle Pekan **Psyko**-kyky, mikä on -1, jolloin lopputulokseksi tulee 3. Pekka epäonnistuu, ja koska Pekalla on vika: **huonot hermot**, pelinjohtaja toteaa, että eiköhän aleta tappelemaan.
>
> Paha Pekka päättää kimpaannuttuaan pistää motoristia turpaan, jolloin siis testataan **Lähitaistelu**-taitoa. Pekka heittää **Lähitaistelu**-taitonsa verran 10-sivuisia noppia, eli kolmea noppaa, saaden tulokseksi 3, 4, 9. Hän valitsee parhaimman, eli luvun 9. Tähän päälle Pekka lisää **Notku** -kykynsä lukeman +2, sekä +1 erikoistumisesta *Baaritappeluun*, josta lopputulokseksi saadaan 12.


## Kriittinen onnistuminen

Jokainen **Kriittinen Noppa** (`0`) räjähtää, ja jos Kriittisiä Noppia on vähintään `**kaksi (2)**`, ja toiminto onnistuu, eli yltää vaikeusasteeseen, niin toiminto katsotaan **Kriittiseksi Onnistumiseksi**.

**Kriittinen Onnistuminen** voi tuoda tilanteeseen erilaisia tilannekohtaisia etuja, ja näitä etuja arvoidessa voidaan ottaa myös huomioon **Kriittisen Aste**, mikä on yksinkertaisesti se kuinka monta räjähtävää noppaa heitettiin yhteensä.

Jos hahmolla ei ole taitoa, niin hän ei voi onnistua Kriittisesti, vaikka saisi kuinka monta räjähtävää noppaa.

> **Pahan Pekan tarina...**
>
> Motoristi yrittää puolustautua Pekan mahtavaa huitaisua vastaan, jolloin tilanne ratkotaan **vastakkaistestinä**, eli Pekka osuu motoristiin vain jos hän sa paremman noppatuloksen. PJ viskoo motoristin Lähitaistelu-taidon verran noppia, ja pyöräyttää kolmella nopalla 0,0,0! Kolme noppaa räjähtää, PJ heittää uudestaan ja saa 8,4,9. Eli lopputulos on 19, mutta Kriittisen aste on 3! Motoristin Notku on melko ankea -1 ja hänellä on kova humalatila, josta vielä -2 lisää, joten lopullinen lukema on (19-3) 16. Tämä on reilusti enemmän kuin Pekan hyökkäys (12), joten Motoristi välttää Pekan huitaisun helposti, ja pelinjohtaja lataa, että koska väistö oli Kriittinen Onnistuminen, niin Motoristi saakin vaparin Pekkaan. Ei nyt mennyt Pekan kannalta kauhean hyvin tämä reissu.

| Kriittinen | Taito 1 | 2     | 3     | 4     | 5    | 6    | 7    | 8    | 9    | 10   |
| ---------- | ------- | ----- | ----- | ----- | ---- | ---- | ---- | ---- | ---- | ---- |
| 2          | 1%      | 3%    | 5%    | 8%    | 11%  | 15%  | 19%  | 23%  | 26%  | 30%  |
| 3          | 0.10%   | 0.4%  | 1%    | 2%    | 3%   | 4%   | 5%   | 7%   | 9%   | 11%  |
| 4          | 0.01%   | 0.05% | 0.1%  | 0.3%  | 0.5% | 1%   | 1%   | 2%   | 2,5% | 3,5% |
| 5          | 0.00%   | 0.01% | 0.02% | 0.04% | 0.1% | 0.2% | 0.3% | 0,4% | 0,6% | 1%   |

## Kohdeluku

Lopullista lukemaa verrataan toiminnon **kohdelukuun**. Jos lopputulos on vähintään yhtä paljon kuin *kohdeluku*, toiminto onnistuu.

Kohdeluku voi määräytyä pelinjohtajan asettaman **vaikeusasteen** perusteella, tai esim. jonkun toisen hahmon, NPC:n, tai vihollisen toiminnon tuloksesta.

Taulukosta voit lukea yleisimmät *vaikeusasteet*, ja niihin liittyvän *kohdeluvun*, sekä onnistumistodennäköisyyden taidolla 1-4.

| Vaikeusaste     | Kohdeluku | Taito 0 | Taito 1 | Taito 2 | Taito 3 | Taito 4 | Taito 5 |
| --------------- | --------- | ------- | ------- | ------- | ------- | ------- | ------- |
| Rutiini         | 4         | 49%     | 70%     | 91%     | 97%     | 99%     | 99%     |
|                 | 5         | 36%     | 60%     | 98%     | 94%     | 97%     | 99%     |
| Helppo          | 6         | 25%     | 50%     | 75%     | 88%     | 94%     | 97%     |
|                 | 7         | 16%     | 40%     | 64%     | 78%     | 87%     | 92%     |
| Kohtalainen     | 8         | 9%      | 30%     | 51%     | 66%     | 76%     | 83%     |
|                 | 9         | 4%      | 20%     | 36%     | 49%     | 59%     | 67%     |
| Vaikea          | 10        | 1%      | 10%     | 19%     | 27%     | 36%     | 41%     |
| Todella vaikea  | 12        | 0.80%   | 9%      | 17%     | 25%     | 32%     | 37%      |
| Erittäin vaikea | 15        | 0.36%   | 6%      | 12%     | 17%     | 22%     | 26%      |
| Mieletön        | 20        | 0.01%   | 1%      | 2%      | 3%      | 4%      | 5%      |
| Lähes mahdoton  | 30        | 0.00%   | 0.1%    | 0.20%   | 0.3%    | 0.4%    | 0.5%   |


## Onnistumisen Marginaali

Joskus täytyy tietää kuinka hyvin toiminto onnistui. Tällöin voidaan laskea toiminnolle **Onnistumisen Marginaali**, eli **OM**. OM on yksinkertaisuudessaan: `[Toiminnon lopputulos]-[Kohdeluku]`. OM 0 vastaa siis täpärää onnistumista, eli hahmo yltää juuri ja juuri kohdelukuun. Useimmiten meille kuitenkin riittää tietää ihan yksinkertaisesti onnistuiko vai ei, jolloin täpäräkin onnistuminen on onnistuminen.

## Vastakkaistesti

Kiinteän vaikeusasteen sijaan kaksi hahmoa voivat mitellä toisiaan vastaan, jolloin etsitään korkeampaa lopputulosta. Tällaista toimintoa kutsutaan **Vastakkaistestiksi**. Kumpikin osapuoli tekee oman testin, mutta testin vaikeusaste on tällöin vastustajan testin lopputulos, kummin päin tahansa tilannetta tutkailee, ja ainoastaan paras tulos voittaa. Kumpikin osapuoli lisää omat olosuhdemuuttujansa omaan testiinsä.

Tasatuloksella etu lasketaan yleensä *puolustajan* hyväksi, mutta myös *pattitilanne* on ihan mahdollinen lopputulos. Pelinjohtaja voi päättää, mikä tuntuu uskottavimmalta, tai hauskimmalta siinä tilanteessa.

Jos kolme tai useampi hahmoa mittelee keskenään, voidaan hahmot sijoittaa lopputuloksensa perusteella eri sijoituksille. Tällaisten tilanteiden ratkaisu voi olla hankalaa, joten soveltakaa omalla vastuulla!

## Kykytesti

Kykytestit ratkaistaan heittämällä **Kolmea** D10, ja pudottamalla **huonoimman** ja **parhaimman**, jolloin jäljelle jää keskinkertaisin noppa, ja lisäämällä tämän tulokseen kyvyn arvon. Kykytestiä voidaan käyttää ratkaisemaan testejä, joihin ei löydy järkevää taitoa.
