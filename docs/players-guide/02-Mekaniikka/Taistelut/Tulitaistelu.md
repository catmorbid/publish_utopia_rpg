---
share: true
---
# Tulitaistelu

Tulitaistelussa luodit lentelevät ympäriinsä ja kuolema korjaa nopeasti. Harhaluodit ovat tappavia ja sivullisilta uhreiltakin on vaikea välttyä. Tulitaistelut ovat usein erittäin nopeasti ohi, ja usein jo ensimmäinen taistelukierros on ratkaiseva.

## Hyökkäys ampuma-aseella

Hyökkäysheitot ratkaistaan testaamalla `Ampumataitoa`. Vaikeusaste riippuu kohteen koosta ja senhetkisestä nopeudesta. **Onnistumisen Marginaalilla** voidaan ostaa **Efektejä**, eli käytännössä joko enemmän osumia, tai pyrkiä tarkempaan osumaan. Yleisesti ottaen nyrkkisääntönä voi pitää, että sarjatuliaseilla otetaan lisää osumia, kun taas kertalaukauksilla, tai puoliautomaattisilla aseilla voidaan pyrkiä tarkkoihin osumiin. Normaali vaikeusaste on 8 ihmisen kokoiseen kohteeseen, joka ei juurikaan liiku.

### Kohteen koko (peruskohdeluku)
**Pienikokoinen kohde (kääpiö)**: 10 (Puolustuskyvyton 5)
**Normaalikokoinen kohde (ihminen)**: 8 (Puolustuskyvytön 4)
**Suurikokoinen kohde (troggi)**: 6 (Puolustuskyvytön 3)

### Kohteen nopeus
**Liikkuva kohde:** Koko+2 tai Koko+Notku
**Nopeasti liikkuva kohde (esim. ajoneuvo):** Koko+6.

### Kohteen puolustautuminen
**Onnistunut väistö**: Hyökkääjälle haitta.
**Kriittinen väistö**: Hyökkäys menee ohi
### Kantama
**Normaali kantama:** Ei muutoksia
**Pitkä kantama**: Hyökkääjälle Haitta.
**Lähietäisyys**: Hyökkääjälle Etu.
**Lähitaistelussa**: Ratkaistaan lähitaistelun. Ks. [Lahitaistelu](./Lahitaistelu.md)

