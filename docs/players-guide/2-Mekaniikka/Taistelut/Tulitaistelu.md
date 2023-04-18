---
share: true
---
# Tulitaistelu

Tulitaistelussa luodit lentelevät ympäriinsä ja kuolema korjaa nopeasti. Harhaluodit ovat tappavia ja sivullisilta uhreiltakin on vaikea välttyä. Tulitaistelut ovat usein erittäin nopeasti ohi, ja usein jo ensimmäinen taistelukierros on ratkaiseva.

## Hyökkäys ampuma-aseella

Hyökkäysheitot ratkaistaan testaamalla `Ampumataitoa`. Vaikeusasteena on hyökkääjän ja kohteen välisen etäisyyden perusteella määrittyvä **Kantama**. Onnistumisen Marginaalilla voidaan ostaa **Efektejä**, eli käytännössä joko enemmän osumia, tai pyrkiä tarkempaan osumaan. Yleisesti ottaen nyrkkisääntönä voi pitää, että sarjatuliaseilla otetaan lisää osumia, kun taas kertalaukauksilla, tai puoliautomaattisilla aseilla voidaan pyrkiä tarkkoihin osumiin.

- **Ylimääräinen osuma**: +1 osuma per Rekyyli OM.
- **Ylimääräinen kohde**: Saat jakaa osumia myös toiseen kohteeseen. Huom. vaatii vähintään 2 osumaa.
- **Yliläpäisyn kohde:** 2 OM. Mikäli käytetään [[Tulitaistelu#Yliläpäisy|Yliläpäisy]]-sääntöä, toissijainen kohde saa puolet ensisijaisen kohteen osumista.
- **Tarkka osuma**: +/- 1 vammaheiton tulokseen per 4 OM.

> [!abstract] Pahan Pekan tarina...
>
> Paha Pekka herää sivukujalta, roskiksesta, jonne hänet on raahattu menetettyään tajuntansa pubissa. Hän huomaa makaavansa useiden ihmisruhojen ja rotan raatojen seassa, kuolemankatku sieraimissaan, kärpästen ympäröimänä. Pekka kömpii ulos ja tonkii ruhoja ja löytää sisälmysten keskeltä vanhan konepistoolin, sekä vähän ammuksia. Vihasta soikeana hän ryömii ulos ja suuntaa pubin etuovelle. Paha Pekka astuu sisälle pubiin, ja etsii motoristin, jolta sai hetki sitten turpaansa, aikeenaan teloittaa vihamiehensä siihen paikkaan. Motoristi huomaa Pekan, tämän ollessa vain muutaman metrin päässä, mutta tässä kohtaa Pekka painaa jo liipaisimen pohjaan. Pekka heittää aloitteen +2 muutoksella. ja saa tulokseksi 12, kun taas yllätetty motoristi saa vain 7. Pekka saa ensimmäisen vuoron...

## Kantama

Aseen kantama määrittää hyökkäyksen perusvaikeusasteen. Kantama voidaan ilmoittaa muodossa `A/B-C` tai pelkkä `B-C`, jossa:
`A` = minimikantama. Asetta on vaikea käyttää ja hyökkäyksen vaikeusaste on 14.
`B` = Optimaalinen kantama.
`C` = Maksimikantama. Yleensä 16x optimaalinen kantama. Tämän jälkeen vahinko puolitettaan.

| Kantama                | Etäisyys (korkeintaan)              | Vaikeusaste | 50m  |
| ---------------------- | ----------------------------------- | ----------- | ---- |
| Minimikantamalla       | Korkeintaan ilmoitettu minimkantama | 14          |      |
| Lähietäisyys           | 1-2 metriä                          | 6           |      |
| Lyhyt kantama          | ½ Optimi                            | 8           | 25m  |
| Optimaalinen kantama   | Aseen ilmoitettu kantama            | 10           | 50m  |
| Pitkä kantama          | 2x Optimi                           | 12          | 100m |
| Erittäin pitkä kantama | 4x Optimi                           | 14          | 200m |
| Äärimmäinen kantama    | 8x Optimi.                          | 16          | 400m |
| Maksimikantama         | 16x Optimi.                         | 20          | 800m |


### Tarkentimet
Aseissa voi olla tarkentimia, jotka antavat jonkinlaisen tarkennus-kertoimen. Tämä voi olla ilmaistu esim. muodossa `x20 tarkennin`. Tarkentimet mahdollistavat aseen käytön huomattavasti pidemmällä kantamalla, tarkentamalla kohdetta, mutta toisaalta pitkän kantaman päähän on silti vaikea ampua ja osua, kun pitää ottaa huomioon kaikenlaiset olosuhdetekijät.

Tarkennin vaikuttaa aseen kantamaan seuraavasti:
- Minimikantama = 1 x tarkennuskerroin, tai minikantama x tarkennuskerroin, kumpi vain on suurempi.
- Optimaalinen kantama = optimaalinen kantama * tarkennuskerroin.
- Jos etäisyys > aseen normaali maksimikantama (ilman kertoimia), vaikeusasteeseen lisätään +4.

Teoriassa tarkentimella voidaan osua hyvinkin pitkien etäisyyksien päästä.

>[!example] Esimerkki
>Zodiac on linnoittautunut kerrostalon katolle tarkkuuskiväärin kanssa vaanimaan kohdetta, joka hänen tulee salamurhata. Tovin odoteltuaan Zodiac huomaa kohteensa, ja ottaa tämän jyvälle. Zodiacin SS-88 Sniper -kiväärissä on x5-kiikaritähtäin. Kohde on 1000 metrin päässä, mutta kiitos kiikaritähtäimen, kiväärin optimaalinen kantama on (60x5) 300m, joten kohde on _Erittäin pitkän kantaman_ päässä (vaikeusaste 14). 1000m on kuitenkin enemmän kuin aseen normaali maksimikantama (960m), joten vaikeusaste nousee neljällä ja on 18. Harmillisen haastavaa - mutta ei toki mahdotonta. Zodiac tähtää 2 toimintopisteellä (+2), ja heittää neljällä nopalla ampumataitoa: 6, 7, 9, 19, ja lisää skarppinsa +5 ja aseen tarkkuuden +3, jolloin lopputulos on peräti 29. Zodiac osuu marginaalilla (29-18) 11. Kiväärin tulinopeus on 3 ja rekyyli 3, joten Zodiac valitsee ylimääräisen osuman ja 2x tarkka osuma, josta tulee +2 vammaheittoon. Kiväärin vahinko on hurja L7+1, ja Läpäisy 2. Kohteella on kuitenkin PL 5 panssari, mikä vähenee läpäisystä PL 3:een, ja vahinko vähenee L 4+1:een. Zodiac heittää 2D8+2 vahinkoa: 3, 5 = 8+2=10 vahinkoa. Aika paljon, mutta kohteella onkin Kestävyys 16, joten se ei riitä tappavaan osumaan, mutta on tarpeeksi vakavaan vammaan (raja 8). Hän heittää vakavan lävistävän vamman +2 muuttujalla: 8+2 = 10. Toinen luodeista osuu kohdetta suoraan kalloon, ja kallo räjähtää sirpaleiksi, värjäten katukivetyksen punaiseksi. Zodiac alkaa pakkailla kamoja, ennen kuin poliisipiirin partiot eksyvät paikalle...

## Puolustautuminen

Tuliaseita vastaan on hankala puolustautua, ja vaihtoehtoja on käytännössä kaksi: **Väistöliikkeet** ja **Suojautuminen**.

### Väistöliikkeet
Hahmo voi yrittää tehdä itsestään hankalamman kohteen käyttämällä 1 toimintopisteen ja testaamalla **Väistöliikkeet** -taitoa. Testin lopputulos on tällöin uusi vaikeusaste kaikille hyökkäyksille kohdetta vastaan, mutta vaikeusaste on kuitenkin *vähintään* kantaman mukainen perusvaikeusaste.
Väistöliikkeet on voimassa kunnes hahmo toimii seuraavaksi. Väistöliikkeitä voi tehdä myös **Reaktiona**, jolloin hahmo viivyttää seuraavaa vuoroaan puolustautumalla.

### Suojautuminen
Paras tapa suojautua tuliaseilta on hakeutua suojaan. Suoja on kuitenkin parhaimmillaankin väliaikainen, mutta voi tarjota pienen hengähdyksen tiukan tulitaistelun keskellä.

Kun hahmo pystyy hyödyntämään suojaa, hän saa tietyn määrän **Suojapisteitä**. Näiden merkitsemiseen kannattaa käyttää vaikka jotain sopivia pelimerkkejä.

Suojapisteet **vähennetään** hahmoa kohtaan tehdyistä hyökkäyksistä. Mutta jos hyökkäys menee ohi, mutta olisi osunut ilman suojapisteitä, niin se osuu suojaan, jolloin hahmo menettää yhden **suojapisteen**. Suoja ei vahingoitu jos kohteeseen osutaan suojasta huolimatta.

Suojapisteet vaikuttavat ainoastaan hyökkäyksiin, jotka kohdistuvat suojan suuntaan, ja suojan voi kiertää jos pääsee selustaan. Jos hahmo on kokonaan suojan peitossa, niin hahmoon ei voi osua, ellei hyökkääjällä ole käytössään aseistusta, jolla pystyy läpäisemään suojan.

| Suoja                    | Suojapisteet |
| ------------------------ | ------------ |
| Flipattu baaripöytä      | 3            |
| Ohut, mutta korkea seinä | 2            |
| Alumiiniroskis           | 1            |
| Betoniporsas             | 4            |
| Betonipylväs             | 5            |
| Auton Ovi                | 2            |
| Paksu metalliovi         | 6            |


## Tulinopeus

Tulitaistelussa hyökkääjät räiskivät menemään yleensä niin paljon lyijyä kuin kykenevät. Hyökkäysten kannalta oleellista onkin aseiden **Tulinopeus**. Tulinopeus määritellään lukemalla, joka kertoo kuinka monta laukausta **sekunnissa** hahmo pystyy ampumaan. Teoreettinen tulinopeus, laukausta minuutissa voidaan siis helposti muuntaa peliin sopivaa muotoon jakamalla laukausta minuutissa luvulla 60, jos tällaisia nippelitietoja haikailee.

*Tulinopeus* on eri kuin aseen toimintopisteet, jotka määrittävät kuinka paljon suhteellista aikaa yhden toiminnon tekemiseen menee, ja siihen otetaan huomioon mm. kuinka hankala asetta on käyttää. Yhden hyökkäyksen aikana hahmo pystyy siis ampumaan tulinopeuden verran luoteja.

Hahmot saavat yleensä päättää montako ammusta aikovat ampua. Yleensä tämä on 1, tai maksimimäärä. Välimuodot harvemmin kannattavat, mutta hahmot voivat vapaasti toteuttaa itseään valitsemalla jotain siltä väliltä.

Tulinopeuden perusteella hahmo saa bonuksen hyökkäykseen, joka on +1 per 5 tulinopeus, ja tosiaan `osumien maksimimäärä = tulinopeus`.

| Tulinopeus      | 1    | 5    | 10    | 15   | 20   | 25   | 30   | 35   | 40   | 45   | 50+  |
| --------------- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- |
| Hyökkäyksen Etu | 0    | +1   | +2   | +3   | +4   | +5   | +6   | +7   | +8   | +9   | +10  |

### Minimitulinopeus

Tulinopeus voidaan merkitä muodoss `[minimi]-[maksimi]`, mikä tarkoittaa, että aseella täytyy ampua vähintään merkityn määrän laukauksia. Esim. `5-30` tarkoittaa, että jokaisten hyökkäyksen tulinopeus on oltava vähintään 5.

### Purskeet

Joillakin aseilla voidaan ampua lyhyitä **Purskeita** korkealla tulinopeudella, mikä parantaa osumatarkkuutta ja vahinkopotentiaalia. Purskeita ei kuitenkaan voi ampua peräkkäin ihan yhtä paljon, mutta niillä on helpompi saada kohtalainen määrä osumia.

Purskeet merkitään aseen minimitulinopeuden tavoin symbolilla `#` minimitulinopeuden kohdalle. Purske kuluttaa aina **kolminkertaisen** määrän ammuksia, mutta osumat tuplataan ja siitä saa +1 TRK normaalin tulinopeuden päälle. Pursketta ampuessa valitaan tulinopeus normaalisti, mutta maksimimäärä on indikoitu minitulinopeuden tavoin.

> [!Example] Esimerkki
> **Smichter P19 GT**:n tulinopeus on `2#-4`. Sillä voi ampua 1-2 pursketta, jolloin ase kuluttaa 3-6 ammusta, tai tehdä normaalin hyökkäyksen 1-4 ammuksella. 2 Pursketta antaa +1TRK purskeesta, mutta ei tarkkuutta tulinopeudesta, ja sillä voi saada 1-2 osumaa, jotka tuplataan, eli käytännössä 2 tai 4 osumaa. Aseen rekyyli on 1, joten neljään osumaan riittää OM 2.

### Jatkuva Sarjatuli
Jos hahmo ampuu täydellä tulinopeudella, on hänellä mahdollisuus jatkaa tulitusta maksamalla vain 1 toimintopiste. Kierroksen aikana voi ampua korkeintaan 4 täyttä sarjaa, mikä jatkuvalla sarjatulella tarkoittaisi aseen TP + 3 toimintopistettä.

Jatkuva sarjatuli voi jatkua seuraavalle kierrokselle, mutta välissä ei voi tehdä muita toimintoja, muuten täytyy maksaa täydet toimintopisteet.

## Osumat

Onnistunessa hyökkäyksessa osumien lukumäärään vaikuttaa **Onnistumisen Marginaali**, sekä aseen **Rekyyli.** Osumien lukumäärä on 1 + OM / Rekyyli. Eli ylimääräiseen osumaan tarvitaan rekyylin verran marginaalia.

Jokainen osuma antaa oman vahinkonopan, jotka sitten lasketaan yhteen.

> [!abstract] **Pahan Pekan tarina...**
> 
>
> Paha Pekka lataa lippaan täydeltä konepistoolilla motoristia. Motoristi on 6 metrin päässä Pekasta, ja Konepistoolin kantama on 15 metriä, joten Pekka on Lyhyellä kantamalla ja heittää vaikeusastetta 6 vastaan. Konepistoolin tulinopeus on 15, ja Pekka vetää täyden sarjan. Hän saa +4 bonuksen hyökkäykseen tulinopeudesta. Pekalla on Ampumataito 3, joten hän heittää kolmea noppaa: 9,8,7, ja lisää Räplänsä +1, saaden kokonaistuloksen 14. Motoristi yrittää väistöliikkeitä kahdella nopalla ja -2 haitalla, mutta saa vain 3, joten vaikeusaste on edelleen 6. Pekka osuu ja saa OM 8. Konepistoolin rekyyli on 2, mutta Pekka on vahva kaveri, joten hänen Ruhonsa +2 alentaa rekyylin 1:een joten Pekka saa yhteensä 9 osumaa motoristiin! Motoristilla on nahkarotsiin ommeltu teräslevyjä, joista hän saa Panssariluokan 2 luoteja vastaan. Konepistoolin Vahinkoluokka on 3, joten jäljelle jää vahinkoluokka 1, josta tulee vain 1d2 vahinkoa. Pekka heittää siis 8D2 vahinkoa ja saa: 1, 2, 2, 2, 2, 2, 1, 1, 2 eli yhteensä 15 vahinkoa! Motoristi lentää seinään ja veri roiskuu. Pekka heittää Vakavan lävistävän vamman motoristille: 9! Osuma lävistää sydämen. Motoristi kuolee välittömästi.

### Keskivahinko

Jos hahmo saa kerralla niin paljon osumia, että ei millään jaksaisi heittää kaikkia vahinkonoppia, varsinkin jos osumat joutuisi heittämään useassa erässä, niin taistelua voi nopeuttaa käyttämällä **keskivahinkoa**. Tällöin jokainen osuma tekee `VL + vahinkomuuttujat` vahinkoa, ja vahinko kerrotaan osumien lukumäärällä. Tämä yksinkertaistus sopii erityisen hyvin yhteen sarjatuliaseiden kanssa, ja silloin kun osumien määrä nousee erittäin korkeaksi.

Lopputulos on hyvin lähellä nopan keskiarvoa (jää vähän alle), mutta voi nopeuttaa peliä huomattavasti. Yleisesti ottaen pelaaja saa päättää haluaako heittää vahinkonoppansa, vai käyttää keskivahinkoa.

> [!info]
> On suositeltavaa, että keskivahinkoa käytetään aina kun vahinkoppien määrä on 6 noppaa tai enemmän.



> [!Example] Esimerkki
>
> Rat Bratz päästää 50 ammuksen sarjan Warrior-5 Minigun gatling-konekivääristään käytävää pitkin juokseviin vihollisiin ja saa 24 osumaa. Aseen Vahinkoluokka on L4+1 (Rat on modannut asettaan). Läpäisy 3 riittää läpäisemään kokonaan vihollisten panssarin, joten Rat tekee D8+1 vahinkoa per osuma. Rat jakaa 24 osumaansa 3 kohteen kesken, josta tulee 8 osumaa per kohde. Ratin pelaaja ei jaksa heitellä niin montaa noppaa, vaan käyttää keskivahinkoa: VL L4+1 keskivahinko on 5, joten jokainen kohde saa 5*8 = 40 vahinkoa. Eiköhän se ollut siinä...

### Lähietäisyys ja Osumat
**Lähietäisyydeltä** (1-2 metriä) käytettynä tuliaseet ovat murhaavan tehokkaita.

Sarjatuliaseissa jokainen ylimääräinen osuma lasketaan kaksinkertaisena, mutta osumien määrä ei voi ylittää aseen normaalia tulinopeutta.

Jos aseessa on osumakerroin, esim. haulikossa, joka käytää suosiluoti-ammuksia (buckshot), niin osumakerroin on tällöin kaksinkertainen, mikä kuvastaa sitä, että koko lyijymassa on helppo saada osumaan yhteen kohteeseen.

> [!Example] Esimerkki
> Spurgul on (taas) humaltuneena joutunut kärhämään paikallisten motoristien kanssa. Baarin pöydät on flipattu ja lyijykuuroja sataa joka suuntaan, ja meno on melko intensiivistä. Spurgul ei jaksa kykkiä pöydän takana, vaan päätää pinkaista baaritiskille, jonka takana kykkivä baarimikko harmillisesti sulki kaljahanat tulitaistelun alettua, ja Spurgulia janottaa. Spurgul ryntää baaritiskille, suoraan baarimikon iholle ja lasauttaa katkaistulla 3-piippuisella haulikollaan kaikki piiput tyhjäksi lähietäisyydeltä. Baarimikko on hämillään eikä osannut odottaa tätä. Spurgul heittää osumisen ja saa tulokseksi 9. Sehän riittää lähietäisyydeltä. Susihaulien x4 osumakerroin muuttuu lähietäisyydellä x8 osumaksi, ja kaiken lisäksi triplapiippu -erikoispiirre kolminkertaistaa osumat, joten Spurgul saa yhteensä 24(!!) osumaa. Baarimikolla on yllään Kriegerin BD-400 luotiliivit, joissa on PL 4, ja harmillisesti susihauleissa on -1 Läpäisy, jolloin PL nousee 5:een. Haulien VL 3 vähenee siis -2:een, josta tulee 1/4 vahinkoa. Siitä huolimatta 1/4 vahingollakin 24 osumaa tekee silti 6 haavapistettä vahinkoa. Baarimikon Kestävyys on 12, joten tämä riittää vakavaan vammaan, mutta koska panssari suodatti kaiken vahingon, muuttuu vahinkotyyppi Murskaavaksi: 4 -> Osuma selkään, selkäranka vaurioituu ja kohde on pökertynyt. 

## Harhaluodit

Harhaluodit voivat aiheuttaa sivullisia kuolemia, tai viedä hahmot tahtomattaan harmin tielle. Harhaluodit tarkistetaan joka hyökkäyksen jälkeen, mikäli vähintään yksi projektiili meni ohi kohteesta. Jos kaikki projektiilit osuivat kohteeseensa, ei harhaluoteja tarvitse tarkistaa.

Jokainen kohde, joka on harhaluotien määrittämällä osuma-alueella on riskinä ottaa harhaluodista. Laske suurpiirteinen ohi menneiden ammusten lukumärää, ja tämän perusteella määrittele kuinka monta harhaluotinoppaa pitää heittää. Osumia ei tarvitse laskea, eikä harhaluotinoppia muuttaa.

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

## Rekyyli

Mikäli aseessa on rekyyli suurempi kuin 1, sitä voi alentaa mikäli asetta käytetään tukevasti tuettuna, esimerkiksi jalustalta, tai hahmo on tarpeeksi voimakas. Tuki ja voimakkuus eivät päde saman aikaan, vaan ainoastaan paras etu lasketaan.

- Välttävästi tuettu ase: -1 rekyyli
- Hyvin tuetty ase: -2 rekyyli
- Voimakas Ruho: -1 rekyyli per +2 Ruho.


## Kriittiset osumat
Jos aseella ei ammuta sarjatulta, eli käytetään tulinopeutta 1-4, niin kriittinen onnistumien aiheuttaa **kriittisiä osumia**. Sarjatulta ampuessa kriittinen onnistuminen aiheuttaa jo heti enemmän osumia, joten ylimääräistä etua siitä ei lasketa.

Kriittisen osuman seurauksena vahinko kerrotaan **kriittisen kertoimella**. Eli jos sait triplakriittisen, niin teet triplavahingon, ja niin edelleen.

## Tähtäys
Hahmo voi käyttää 1-5 toimintopistettä tähtäykseen, jolloin hän saa +1 per toimintopiste välittömästi tähtäystä seuraavaan hyökkäykseen. Hän kuitenkin viivyttää vuoroaan tähtäyksen aikan, joten jos joku ehtii toimimaan häiritsevästi tässä välissä, hahmo menettää tähtäyksen edun. Varsinainen hyökkäys voi venyä seuraavalle kierrokselle, mutta hahmo joutuu kuitenkin päättämään heti kuinka monta pistettä aikoo käyttää tähtäykseen.

Kannattaa käyttää vaikka noppa (D6 toimii tähän hyvin) merkitsemään muistiin paljonko toimintopisteitä olit jo käyttänyt tähtäykseen. Jos hahmo haluaa ampua ennen kuin on käyttäny kaikki aikomansa pisteet, tulee hänen tehdä Vaikea **Taisteluvalmius**-testi, jossa onnistuessaan hän saa muuttaa suunnitelmiaan.

## Kriittinen Tähtäys
Hahmo voi yrittää tähdätä heikkoihin kohtiin kohteessa. Tämä on mahdollista vain, jos hahmo ampuu kertatulta, eli käyttää tulinopeutta 1, mutta myös jos hän ampuu [[Tulitaistelu#Purskeet|Purskeita]]. Tähdätessään heikkoihin kohtiin, Pelinjohtaja määrää muutoksen vaikeusasteeseen, riippuen siitä kuinka vaikea kyseiseen kohtaan on tähdätä.

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

Osumat toissijaisiin kohteisiin voidaan ratkaista esim. *harhaluodeilla*, tai mikäli se on haluttu efekti, niin hyökkääjä voi käyttää [[Tulitaistelu#Hyökkääminen|Hyökkäyksen]] **onnistumismarginaalia** ottaakseen ylimääräisen yliläpäisykohteen. Yliläpäisy voi jatkua myös toissijaisen kohteen jälkeen, mikäli vain läpäisyä riittää, mutta jokainen läpäisty kohde vähentää Läpäisyarvoa yhdellä.

> [!Example] Esimerkki
> **Driver** on karaistunut NWFL Troggi, joka joutuu puolustamaan ryhmäänsä hyökkäävältä laumalta mutanttisusipetoja keskellä erämaata. Driver on ladannut automaattihaulikkoonsa APN Panssarineula-ammuksia, ja lataa sarjan kohti hyökkäävää laumaa. Koirat tulevat kivassa letkassa kahdessa rivissä, joten Driver pyrkii osumaan kahteen letkan ensimmäiseen. Hyökkäysheitosta tulee 15 ja kohteet ovat optimaalisella kantamalla, joten Driver osuu OM 7. Hän käyttää 4 OM saadakseen kumpaankin kohteeseen toissijaisen Yliläpäisykohteen. Jäljelle jäävällä OM 3 hän saa toisen osuman. Kohteilla on PL 1 ja ammuksissa on LL 3, joten yliläpäisyyn jää (3 - 1 (PL) - 1 (yliläpäisy)) LL 1. Ammuksissa on x6 osuma-kerroin joten kumpikin ensisijainen kohde ottaa 6d4 vahinkoa. Ensimmäinen peto ottaa 16 vahinkoa ja toinen 15 vahinkoa. kumpikin pedoista kuolee osumiin. Yliläpäisyn kohteet ottavat kumpikin 3 osumaa LL 1, mikä riittää läpäisemään panssarin PL 1, joten kumpikin ottaa 3d4 vahinkoa: 9 ja 6 mikä riittää vakvaan ja toinen lievään vammaan. Vamma-heitoista tulee 6, 9. Kaksi koirista kuolee, kolmas tipahtaa ja vuotaa kuiviin, mutta neljäs jatkaa matkaansa, vaikkakin haavoittuneena.