### Efektit
- **Ylimääräinen osuma**: +1 osuma per 4 OM (oletus).
- **Ylimääräinen kohde**: Saat vapaasti jakaa osumia myös toiseen kohteeseen. Huom. vaatii vähintään 2 osumaa.
- **Yliläpäisyn kohde:** 2 OM. Mikäli käytetään [Yliläpäisy](Tulitaistelu.md#Yliläpäisy)-sääntöä, toissijainen kohde saa puolet ensisijaisen kohteen osumista.
- **Tarkka osuma**: +/- 1 vammaheiton tulokseen per 4 OM.

## Kantama

Aseen kantama määrittää hyökkäykseen edun tai haitan, tai muita vaikutuksia.

| Kantama              | Etäisyys (korkeintaan)                | Vaikutus | Sarjatuli                 | Osumakerroin   |
| -------------------- | ------------------------------------- | -------- | ------------------------- | -------------- |
| Minimikantamalla     | Pienempi kuin ilmoitettu minimkantama | Haitta   |                           | Haitta         |
| Lähietäisyys         | 1 metriä                              | Etu      | Isompi noppa              | x2             |
| Lyhyt kantama        | ½ Normaali                            | -        | -                         | x2             |
| Optimaalinen kantama | Aseen ilmoitettu kantama              | -        | Pienempi sarjatulinoppa   | x1, Etu        |
| Pitkä kantama        | 4x Normaali                           | Haitta   | 2 pienempi sarjatulinoppa | x1, Ei haittaa |


## Puolustautuminen

Tuliaseita vastaan on hankala puolustautua, ja vaihtoehtoja on käytännössä kaksi: **Väistöliikkeet** ja **Suojautuminen**.

### Väistöliikkeet
*1 Toimintopiste*
Hahmo voi yrittää tehdä itsestään hankalamman kohteen käyttämällä 1 toimintopisteen ja testaamalla **Väistöliikkeet** -taitoa. Testin **kohdeluku** **10**. Jos hahmo onnistuu, hän tekee itsestään vaikeamman kohteen ja hyökkääjä saa **Haitan** hyökkäykseensä. **Kriittinen Onnistuminen** väistössä välttää hyökkäyksen kokonaan.

Väistöliikkeet on voimassa aina siihen asti kunnes hahmo toimii seuraavaksi. Väistöliikkeitä voi tehdä myös **Reaktiona**, jolloin hahmo viivyttää seuraavaa vuoroaan puolustautumalla.
### Suojautuminen
*1 toimintopiste*
Paras tapa suojautua tuliaseilta on hakeutua suojaan. Suoja on kuitenkin parhaimmillaankin väliaikainen, mutta voi tarjota pienen hengähdyksen tiukan tulitaistelun keskellä. Suojautuminen vaatii 1 toimintopisteen, mutta hahmo saa automaattisesti käyttöönsä lähinnä olevan suojan.

Kun hahmo pystyy hyödyntämään suojaa, hän saa tietyn määrän **Suojapisteitä**. Näiden merkitsemiseen kannattaa käyttää vaikka jotain sopivia pelimerkkejä.

Jos hahmoa kohti ammutaan, niin kaikki osumat iskeytyvät oletuksena suojaan, eikä hahmoon. Hahmo ei siis kärsi lainkaan vahinkoa.

Hyökkäyksen vahinko heitetään normaalisti, mutta PL = suojapisteet ja läpäisy lasketaan normaalisti. Jos yhtään vahinkoa tulee läpi, niin suoja *vahingoittuu* ja suojapisteet vähenevät yhdellä. Jos vahinkon on vähintään 2x suojapisteet, niin suoja ottaa *tuplavahingon*, eli pisteet vähenevät kahdella. Jos taas vahinko on yhtä kuin tai enemmän kuin 4x suojapisteet, niin suoja *tuhoutuu* välittömästi. Suoja tuhoutuu myös mikäli suojapisteet laskevat 0:aan.

Jos hyökkäyksen läpäisy on enemmän kuin suojapisteet, niin hyökkäys läpäisee suojan ja kohde ottaa vahinkoa suojasta huolimatta, mutta efektiivinen läpäisy on $(läpäisy - suojapisteet - 1)$.

Suojapisteet vaikuttavat ainoastaan hyökkäyksiin, jotka kohdistuvat suojan suuntaan, ja suojan voi kiertää jos pääsee selustaan. Jos hahmo on kokonaan suojan peitossa, niin hahmoon ei voi osua, ellei hyökkääjällä ole käytössään aseistusta, jolla pystyy läpäisemään suojan.

| Suoja                    | Suojapisteet | Tuplavahinko (x2) | Tuho (x4) | 
| ------------------------ | ------------ | ------------ | --------- |
| Flipattu baaripöytä      | 3            | 6            | 12        |
| Ohut, mutta korkea seinä | 2            | 4            | 8         |
| Alumiiniroskis           | 1            | 2            | 4         |
| Betoniporsas             | 4            | 8            | 16        |
| Betonipylväs             | 5            | 10           | 20        |
| Auton Ovi                | 2            | 4            | 8         |
| Paksu metalliovi         | 6            | 12           | 24        |

> [!example] Esimerkki
> David joutuu tiukan tulituksen alle ja hakeutuu läheisen betoniporsaan taakse suojaan, saaden 4 suojapistettä. Häntä vastaan hyökätään rynnäkkökivääreillä. Rynnäkkökiväärin vahinkoluokka on L5 ja läpäisy 1, joten betoniporsaan PL on 3, mikä vähentään kiväärin vahingon d4:ään. David ottaa 5 osumaa, jotka osuvat suojaan, ja tekevät siis 5d4 vahinkoa, eli yhteensä 10 pistettä. Tämä riittää tuplavahinkoon suojaan, joten davidin suojapisteet tippuvat 2:een.
> Seuraava hyökkäys on 4 osumaa, mutta nyt Davidilla on enää 2 suojapistettä, josta saa PL 2, läpäisyn kanssa PL1 kivääriä vastaan, eli Davidin suoja ottaa 4d8 vahinkoa, josta tulee yhteensä 18 pistettä. 2 suojapisteellä tuhon raja on kuitenkin enää 8 pistettä, joten tämä riittää tuhoamaan suojan lopullisesti.
## Osumat

Onnistunessa hyökkäyksessa osumien lukumäärään vaikuttaa **Onnistumisen Marginaali**. Normaalisti ylimääräisen osumaan vaaditaan 2 OM, mutta tämä voi vaihdella.

Jokainen osuma antaa oman vahinkonopan, jotka sitten lasketaan yhteen.

> [!abstract] **Pahan Pekan tarina...**
> 
>
> Paha Pekka lataa lippaan täydeltä konepistoolilla motoristia. Motoristi on 6 metrin päässä Pekasta, ja Konepistoolin kantama on 15 metriä, joten Pekka on Lyhyellä kantamalla (8m). Kohde on keskikokoinen, joten vaikeusaste on 8 ja konepistoolin sarjatulinoppa on D12 eli aseen oletus. Pekalla on Ampumataito 3, joten hän heittää kolmea noppaa: 9,8,7, joista ottaa parhaan eli 9 ja lisää Skarppinsa +1, sekä sarjatulinopasta +6 saaden kokonaistuloksen 16. Motoristi yrittää väistöliikkeitä kahdella nopalla ja haitalla, mutta saa vain 3 ja siis epäonnistuu, joten vaikeusaste on edelleen 8. Pekka osuu ja saa OM 8. Konepistoolin hallintaluku on yhteensä 5 (perus 3 + Pekan Ruho 2), mutta sarjatulinopan 6 on suurempi kuin hallintaluku, joten sarja ei pysy kovin hyvin hallinnassa, jolloin lisäosuman marginaali on 2, eli Pekka saa yhteensä 5 osumaa. Motoristilla on nahkarotsiin ommeltu teräslevyjä, joista hän saa Panssariluokan 2 luoteja vastaan. Konepistoolin Vahinkoluokka on 3, joten jäljelle jää vahinkoluokka 1, josta tulee vain 1d2 vahinkoa. Pekka heittää siis 5D2 vahinkoa ja saa: 1, 2, 2, 2, 2 eli yhteensä 9 vahinkoa! Motoristi saa Vakavan lävistävän vamman: 9! Osuma lävistää sydämen. Motoristi kuolee välittömästi.

### Keskivahinko

Jos hahmo saa kerralla niin paljon osumia, että ei millään jaksaisi heittää kaikkia vahinkonoppia, varsinkin jos osumat joutuisi heittämään useassa erässä, niin taistelua voi nopeuttaa käyttämällä **keskivahinkoa**. Tällöin jokainen osuma tekee `VL + vahinkomuuttujat` vahinkoa, ja vahinko kerrotaan osumien lukumäärällä. Tämä yksinkertaistus sopii erityisen hyvin yhteen sarjatuliaseiden kanssa, ja silloin kun osumien määrä nousee erittäin korkeaksi.

Lopputulos on hyvin lähellä nopan keskiarvoa (jää vähän alle), mutta voi nopeuttaa peliä huomattavasti. Yleisesti ottaen pelaaja saa päättää haluaako heittää vahinkonoppansa, vai käyttää keskivahinkoa.

> [!info]
> On suositeltavaa, että keskivahinkoa käytetään aina kun vahinkoppien määrä on 6 noppaa tai enemmän.



> [!Example] Esimerkki
>
> Rat Bratz päästää 100 ammuksen sarjan Warrior-5 Minigun gatling-konekivääristään käytävää pitkin juokseviin vihollisiin ja saa 24 osumaa. Aseen Vahinkoluokka on L4+1 (Rat on modannut asettaan). Läpäisy 3 riittää läpäisemään kokonaan vihollisten panssarin, joten Rat tekee D8+1 vahinkoa per osuma. Rat jakaa 24 osumaansa 3 kohteen kesken, josta tulee 8 osumaa per kohde. Ratin pelaaja ei jaksa heitellä niin montaa noppaa, vaan käyttää keskivahinkoa: VL L4+1 keskivahinko on 5, joten jokainen kohde saa 5*8 = 40 vahinkoa. Eiköhän se ollut siinä...

### Osumakerroin

Joissain aseissa on vahingon kohdalle merkitty osumakerroin `(Esim. x4)`, mikä yleensä kertoo, että sillä ammutaan kerralla iso määrä pieniä projektiileja, kuten esimerkiksi haulikoissa. Tämä indikoi osumien määrän normaalilla kantamalla; lähempänä osumakerroin kasvaa, kun taas kauempana se pienenee, mutta osumiseen saa edun, mikä kuvastaa suurempaa hajontaa ja sitä kautta syntyvää osumatarkkuutta. Jos aseessa on osumakerroin, niin kantaman vaikutus on seuraavanlainen (Kantaman normaalit vaikutukset on jo huomioitu):

- **Lähietäisyys:** osumakerroin x2 ja Etu.
- **Lyhyt Kantama**: osumakerroin x2, Ei etua.
- **Optimaalinen kantama**: normaali osumakerroin ja Etu. Voit ottaa ylimääisen kohteen (1 ylimääräinen osuma).
- **Pitkä kantama**: osumakerroin 1/2. Ei etua. Voit ottaa 2 ylimääräistä kohdetta (1-2 ylimääräistä osumaa).

### Kriittiset osumat
Jos aseella ei ammuta sarjatulta, niin kriittinen onnistumien aiheuttaa **kriittisiä osumia**. Sarjatulta ampuessa kriittinen onnistuminen aiheuttaa jo heti enemmän osumia, joten ylimääräistä etua siitä ei lasketa.

Kriittisen osuman seurauksena vahinko kerrotaan **kriittisen kertoimella**. Eli jos sait triplakriittisen, niin teet triplavahingon, ja niin edelleen.

## Sarjatuli
Sarjatuli on arvaamatonta ja vaarallista. Siinä on hyvät ja huonot puolensa. Sopivalla kantamalla sarjatuliaseilla on helpompi osua johonkin, mutta sarjatulta voi olla vaikea hallita tehokkaasti. Sarjatuliaseet jaetaan neljään eri luokkaan tulinopeuden perusteella. Tulinopeus määrää ammusten kulutuksen ja vastaavasti **Sarjatulinopan** koon. Voit halutessasi ampua ilmoitettua pienemmän sarjan, jolloin vastaavasti käytät pienempää sarjatulinoppaa, mutta säästät ammuksia.

Tulinopeus ilmoitetaan Erikoispiirteenä aseluettelossa. Tulinopeus määrittää lisäosuman hinnan *Onnistumismarginaalista*, ja se suhteutetaan aina hyökkäyksen kantamaan. Parhaimmillaan voit myös saada *osumakertoimen* tulinopeudesta.

| Tulinopeus    | Lähietäisyys | Lyhyt   | Normaali | Pitkä kantama |
| ------------- | ------------ | ------- | -------- | ------------- |
| Pikatuli      | OM 2         | OM 3    | OM 4     | OM 4          |
| Sarjatuli     | OM 1         | OM 2    | OM 3     | OM 4          |
| Luotisade     | OM 1 X2      | OM 1    | OM 2     | OM 4          |
| Metallimyrsky | OM 1 X3      | OM 1 X2 | OM 1     | OM 4          | 

### Sarjatulen Hallinta
Vertaa hyökkäyksen taitonoppaa aseen hallintalukuun, joka on: $Rekyyli-Ruho$. Jos Hallintaluku on pienempi kuin 0, niin sarjatuli pysyy aina hallinnassa. Jos taitonoppa on pienempi tai yhtä suuri kuin hallintaluku, niin sarjatuli ei pysy hallinnassa. Heitä D6 seuraukset. Lisäosumien OM on tällöin vakio 6, eli sarjatuliaseesta on enemmän haittaa kuin hyötyä.

| D6  | Seuraus                                                                   |
| --- | ------------------------------------------------------------------------- |
| 1   | D6 sivullista uhria                                                       |
| 2   | Kaadut maahan                                                             |
| 3   | Liipasin jää pohjaan: kulutat 3x määrän ammuksia                          |
| 4   | Osut kaveriin kohteen sijasta                                             |
| 5   | Kaadut maahan ja ase lentää kädestäsi                                     |
| 6   | Ase riistäytyy käsistä ja pudotat sen, mutta otat myös nahkaasi D6 osumaa |


> [! example] Esimerkki
> Spurgul on pubin vessassa asioimassa, eikä osaa aavistaa, että joku nilkki on päättänyt yrittää ryöstää hänet wc:ssä. Ryöstön välineenä on konepistooli, jolla ryöstäjä pyrkii maalaamaan spurgulin seinälle.
> Hyökkääjällä on MP-3 Micro SMG, joka sinkoaa *sarjatulta*. He ovat lähietäisyydellä ja Nilkki heittää 2 noppaa edulla, koska on huumepäissään plus sarjatulinopan: 9, 8, joten lopputulos on 9+8 = 15 + 0 (skarppi). Spurgul on kääpiö, joten häneen on vaikea osua (Kohdeluku 10), mutta koska hän ei lainkaan huomaa hyökkäystä, on hän puolustuskyvytön (Kohdeluku 5). Hyökkäys osuu ja marginaalilla 10. Aseen hallintaluku on 6, mutta se pysyy hallinnassa. OM 10 Sarjatulella lähitetäisyydeltä tarkoittaa 10 osumaa. Spurgulilla on kuitenkin PL 2, mikä saattaa pelastaa hänet, mutta hän ottaa silti 10d2 osumaa... Ei näytä hyvältä!

### Purskeet

Joillakin aseilla voidaan ampua lyhyitä **Purskeita** korkealla tulinopeudella, mikä parantaa osumatarkkuutta ja vahinkopotentiaalia. Purskeita mahtuu kuitenkin vain yksi per toiminto. Purskeet on hyvä tapa säästää ammuksia, mutta kuitenkin aiheuttaa merkittävää vahinkoa.

Purske on useimmmiten 2-5 ammusta, aseesta riippuen. Se antaa **Edun** hyökkäykseen **lyhyellä kantamalla** tai **lähietäisyydeltä**. Purske pysyy aina hallinnassa ja ylimääräisten osumien marginaali on normaali eli OM 2, mutta et voi tehdä enempää kuin yhden Purskeen per hyökkäys. Purskeita voi tähdätä, mutta ne voi kohdistaa vain yhteen kohteeseen kerralla.

> [!Example] Esimerkki
> **Smichter P19 GT**:llä on erikoispiirre **Purske-3**, eli sillä voi ampua 3 ammuksen Purskeita. Neo on ostanut parin näitä ja testailee niitä KharmaCorpin kätyreihin. Neo räiskäyttää kahdella aseella Purskeen ja heittää 2d (Etu) kummallekin aseelle: 7+8=15 ja 16+6 = 22. Kohde on yllätetty, joten lasketaan puolustuskyvyttömäksi, eli Kohdeluku on vain 4. Neo tarvitsee 6 marginaalia 3 osumaan, joten kumpikin hyökkäys saa maksimiosumat. Lisäksi Neo tähtää kohdetta päähän, eli oottaa 1. aseelle +1 tähtäyksen ja toiselle +3 tähtäyksen.

### Jatkuva Sarjatuli
Jos hahmo ampuu täydellä tulinopeudella, on hänellä mahdollisuus jatkaa tulitusta maksamalla vain 1 toimintopiste. Kierroksen aikana voi ampua korkeintaan 4 täyttä sarjaa, mikä jatkuvalla sarjatulella tarkoittaisi aseen TP + 3 toimintopistettä.

Jatkuva sarjatuli voi jatkua seuraavalle kierrokselle, mutta välissä ei voi tehdä muita toimintoja, muuten täytyy maksaa täydet toimintopisteet.

## Harhaluodit

Harhaluodit voivat aiheuttaa sivullisia kuolemia, tai viedä hahmot tahtomattaan harmin tielle. Harhaluodit tarkistetaan joka hyökkäyksen jälkeen, mikäli vähintään yksi projektiili meni ohi kohteesta. Jos kaikki projektiilit osuivat kohteeseensa, ei harhaluoteja tarvitse tarkistaa.

Jokainen kohde, joka on harhaluotien määrittämällä osuma-alueella on riskinä ottaa harhaluodista. Laske **suurpiirteinen** ohi menneiden ammusten lukumärää, ja tämän perusteella määrittele kuinka monta harhaluotinoppaa pitää heittää. Osumia ei tarvitse laskea, eikä harhaluotinoppia muuttaa.

| Harhaluotien lkm | Harhaluotinopat |
| ---------------- | --------------- |
| 1-10             | 1               |
| 11-20            | 2               |
| 21-30            | 3               |
| 31-40 jne.       | 4               |

Sen jälkeen heitä harhaluotinopat (D10) jokaista kohdetta vastaan, joka on osuma-alueella. Mikäli noppa näyttää harhaluodin **kohdelukua**, tai enemmän, niin hahmo saa yhden osuman. Osumaluku riippuu etäisyydestä. Ihan läheltä ammuttuna osumaluku on melko pieni, kun taas pitkän matkan päästä se on erittäin suuri.

| Harhaluodit / etäisyys | Kohdeluku | 
| ---------------------- | --------- |
| 2 m tai alle           | 4         |
| 3-4m                   | 5         |
| 5-8m                   | 6         |
| 9-16m                  | 7         |
| 17-32m                 | 8         |
| 33-64m                 | 9         |
| 65-128m                | 10        |

Heitä vahinko normaalisti per osuma. Saman kaliiperin aseiden harhaluodit kannattaa niputtaa yhteen, mutta eri kaliiperin aseet taas kannattaa heittää erikseen, koska niillä on ihan eri vahinko.

Hahmo altistuu harhaluodeille mikäli liikkuu alueelle, jossa on juuri räiskitty paljon luoteja. Jos sillä on merkitystä, niin yleisesti ottaen voidaan ajatella, että alue on **vaarallinen** ampujan seuraavaan toimintoon asti. Jos hahmo liikkuu usean harhaluotialueen läpi, niin hahmo voi ottaa joka alueella harhaluoteja.

Hahmot, jotka ovat **suojassa** ovat automaattisesti turvassa harhaluodeilta.

> [!Example] Esimerkki
> **Neo** on joutunut keskelle kahden katujengin tulitaistelua, ja piileskelee auton takana, kun huomaa, että sivukujalta ilmestyvä sinijää-narkkari ryntää häntä kohti suu sinisen vaahdon peitossa kirves kourassaan. Neo menee paniikkin, ja ryntää pakoon. Harmi vaan, että hän juoksee suoraan jengiläisten tulituksen keskelle.
> 
> PJ toteaa, että alueella on juuri vaihdettu erittäin suuri määrä luoteja, ja päättää harhaluotien määräksi n. 50, josta tulee 5 harhaluotinoppaa. PJ heittä 5D10: 3, 7, 5, 9, 8. Ampujat ovat noin 15m päässä Neosta, joten harhaluodin osumaluku on 7, eli Neo ottaa 3 osumaa! Osumien VL on 3, ja Neolla on PL 2 luotiliivit, joten hän saa 3D2 vahinkoa, josta tulee yhteensä 4 pistettä. Siitähän tulee lievä haava!
> 
> Koska sinijäänarkkari juokse Neon perään, niin tämäkin ottaa samanmoiset osumat: 10, 10, 6, 7, 1 - eli neljä (4) osumaa. Ilman panssaria tästä tulee 4D6 vahinkoa: PJ heittää 14 vahinkoa, mikä riittää vakavaan vammaan (Sinijää nostaa kestävyyttä melkoisesti). Narkkari ottaa osumaa polvilumpioon, ja tipahtaa, mutta jatkaa silti suu vaahdossa ryömien eteenpäin.

## Tähtäys
Hahmo voi käyttää 1-5 toimintopistettä tähtäykseen, jolloin hän saa +1 per toimintopiste välittömästi tähtäystä seuraavaan hyökkäykseen. Hän kuitenkin viivyttää vuoroaan tähtäyksen aikan, joten jos joku ehtii toimimaan häiritsevästi tässä välissä, hahmo menettää tähtäyksen edun. Varsinainen hyökkäys voi venyä seuraavalle kierrokselle, mutta hahmo joutuu kuitenkin päättämään heti kuinka monta pistettä aikoo käyttää tähtäykseen.

Kannattaa käyttää vaikka noppa (D6 toimii tähän hyvin) merkitsemään muistiin paljonko toimintopisteitä olit jo käyttänyt tähtäykseen. Jos hahmo haluaa ampua ennen kuin on käyttäny kaikki aikomansa pisteet, tulee hänen tehdä Vaikea **Taisteluvalmius**-testi, jossa onnistuessaan hän saa muuttaa suunnitelmiaan.

## Tarkka-ammunta
Tarkka-ammuntaa voidaan käyttää ampumaan etäisyyksille, jotka ylittävät aseen Pitkän kantaman. Jos aseessa on Tarkennin, niin. Tarkennin määrittää tarkka-ammunnassa käytettävän normaalikantaman. Esim. `x4 tarkennin` tarkoittaa, että asetta voidaan käyttään tarkka-ammuntaan ja tarkka-ammunnan normaalikantama on 4x aseen kantama. Pitkä kantama on siis $Normaali kantama * Tarkennin * 2$, ja siitä tulee haitta hyökkäykseen kuten yleensä.

Ainoastaan kiväärit soveltuvat pitkille matkoille ja pienemmistä kaliipereista loppuu auttamatta teho kesken. Tarkkuuskiväärillä voidaan tarkka-ammunnassa ampua myös yli pitkän kantaman, jolloin hyökkäykseen tulee Haitta, ja lisäksi vahinko puolitetaan. Maksimikantama tarkka-ammunnassa on 2x pitkä kantama.

Hyökkäyksen kohdeluku lasketaan normaalisti, mutta se on kaksinkertainen ja ampujalta odotetaan vähintään yhden kierroksen valmistautumista ja tähtäämistä. Hyökkäys jaetaan kahteen osaan: **Tähtäys** (Taktiikka) ja **Ampuminen** (Ampumataito). Jos tähtäys epäonnistuu, niin hyökkäykseen tulee Haitta. Hyökkäykseen voi saada edun, jos Tähtäys onnistuu kriittisesti.

Jokainen ylimääräinen tähtäämiseen käytetty kierros vähentää ampumisen vaikeusastetta yhdellä. Hahmo voi kuitenkin tähdätä korkeintaan puolet ampumataitonsa taitoasteesta. Eli ampumataito 10 mahdollistaisi 5 kierroksen tähtäilyn.


>[!example] Esimerkki
>Zodiac on linnoittautunut kerrostalon katolle tarkkuuskiväärin kanssa vaanimaan kohdetta, joka hänen tulee salamurhata. Tovin odoteltuaan Zodiac huomaa kohteensa, ja ottaa tämän jyvälle. Kohde on keskikokoinen humanoidi, joka liikkuu hitaasti, joten hyökkäyksen vaikeusaste on 16. Zodiacin SS-88 Sniper -kiväärissä on x5-kiikaritähtäin, joten hänen normaalikantamansa tarkka-ammunassa on 250 metriä. Kohde on kuitenkin 1000 metrin päässä, mikä on aivan Zodiacin maksimikantamalla! Zodiac tähtää 2 kierrosta, joten vaikeusaste laskee 14:a ja heittää neljällä nopalla ampumataitoa. Hänellä on 1 haitta (pitkä kantama) ja 1 etu (Erikoistuminen), joten toiminto ratkaistaan normaalisti: 6, 7, 9, 19 = 19 ja lisää skarppinsa +5. Lopputulos on 24, eli Zodiac osuu ja saa 10 pisteen marginaalin! Hän ostaa 1 lisäosuman (2 OM) ja 2 tähtäystä (+2 vammaan, 8 OM) Kiväärin vahinko on hurja L8, ja Läpäisy 1. Kohteella on kuitenkin PL 5 panssari, mikä vähenee läpäisystä PL 4:een, ja vahinko vähenee L 4:ään. Zodiac heittää 2D8 vahinkoa: 6+4 = 10 vahinkoa. Aika paljon, mutta kohteella onkin Kestävyys 16, joten se ei riitä tappavaan osumaan, mutta on tarpeeksi vakavaan vammaan (raja 8). Hän heittää vakavan viiltohaavan ja saa tuloksen 8+2 (tähtäys x2) =10. Luoti osuu kohdetta kalloon ja kallo räjähtää kappaleiksi. Kohde tipahtaa maahan maalaa katukivetyksen punaiseksi. Zodiac alkaa pakkailla kamoja, ennen kuin poliisipiirin partiot eksyvät paikalle...

## Kriittinen Tähtäys
Hahmo voi yrittää tähdätä heikkoihin kohtiin kohteessa. Tämä on mahdollista vain, jos hahmo ampuu kertatulta, eli käyttää tulinopeutta 1, mutta myös jos hän ampuu [Purskeita](Tulitaistelu.md#Purskeet). Tähdätessään heikkoihin kohtiin, Pelinjohtaja määrää muutoksen vaikeusasteeseen, riippuen siitä kuinka vaikea kyseiseen kohtaan on tähdätä.

Oletuksena vaikeusaste riippuu siitä millainen panssari kohteella on yllään.

Onnistuessaan heikkoon kohtaan tähdätty hyökkäys tekee automaattisesti kriittisen, joko x2 tai x3 kertoimella, riippuen ruumiinosasta ja vaikeusasteesta.

| Kohteen Panssari | Vaikeusaste (x2) | Vaikeusaste (x3) |
| ---------------- | ---------------- |:---------------- |
| Ei Panssaria     | +4               | +8               |
| Kevyt            | +6               | +10              |
| Keskiraskas      | +8               | +12              |
| Raskas           | +10              | +15              |

## Yliläpäisy
Jos oleellista, niin taistelussa voidaan huomioida **Yliläpäisy**, jolloin projektiilit voivat läpäistä yhden kohteen, ja osua toiseen kohteeseen sen takana. Yliläpäisy tapahtuu automaattisesti, mikäli aseessa on vähintään 1 piste läpäisyä jäljellä sen jälkeen kun läpäisy on vähentänyt panssarin nolliin. Tällöin ammus jatkaa matkaansa kohteen läpi, ja sen *efektiivinen läpäisy* on jäljellä oleva läpäisy.

Osumat toissijaisiin kohteisiin voidaan ratkaista esim. *harhaluodeilla*, tai mikäli se on haluttu efekti, niin hyökkääjä voi käyttää [Hyökkäyksen](Tulitaistelu.md#Hyökkääminen) **onnistumismarginaalia** ottaakseen ylimääräisen yliläpäisykohteen. Yliläpäisy voi jatkua myös toissijaisen kohteen jälkeen, mikäli vain läpäisyä riittää, mutta jokainen läpäisty kohde vähentää Läpäisyarvoa yhdellä.

> [!Example] Esimerkki
> **Driver** on karaistunut NWFL Troggi, joka joutuu puolustamaan ryhmäänsä hyökkäävältä laumalta mutanttisusipetoja keskellä erämaata. Driver on ladannut automaattihaulikkoonsa APN Panssarineula-ammuksia, ja lataa sarjan kohti hyökkäävää laumaa. Koirat tulevat kivassa letkassa kahdessa rivissä, joten Driver pyrkii osumaan kahteen letkan ensimmäiseen. Hyökkäysheitosta tulee 15 ja kohteet ovat optimaalisella kantamalla, joten Driver osuu OM 7. Hän käyttää 4 OM saadakseen kumpaankin kohteeseen toissijaisen Yliläpäisykohteen. Jäljelle jäävällä OM 3 hän saa toisen osuman. Kohteilla on PL 1 ja ammuksissa on LL 3, joten yliläpäisyyn jää (3 - 1 (PL) - 1 (yliläpäisy)) LL 1. Ammuksissa on x6 osuma-kerroin joten kumpikin ensisijainen kohde ottaa 6d4 vahinkoa. Ensimmäinen peto ottaa 16 vahinkoa ja toinen 15 vahinkoa. kumpikin pedoista kuolee osumiin. Yliläpäisyn kohteet ottavat kumpikin 3 osumaa LL 1, mikä riittää läpäisemään panssarin PL 1, joten kumpikin ottaa 3d4 vahinkoa: 9 ja 6 mikä riittää vakvaan ja toinen lievään vammaan. Vamma-heitoista tulee 6, 9. Kaksi koirista kuolee, kolmas tipahtaa ja vuotaa kuiviin, mutta neljäs jatkaa matkaansa, vaikkakin haavoittuneena.