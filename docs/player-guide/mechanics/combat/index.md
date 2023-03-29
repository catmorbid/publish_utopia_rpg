---
category: player-guide/mechanics/combat
share: true
---
# Taistelut

Utopia sijoittuu äärimmäisen väkivaltaiseen maailmaan, jossa kaikki turhat lait on korvattu itsevaltiaiden mielivaltaisilla säännöillä, tai täydellisellä anarkialla. Pelaajien on syytä jo tässä vaiheessa ymmärtää, että taistelut tulevat olemaan merkittävä osa peliä, ja on oleellista on ymmärtää miten helppoa pelissä on kuolla, joten eiköhän aloiteta siitä! Jos haluat ensin tietää miten hahmoja luodaan, tai lukea muita sääntöjä, niin voit lukea eteenpäin [[3-characters]] osiosta, ja palata tänne, kun ei enää pelota. Mutta tulet kyllä tutustumaan tähän osioon, tavalla tai toisella.

## Vahinko ja vammautuminen

Kun hahmot ottavat osumaa, toimitaan seuraavasti:

Aseilla on **Vahinkoluokka** ja **Läpäisykyky**, joita käytetään määrittämään kuinka paljon vauriota sillä voi saada aikaiseksi, ja kohteen **Panssariluokka** vähentää vahinkoa. Vahinkoluokan perusteella saadaan **Vahinkonoppa**.

### Vahinkoluokan laskeminen

- **Läpäisykyky** vähennetään kohteen **Panssariluokasta**. Panssariluokka voi vaihdella **Vahinkotyypin** mukaan.
	- **Negatiivinen Läpäisy** lisätään kohteen PL:ään, mikäli PL on 1 tai enemmän.
- **Panssariluokka** vähennetään hyökkääjän **Vahinkoluokasta**.
- Lopullisen vahinkoluokan perusteella perusteella saadaan **Vahinkonoppa.**
- Vahinkonop päälle lisätään **vahinkomuuttujat**, jos niitä on.

### Vahinkonopat ja -muuttujat

Vahinkoluokan perusteella saadaan Vahinkonoppa (ks. taulukko). Pelaajat voivat suoraan kirjoittaa ylös hyökkäystensä Vahinkonopan ja vahinkomuuttujan hahmolomakkeeseen helpottamaan laskemista, koska panssariluokka ainoastaan muuttaa vahinkonoppaa asteittain pienemmäksi.

> **Pahan Pekan tarina...**
>
> Motoristi pamauttaa nyrkkiraudalla Paha Pekkaa naamariin ja heittää hyökkäyksestään 9. Pekka oli päättänyt, että ei halua väistää, vaan käyttää Peruspuolustustaan, joka on vain 6. Motoristi osuu pekkaan marginaalilla 3. Nyrkkiraudan vahinkoluokka on M2, ja tämän päälle Motoristin **Ruhosta** tulee vielä +2, joten vahinkoluokka on  yhteensä 4. Pekalla on luotiliivit, joista kuitenkin tulee Murskaavaa vahinkoa vastaan vain Panssariluokka 1, mikä vähentää vahinkoluokan 3:een. Motoristi heittää 1D6 vahinkoa, ja saa tulokseksi 6! No nyt taisi sattua Pekkaa leukaan!

| Vahinkoluokka | Vahinkonoppa | min  | keskiarvo | max  |
| ------------- | ------------ | ---- | --------- | ---- |
| -4            | 1/16         | 0.06 | 0.06      | 0.06 |
| -3            | 1/8          | 0.13 | 0.13      | 0.13 |
| -2            | 1/4          | 0.25 | 0.25      | 0.25 |
| -1            | 1/2          | 0.5  | 0.5       | 0.5  |
| 0             | 1            | 1    | 1         | 1    |
| 1             | d2           | 1    | 1.5       | 2    |
| 2             | d4           | 1    | 2.5       | 4    |
| 3             | d6           | 1    | 3.5       | 6    |
| 4             | d8           | 1    | 4.5       | 8    |
| 5             | d10          | 1    | 5.5       | 10   |
| 6             | d12          | 1    | 6.5       | 12   |
| 7             | d8+d6        | 2    | 8         | 14   |
| 8             | 2d8          | 2    | 9         | 16   |
| 9             | d10+d8       | 2    | 10        | 18   |
| 10            | 2d10         | 2    | 11        | 20   |
| 11            | d12+d10      | 2    | 12        | 22   |
| 12            | 2d12         | 2    | 13        | 24   |

Pelaaja heittää yhden **vahinkonopan** per [[#Osumat]] ja laskee luvut yhteen. Jos vahinkonoppaan pätee **vahinkomuuttujia**, lisätään muuttujat kerrottuna osumien määrällä noppien summaan.

Vahinkoluokat seitsemästä (7) ylöspäin antavat toisen nopan. Tällöin heitetään kumpaakin noppaa osumien verran.

> **Esimerkki**
>
> **Anargil** ampuu sarjan Örkkimotoristiin, jolla on yllään metallipanssari. Anargilin konepistoolissa on on läpäisy 0 ja VL 4+2. Örkin PL on 3, joten Anargilin aseen vahinkoluokka on enää 1, eli hän heittää vahinkona 1D2+2 per osuma. Yhteensä 3 osumaa tarkoittaa, että Anargil aiheuttaa 3D2+6 vahinkoa örkkiin.

### Minimivahinko

Jos vahinkoluokka on 0 tai pienempi, niin ase tekee minimivahinkoa. Minimivahinko on 1 + vahinkomuuttujat. Jos vahinkoluokka laskee alle 0, niin minimivahinko puolitetaan joka askeleelta. Vaikka vahinko olisi alle 0, niin iso määrä osumia voi silti saada jotakin aikaan, jolloin se kannattaa laskea.

> [!Example]
> **Esimerkki**
> 
> Rat Bratz on nenäsillään voimahaarniskaan sonnustautuneen vihollisen kanssa. Hänellä on käsissään luotettu Warrior-5 minigun, ja hän päästää tyypilliseen tapaan täyden sarjan kohti vihollista. Rat on varustautunut panssarinläpäisevillä ammuksilla, joten aseessa on Läpäisy 4, mutta vahinko on vain L3+1 (rat on modannut asettaan). Rat saa hyökkäyksestään tulokseksi 33(!!), ja hän on optimaalisella kantamalla ja aseen rekyylin 1, joten vihollinen ottaa yhteensä peräti 25 osumaa. Kohteen Panssariluokka läpäisevää vahinkoa vastaan on kuitenkin 10, joten läpäisynkin kera lopputulos on -2, eli ase tekee vain minimivahinkoa. Minimivahinko on 2/4, eli 0.5 per osuma, joten yhteensä Rat tekee 12 vahinkoa kohteeseen. Koska osumia on aivan tolkuton määrä, on tämä ihan riittävästi Vakavaan Vammaan! Rat heittää vammasta 7. Kohde ottaa mittavia vaurioita sisäelimiin, tipahtaa koristen maahan ja pystyy ainoastaan ryömimään eteenpäin.
> 

### Haavapisteet ja vammat

Kun hahmo ottaa vahinkoa, merkitään vahinko ylös **Haavapisteinä**. Jos haavapisteet on vähintään yhtä paljon kuin hahmon **Kuntopisteet (KP)**, niin hahmo menettää tajuntansa, mutta tokenee kunhan haavapisteitä on vähemmän kuin hahmon *Kuntopisteitä*.

Jos hahmo ottaa kerralla tarpeeksi paljon vahinkoa, voi hän saada **Vammoja**. Vammarajat lasketaan hahmon muun [[Statistiikka|Statistiikan]] mukana, ja niihin vaikuttaa hahmon [[Statistiikka#Kestävyys|Kestävyys]].

**Lievät Vammat** hankaloittavat elämää, mutta ovat yleensä helposti parannettavissa. Lievästä vammasta tulee aina -1 haitta toimiin kivusta.

**Vakavat Vammat** ovat usein kuollettavia, tai vaikeuttavat elämää pysyvästi. Aivovauriot, tuhoutuneet raajat, jne. Vakavat vammat aiheuttavat aina -2 haitan toimiin kivusta ja särystä.

**Kuollettavat Vammat** aiheuttavat aina äkillisen kuoleman. Peli on ohi, eikun rollaamaan uutta hahmoa!

Vammojen lisäksi hahmon kuntoa mitataan [[Statistiikka#Kuntopisteet|Kuntopisteillä]], jotka määrittelevät kuinka pitkään hahmo pysyy toimintakykyisenä. Jos haavapisteitä on yhtä paljon tai enemmän kuin kuntopisteitä, niin hahmo menettää toimintakykynsä, eli useimmiten vaipuu tajuttomuuden tilaan.

On PJ:n ja pelaajien välinen asia, mitä he tekevät tajuttomilla hahmoilla, mutta yleensä siitä voi toipua helpohkosti.

Jos hahmo saa vamman, hän heittää nopalla vahinkotyypin mukaisesta taulukosta, vamman vakavuuden osoittamasta sarakkeesta. Vammat tulee kirjata ylös hahmolomakkeeseen, jotta voidaan myöhemin ratkaista niiden parantuminen.

> **Pahan Pekan tarina...**
>
> Pekalla on Kestävyys 16 (mikä on tosi hyvä!), joten hänen lievän vamman raja on 4 vahinkoa, ja vakavan 8. Motoristi osui Pekkaan tehden 6 pistettä vahinkoa, mikä ylittää lievän vamman rajan. Pekka heittää D10 vammastaan: 8. Pekka saa kovan iskun päähän ja menettää vähän vähäistä älyään (1 piste vauriota Dataan) ja on 1 kierroksen pökerryksissä. Tämä ei näytä hyvältä. Lähteeköhän kohta henki?

#### Murtumat

Murtumien taulukko.

Lievä murtuma antaa aina -1 kivusta, ja vakava murtuma -2 kivusta.

| D10  | Lievä Murtuma (-1)                                           | Vakava Murtuma (-2)                                          |
| ---- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| 1    | Ai, sattuu! 1d4 ylimääräistä vahinkoa.                       | Kivulias osuma, mutta mitään ei tainnut mennä rikki? Kärsit 1d10 vahinkoa. -1 kivusta. |
| 2    | Osuma jalkaan. -1 Notku.                                     | Toinen jalka murtuu pirstaleiksi. -3 Notku.                  |
| 3    | Osuma käteen. -1 Ruho.                                       | Käsi murskautuu ja on käyttökelvoton. -3 Ruho.               |
| 4    | Osuma selkään. Nyt meni hermoon! -1 Spiidi.                  | Selkäranka vaurioituu. 50% mahd. -3 Spiidi, tai halvaannut alaraajoista. 1 Kierros pökertynyt. |
| 5    | Kova tälli korvia pitkin. -1 Skarppi.                        | Tärykalvot puhkeavat iskun voimasta. -3 Skarppi. 1 Kierros pökertynyt. |
| 6    | No nyt osui nenään! Naama ei ole entisensä. -1 Pärstä.       | Kasvot ruhjoutuvat tunnistamattomiksi. Pärstä -3, Psyko -2. 1 Kierros pökertynyt. |
| 7    | Isku palleaan vie ilmat pihalle. Hahmo on 1 kierroksen pökerryksissä. | Kova isku keskiruumiseen. Kuolet 1D6 minuutissa sisäiseen verenvuotoon. 3 Kierrosta pökertynyt. |
| 8    | Kova isku päähän. -1 Data. 1 kierros pökertynyt.             | Saat vakavan aivovamman. -3 Data, -3 Karuus. Menetät tajunnan. |
| 9    | Suoraan silmään. Näkökyky menee 1D6 kierrokseksi.            | Nenä survoutuu aivoihin. Menetät tajunnan ja kuolet 1D6 kierroksessa. |
| 10   | Kova isku kalloon. Testaa Karaistuminen VA10, tai menetät tajunnan. | Osuma kalloon. Kallo menee murskaksi ja aivot roiskuvat pitkin katukivetystä. |

#### Lävistykset

Lävistysten taulukko

Lievä Lävistys antaa aina -1 kivusta, ja vakava Lävistys -2 kivusta.

| D10 | Lievä Lävistys (-1)                                                                                   | Vakava Lävistys (-2)                                                                                      |
| --- | ----------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------- |
| 1   | Pelkkä lihasvamma! Ota 1 HP vahinkoa.                                                                 | Osuma välttää pahimmat kohdat, mutta sattuu pirusti! Ota 1D4 vahinkoa.                                    |
| 2   | Ikävä viilto raajaan. Ota 1D4 lisää vahinkoa.                                                         | Osuma selkään. Spiidi -2.                                                                                 |
| 3   | Osuma kylkeen, henkeä ahdistaa. Spiidi -1.                                                            | Polvilumpio tuhoutuu. Liikkuminen vaikeutuu. Notku -2.                                                    |
| 4   | Korva repeytyy. Skarppi -1.                                                                           | Osuma lävistää keuhkot. Henki ei kulje! Ruho -3.                                                          |
| 5   | Osuma käteen. Verta tulee! Otat 1 HP vahinkoa per minuutti. Koitapa paikata itsesi piakkoin. Ruho -1. | Osuma kaulavaltimoon. Mittavaa verenvuotoa. Kuolontesti joka kierros.                                     |
| 6   | Osuma jalkaterään. Notku -1.                                                                          | Osuma lävistää kasvot. Et pysty puhumaan. Pärstä -1, Karuus -3.                                           |
| 7   | Osuma hartiaan. Ruho -1.                                                                              | Mittavia vaurioita sisäelimiin. Pystyt ainoastaan ryömimään eteenpäin. Kuolontesti joka kierros. Ruho -4. |
| 8   | Osuma jalkaan. Kovaa verenvuotoa. Kuolontesti kerran kohtauksessa. -2 Kivusta.                        | Raaja repeytyy irti. Kovaa verenvuotoa. Kuolontesti joka kierros. Ruho -4.                                |
| 9   | Osuma vatsaan. Vuodat kunnolla. Kuolontesti kerran kohtauksessa. -2 Kivusta.                          | Osuma lävistää sydämen. Kuolet välittömästi.                                                              |
| 10  | Osuma silmään. Silmä puhki. Ota 1D10 HP vahinkoa. -2 Skarppi.                                         | Osuma lävistää kalloon. Kuolet välittömästi.                                                              |

#### Palovammat

Palovammojen taulukko

Lievä palovamma antaa aina -1 kivusta, ja vakava palovamma -2 kivusta.

| D10  | Lievä Palovamma (-1)                                         | Vakava Palovamma (-2)                                        |
| ---- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| 1    | Polttaa! Ota 1D2 vahinkoa.                                   | Olet tuskissasi. Ota 1D10 vahinkoa ja -2 kivusta.            |
| 2    | Poltat kätesi. -1 Ruho.                                      | Tuli polttaa hermojasi. Lamaannut kivusta 1D4 kierrokseksi ja otat 1D10 vahinkoa ja -2 kivusta. |
| 3    | Poltat jalkasi. -1 Notku.                                    | Jalkasi palaa karrelle. -2 Notku, 1D6 vahinkoa.              |
| 4    | Poltat kasvosi. -1 Karuus.                                   | Kätesi palaa karrelle. -2 Räplä, 1D6 vahinkoa.               |
| 5    | Sokeudut. -2 Skarppi. Et näe mitään, ja tarvitset välitöntä ensiapua. | Keskiruumis palaa karrelle. -2 Ruho ja -2 pärstä. 1D6 vahinkoa. |
| 6    | Lahje syttyy tuleen. Ota 1 vahinko joka kierros, kunnes saat tulen sammumaan. Ota 1D4 vahinkoa. | Poltat kasvosi pahasti. Et ole enää entisensä. -2 Pärstä, -2 Psyko ja -2 Karuus. 1D8 vahinkoa. |
| 7    | Hiha syttyy tuleen. Ota 1 vahinko joka kierros, kunnes saat tulen sammumaan. Ota 1D4 vahinkoa. | Menetät molemmat silmäsi. -4 Skarppi ja -2 psyko. Et näe mitään. 1D8 vahinkoa. |
| 8    | Saat ikäviä palovammoja keskiruumiseen. Ota 1D6 vahinkoa. Ruho -1. | Tuli polttaa sisuskalujasi. Lyyhistyt ja huudat kivusta. Kuolet 1D10 kierroksessa, mutta jatkat huutamista koko tämän ajan. |
| 9    | Erittäin kivuliaita vammoja. Ota 1D10 vahinkoa. -1 kaikkiin toimiin kivusta. | Raajasi sulaa kuumuudessa, ja siitä jää jäljelle hiiltynyt luuranko. Olet tuskissasi. Ota 1D12 vahinkoa, ja -4 kivusta. |
| 10   | Leimahdat kunnolla liekkeihin! Ota 1D4 vahinkoa joka kierros, kunnes liekit on tukahdutettu. -2 kaikkiin toimiin kivusta. | Leimahdat liekkeihin ja hetken päästä sinusta jää hiiltynyt, kuollut kasa lihaa ja luita. Lähialueiden kannibaalit lipovat kieltään. |



## Paraneminen

Hahmo paranee levossa tai tajuttomana 1 haavapisteen per 4 tuntia. Yöunien aikana siis toipuu yleensä 2 pistettä. Lääkkeet nopeuttavat toipumista huomattavasti, joten niitä kannattaa ostaa aina vähän varastoon. Haavapisteiden parantaminen onkin usein triviaalia, mutta sen sijaan vammat voivat aiheuttaa paljonkin päänvaivaa.

Lievät vammat parantuvat noin 2 viikossa, jos niitä hoidetaan edes jotenkin. Vakavat vammat, mikäli niistä selviää hengissä, vievät helposti monta kuukautta toipumisaikaa, riippuen vaurioista. Lääketieteellä ja huippuluokan lääkkeillä, tämä aika saadaan toki minimoitua, mutta tämä tulee kalliiksi.

Jos vammaan voidaan tehdä sopiva toimenpide, niin voi käyttää listattua toipumisaikaa, jonka jälkeen vamma ei enää aiheuta haittaa. **Kykyvauriot** tulee hoitaa erikseen.

**Kykyvauriot** ovat **pysyviä**, ellei niitä hoideta kirurgisesti ja/tai kuntoutuksella.

Jos hahmo menettää raajan, niin raaja voidaan korvata kirurgisesti bioproteesilla, tai kyberneettisellä proteesilla.


| Ongelma                  | Korjaustoimenpide                                                                      | Hinta | TEK | Toipumisaika |
| ------------------------ | -------------------------------------------------------------------------------------- | ----- | --- | ------------ |
| -                        | Perustoimenpiteet joilla estetään tulehdukset (siteet, lääkkeet jne.)                  | 200   | 1   | 2d6 vrk      |
| Kova verenvuoto          | Kovan verenvuodon (esim. valtimo) tyrehdytys. Korvaava veriplasma.                     | 1000  | 1   | 3d10 vrk     |
| Sisäinen verenvuoto      | Sisäisen verenvuodon korjaus. Vaatii kirurgiaa                                         | 6000  | 2   | 3d8 vrk      |
| Lieviä Sisäelinvaurioita | Kirurgiset toimenpiteet ja kohdennettu lääkitys.                                       | 3000  | 2   | 3d6 vrk      |
| Vakavia Sisäelinvauroita | Bioproteesin asennus. Kirurginen toimenpide.                                           | 5000  | 3   | 3d6 vrk      |
| Tuhoutunut silmä/korva   | Tuhoutuneen silmän/korvan korjaus. Bioproteesin asennus. Näkökyky palautuu hiljalleen. | 10000 | 3   | 3d10 vrk     |
| Tuhoutunut käsi          | Uuden bioproteesin regenerointi ja asennus                                             | 7000  | 3   | 3d8 vrk      |
| Lievät Palovammat        | Ihon regenerointi kantasoluterapialla.                                                 | 5000  | 3   | 3d6 vrk      |
| Vakavat Palovammat       | Pitkä ja hankala kantasoluhoito iholle ja kehonsisäisten palovammojen hoito.           | 15000 | 3   | 3d10 vrk     |


### Kykyvauriot

Hahmo voi vammojen seurauksena, tai jotakin muuta kautta kärsiä **kykyvaurioista**. Kykyvaurio kohdistuu yhden kyvyn lukemaan, ja lukeman kautta voi siis myös vaikuttaa *kykyarvoon*. Kykyvaurio voidaan ilmaista esimerkiksi muodossa: `-1 Notku`, jolloin tämä tarkoittaa 1 pistettä kykyvauriota Notkun **lukemaan**.

Kykyvauriot merkitään hahmolomakkeeseen kyvyn kohdalle. Jos hahmo ottaa kymmenen pistettä kykyvauriota mihin tahansa kykyyn, niin hän rampautuu pysyvästi.

Kykyvaurion vaikutus on **pysyvä**, eli hahmon kyky heikkenee ilmaistun lukeman verran. Kykyvaurioita voi onneksi pyrkiä paikkamaan lääketieteellisin keinoin, ja toki on mahdollista, että hahmo aina treenaa itsensä takaisin kuntoon, jolloin hänen siis tulee käyttää kokemuspisteitä kykyjensä nostamiseksi taas. Jos hahmo nostaa kykyjään kokemuspisteillä, kun hänellä on kykyvauriota, niin hän poistaa ensin kykyvauriot, ja vasta kun kaikki kykyvauriot on poistuneet, hän voi nostaa kykyä paremmaksi kuin se oli ennen vauriota.

Kykyvaurioita voi yrittää parannella hankkiutumalla asiantuntevaan hoitoon, mutta hoito ottaa aikansa ja maksaa rahaa. Toipumisaikana tulee olla vuodelevossa, ja välttää liiallista aktiviteettia. Jos kaikkia vaurioita ei saatu korjattua, joutuu hahmo odottamaan, että on toipunut ennen kuin voi astua uudelleen leikkurin pöydälle. Jokainen vauroitunut kyky vaatii oman operaationsa.

| Hoidon laatu   | Kykyvaurion korjaaminen                                | TEK | Hinta | Toipumisaika |
| -------------- | ------------------------------------------------------ | --- | ----- | ------------ |
| Lihanleikkaaja | Kyky paranee 1d4-2 pisteellä. Se voi siis myös laskea! | 0   | 500   | 3d10 vrk     |
| Amatöörimaista | Kyky paranee 1d4-1 pistettä.                           | 1   | 1000  | 3d8 vrk      |
| Ammattimainen  | Kyky paranee 1d6 pistettä                              | 2   | 2000  | 3d6 vrk      |
| Laadukas       | Kyky paranee 2d4 pistettä                              | 3   | 4000  | 3d4 vrk      |
| Eliitti        | Kyky paranee 2d6 pistettä                              | 4   | 5000  | 2d6 vrk      |
| Huippulaatua   | Parantaa kaikki kykyvauriot                            | 5   | 6000 | 1d6 vrk      | 

### Nanolääketiede
Voit ostaa minkä tahansa operaation **Nanolääketieteellisenä** hoitona, jossa nanobotit hoitavat vaurioiden korjauksen, mutta näissä hinta on kaksinkertainen ja **TEK 4**, mutta toipumisaika on ilmoitetun ajan **minimiaika**. Eli toipumisaika 3d8 vrk olisi vain 3 vrk.

## Taistelukierrokset

Taistelu jaetaan kierroksiin. Yksi kierros vastaa noin 6 sekuntia pelin maailmassa. Yhden kierroksen aikana kukin osallistuja saa toimia niin monta kertaa kuin ehtii **Toimintopisteidensä** puitteissa. Lähtökohtaisesti taistelut alkavat siitä, että joku **tekee aloitteen**, eli julistaa ensimmäisen toiminnon. Aloitteen tekijällä on aina etulyöntiasema, mutta muut toimijat voivat yrittää väliin, mikäli ovat tietoisia siitä, että nyt alkaa tapahtua. Siksi taistelun alkaessa määritetään aina **Aloite**, mikä määrää sen kuka saa tehdä taistelun *ensimmäisen* toiminnon.

Aloitetta varten testataan **Taistelureaktiot**-taitoa. Paras lukema voittaa. Aloitteentekijä saa aina +2 edun toimintoonsa. Jos hahmo joutuu yllätetyksi, ei hän saa heittää aloitetta lainkaan, vaan häviää sen automaattisesti.

Ensimmäisen **toiminnon** jälkeen edetään siinä järjestyksessä kenellä on eniten **toimintopisteitä**. Jos hahmoilla on saman verran toimintopisteitä, voit verrata hahmojen Spiidi-kykyä, ja toimia suurimman Spiidin mukaisessa järjestyksessä. Jos yhdellä hahmolla on niin paljon toimintopisteitä, että hän on jatkuvasti muita taistelijoita edellä, saa hän tosiaan toimia aina kun hänellä on eniten toimintopisteitä. Tämä voi kuulostaa epäreilulta, mutta niin se vaan menee.

Jokaisen toiminnon jälkeen hahmo vähentää toimintopisteistään toiminnon pistemäärän verran. Niin sanottu "standardi" toiminto on 2 pistettä. Tämä antaisi keskivertohahmolle 2 toimintoa joka kierroksessa.

Toimintopisteitä voi **säästää**: Jokainen 2 säästettyä toimintopistettä säästää ensikierrokselle yhden toimintopisteen.

Uuden kierroksen alettua hahmon toimintopisteet nollautuvat lukemaan: Toimintopisteet + Säästetyt toimintopisteet / 2.

| Toiminto         | TP  | Kuvaus                                    | Testi                             |
| ---------------- | --- | ----------------------------------------- | --------------------------------- |
| Liikkuminen      | 1-5 | Hahmo voi liikkue liikenopeutensa verran. | `Urheilu`, jos tarvitaan          |
| Aseeton hyökkäys | 2   | Hahmo voi hyökätä ilman aseita             | `Taistelulajit` tai `Nyrkkitappo` |
| Melee hyökkäys   | 2-4 | Hahmo voi hyökätä lähitaisteluaseella | `Taistelulajit`              |
| Vastahyökkäys | 2-4 | Puolustus ja hyökkäys lähitaistelussa | `Taistelulajit` |
| Ampuminen        | 2-5 | Hahmo voi ampua kohdetta | `Ampumataito` |
| Väistäminen | 2 | Hahmo pyrkii väistämään hyökkäyksen | `Väistäminen` |
| Suojautuminen | 1 | Hahmo hyödyntää läheistä suojaa | Ei testiä. |



> **Pahan Pekan tarina...**
>
> Motoristilla oli kierroksen alussa 4 toimintopistettä, joista hän käytti jo 2 pistettä Pahan Pekan iskun väistämiseen, ja saikin ilmaisen iskun. Paha Pekka puolestaan menetti loput kierroksestaan, jouduttuaan pökerryksiin. Motoristi voi siis toimia uudestaan, ja päättää pamauttaa nyrkkiraudalla pökerryksissä olevaa Pekkaa naamaan. Motoristi heittä kolmella nopalla 9,8,4 josta paras on 9, ja tähän tulee -3 motoristin kyvyistä ja humalatilasta.  Lopputulos 6 on enemmän kuin Pekan peruspuolustus 5, joten Motoristi Osuu. Taas. Hän heittää vahingon D6:lla (se laskettiin, jo, joten ei tarvitse laskea uudestaan) ja saa tulokseksi 2 pistettä vahinkoa. Tästä ei tule vammaa, mutta Pekan HP tippuu nolliin, ja hän menettää tajuntansa.

## Tulitaistelu

Tulitaistelussa luodit lentelevät ympäriinsä ja kuolema korjaa nopeasti. Harhaluodit ovat tappavia ja sivullisilta uhreiltakin on vaikea välttyä. Tulitaistelut ovat usein erittäin nopeasti ohi, ja usein jo ensimmäinen taistelukierros on ratkaiseva.

### Hyökkäys ampuma-aseella

Hyökkäysheitot ratkaistaan testaamalla `Ampumataitoa`. Vaikeusasteena on hyökkääjän ja kohteen välisen etäisyyden perusteella määrittyvä **Kantama**. Onnistumisen Marginaalilla voidaan ostaa **Efektejä**, eli käytännössä joko enemmän osumia, tai pyrkiä tarkempaan osumaan. Yleisesti ottaen nyrkkisääntönä voi pitää, että sarjatuliaseilla otetaan lisää osumia, kun taas kertalaukauksilla, tai puoliautomaattisilla aseilla voidaan pyrkiä tarkkoihin osumiin.

- **Ylimääräinen osuma**: +1 osuma per Rekyyli OM.
- **Ylimääräinen kohde**: Saat jakaa osumia myös toiseen kohteeseen. Huom. vaatii vähintään 2 osumaa.
- **Yliläpäisyn kohde:** 2 OM. Mikäli käytetään [[#Yliläpäisy]]-sääntöä, toissijainen kohde saa puolet ensisijaisen kohteen osumista.
- **Tarkka osuma**: +/- 1 vammaheiton tulokseen per 4 OM.

> **Pahan Pekan tarina...**
>
> Paha Pekka herää sivukujalta, roskiksesta, jonne hänet on raahattu menetettyään tajuntansa pubissa. Hän huomaa makaavansa useiden ihmisruhojen ja rotan raatojen seassa, kuolemankatku sieraimissaan, kärpästen ympäröimänä. Pekka kömpii ulos ja tonkii ruhoja ja löytää sisälmysten keskeltä vanhan konepistoolin, sekä vähän ammuksia. Vihasta soikeana hän ryömii ulos ja suuntaa pubin etuovelle. Paha Pekka astuu sisälle pubiin, ja etsii motoristin, jolta sai hetki sitten turpaansa, aikeenaan teloittaa vihamiehensä siihen paikkaan. Motoristi huomaa Pekan, tämän ollessa vain muutaman metrin päässä, mutta tässä kohtaa Pekka painaa jo liipaisimen pohjaan. Pekka heittää aloitteen +2 muutoksella. ja saa tulokseksi 12, kun taas yllätetty motoristi saa vain 7. Pekka saa ensimmäisen vuoron...

### Kantama

Aseen kantama määrittää hyökkäyksen perusvaikeusasteen. Kantama voidaan ilmoittaa muodossa `A-B` tai pelkkä `B`. Jälkimmäinen numero, tai ainoastaan yksi numero kertoo aseen **Optimaalisen Kantaman**, kun taas kaksi numeroa tarkoittaa, että ensimmäinen on **Minimikantama**, ja vasta toinen lukema optimalinen kantama.

Jos hahmo on lähempänä kuin **minimikantama**, on asetta vaikea käyttää hyökkäykseen, ja hyökkäyksen vaikeusaste on 10.

| Kantama                | Etäisyys (korkeintaan)              | Vaikeusaste | 50m  |
| ---------------------- | ----------------------------------- | ----------- | ---- |
| Minimikantamalla       | Korkeintaan ilmoitettu minimkantama | 10          |      |
| Lähietäisyys           | 1-3 metriä                          | 6           |      |
| Lyhyt kantama          | ½ Optimi                            | 8           | 25m  |
| Optimaalinen kantama   | Aseen ilmoitettu kantama            | 10           | 50m  |
| Pitkä kantama          | 2x Optimi                           | 12          | 100m |
| Erittäin pitkä kantama | 4x Optimi                           | 14          | 200m |
| Äärimmäinen kantama    | 8x Optimi.                          | 16          | 400m |
| Maksimikantama         | 16x Optimi.                         | 20          | 800m |


#### Tarkentimet
Aseissa voi olla tarkentimia, jotka antavat jonkinlaisen tarkennus-kertoimen. Tämä voi olla ilmaistu esim. muodossa `x20 tarkennin`. Tarkentimet mahdollistavat aseen käytön huomattavasti pidemmällä kantamalla, tarkentamalla kohdetta, mutta toisaalta pitkän kantaman päähän on silti vaikea ampua ja osua, kun pitää ottaa huomioon kaikenlaiset olosuhdetekijät.

Tarkennin vaikuttaa aseen kantamaan seuraavasti:
- Minimikantama = 1 x tarkennuskerroin, tai minikantama x tarkennuskerroin, kumpi vain on suurempi.
- Optimaalinen kantama = optimaalinen kantama * tarkennuskerroin.
- Jos etäisyys > aseen normaali maksimikantama (ilman kertoimia), vaikeusasteeseen lisätään +4.

Teoriassa tarkentimella voidaan osua hyvinkin pitkien etäisyyksien päästä.

>**Esimerkki**:
>Zodiac on linnoittautunut kerrostalon katolle tarkkuuskiväärin kanssa vaanimaan kohdetta, joka hänen tulee salamurhata. Tovin odoteltuaan Zodiac huomaa kohteensa, ja ottaa tämän jyvälle. Zodiacin SS-88 Sniper -kiväärissä on x5-kiikaritähtäin. Kohde on 1000 metrin päässä, mutta kiitos kiikaritähtäimen, kiväärin optimaalinen kantama on (60x5) 300m, joten kohde on _Erittäin pitkän kantaman_ päässä (vaikeusaste 12). 1000m on kuitenkin enemmän kuin aseen normaali maksimikantama (960m), joten vaikeusaste nousee neljällä ja on 16. Harmillisen haastavaa - mutta ei toki mahdotonta. Zodiac tähtää 2 toimintopisteellä (+2), ja heittää neljällä nopalla ampumataitoa: 6, 7, 9, 19, ja lisää skarppinsa +5 ja aseen tarkkuuden +3, jolloin lopputulos on peräti 29. Zodiac osuu marginaalilla 13. Kiväärin tulinopeus on 2 ja rekyyli 4, joten Zodiac valitsee ylimääräisen osuman ja 2x tarkka osuma, josta tulee +2 vammaheittoon. Kiväärin vahinko on hurja L7+1, ja Läpäisy 2. Kohteella on kuitenkin PL 5 panssari, mikä vähenee PL 3, ja vahinko vähenee L 6. Zodiac heittää 2D12 vahinkoa: 10, 12 = 15 vahinkoa! Aika paljon, mutta kohteella onkin Kestävyys 16, joten Zodiac jää yhden pisteen päähän tappavasta vammasta. Hän heittää kuitenkin vakavan lävistävän vamman +2 muuttujalla: 8+2 = 10. Toinen luodeista osuu kohdetta suoraan kalloon, ja kallo räjähtää sirpaleiksi, värjäten katukivetyksen punaiseksi. Zodiac alkaa pakkailla kamoja, ennen kuin poliisipiirin partiot eksyvät paikalle...

### Puolustautuminen

Tuliaseita vastaan on hankala puolustautua, ja vaihtoehtoja on käytännössä kaksi: **Väistöliikkeet** ja **Suojautuminen**.

#### Väistöliikkeet
Hahmo voi yrittää tehdä itsestään hankalamman kohteen käyttämällä 1 toimintopisteen ja testaamalla **Väistöliikkeet** -taitoa. Testin lopputulos on tällöin uusi vaikeusaste kaikille hyökkäyksille kohdetta vastaan, mutta vaikeusaste on kuitenkin *vähintään* kantaman mukainen perusvaikeusaste.
Väistöliikkeet on voimassa hahmon seuraavan vuoroon asti.

#### Suojautuminen
Paras tapa suojautua tuliaseilta on hakeutua suojaan. Suoja on kuitenkin parhaimmillaankin väliaikainen, mutta voi tarjota pienen hengähdyksen tiukan tulitaistelun keskellä.

**Suoja** kestää aina tietyn määrän osumia, ja jokainen osuma hahmoon osuu suojaan, mikäli hahmo on suojassa. Suojalla on **Panssariluokka**. Mutta sitä ei käytetä vahingon laskemiseen, vaan ainoastaan sen laskemiseen, että vahingoittaako osuma suojaa vai ei. Jos PL on suurempi kuin aseen VL, niin ase ei vahingoita suojaa lainkaan.

Lisäksi suojalla voi olla **Kovuus**-arvo. Jos Aseen läpäisy ylittää Kovuus-arvon, niin suoja ei tehoa yhtä hyvin. Yleensä suoja kuitenkin auttaa vähentämään osumien määrää ihan vaan sillä, että se estää näkyvyyden kohteeseen, joten vaikka ammukset läpäisevät suojan, vain puolet osumista lasketaan. Jos hyökkääjä pystyy näkemään suojan materiaalin läpi, niin hänellä on silloin etulyöntiasema, ja kaikki osumat lasketaan normaalisti, jos ammus läpäisee suojan.

| Suoja                  | Osumat | PL  | Läpäisy |
| ---------------------- | ------ | --- | ------- |
| Puunrunko              | 15     | 1   | 1       |
| Auton ovi              | 5      | 1   | 0       |
| Kokonainen auto        | 30     | 2   | 2       |
| Flipattu toimistopöytä | 10     | 1   | 0       |
| Flipattu Metallipöytä  | 10     | 2   | 2       |
| Betoniporsas           | 10     | 3   | 2       |
| Betonipylväs           | 15     | 3   | 3       |
| Betoniseinä            | 20     | 4   | 3       |
| Paksu teräsovi         | 30     | 5   | 4       |

### Tulinopeus

Tulitaistelussa hyökkääjät räiskivät menemään yleensä niin paljon lyijyä kuin kykenevät. Hyökkäysten kannalta oleellista onkin aseiden **Tulinopeus**. Tulinopeus määritellään lukemalla, joka kertoo kuinka monta laukausta **sekunnissa** hahmo pystyy ampumaan. Teoreettinen tulinopeus, laukausta minuutissa voidaan siis helposti muuntaa peliin sopivaa muotoon jakamalla laukausta minuutissa luvulla 60, jos tällaisia nippelitietoja haikailee.

*Tulinopeus* on eri kuin aseen toimintopisteet, jotka määrittävät kuinka paljon suhteellista aikaa yhden toiminnon tekemiseen menee, ja siihen otetaan huomioon mm. kuinka hankala asetta on käyttää. Yhden hyökkäyksen aikana hahmo pystyy siis ampumaan tulinopeuden verran luoteja.

Hahmot saavat yleensä päättää montako ammusta aikovat ampua. Yleensä tämä on 1, tai maksimimäärä. Välimuodot harvemmin kannattavat, mutta hahmot voivat vapaasti toteuttaa itseään valitsemalla jotain siltä väliltä.

Tulinopeuden perusteella hahmo saa bonuksen hyökkäykseen, joka on +1 per 5 tulinopeus, ja tosiaan `osumien maksimimäärä = tulinopeus`.

| Tulinopeus      | 1    | 5    | 10    | 15   | 20   | 25   | 30   | 35   | 40   | 45   | 50+  |
| --------------- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- |
| Hyökkäyksen Etu | 0    | +1   | +2   | +3   | +4   | +5   | +6   | +7   | +8   | +9   | +10  |

#### Minimitulinopeus

Tulinopeus voidaan merkitä muodoss `[minimi]-[maksimi]`, mikä tarkoittaa, että aseella täytyy ampua vähintään merkityn määrän laukauksia. Esim. `5-30` tarkoittaa, että jokaisten hyökkäyksen tulinopeus on oltava vähintään 5.

#### Purskeet

Joillakin aseilla voidaan ampua lyhyitä **Purskeita** korkealla tulinopeudella, mikä parantaa osumatarkkuutta ja vahinkopotentiaalia. Purskeita ei kuitenkaan voi ampua peräkkäin ihan yhtä paljon, mutta niillä on helpompi saada kohtalainen määrä osumia.

Purskeet merkitään aseen minimitulinopeuden tavoin symbolilla `#` minimitulinopeuden kohdalle. Purske kuluttaa aina **kolminkertaisen** määrän ammuksia, mutta osumat tuplataan ja siitä saa +1 TRK normaalin tulinopeuden päälle. Pursketta ampuessa valitaan tulinopeus normaalisti, mutta maksimimäärä on indikoitu minitulinopeuden tavoin.

> [!Example] 
> **Smichter P19 GT**:n tulinopeus on `2#-4`. Sillä voi ampua 1-2 pursketta, jolloin ase kuluttaa 3-6 ammusta, tai tehdä normaalin hyökkäyksen 1-4 ammuksella. 2 Pursketta antaa +1TRK purskeesta, mutta ei tarkkuutta tulinopeudesta, ja sillä voi saada 1-2 osumaa, jotka tuplataan, eli käytännössä 2 tai 4 osumaa. Aseen rekyyli on 1, joten neljään osumaan riittää OM 2.

#### Jatkuva Sarjatuli
Jos hahmo ampuu täydellä tulinopeudella, on hänellä mahdollisuus jatkaa tulitusta maksamalla vain 1 toimintopiste.

### Osumat

Onnistunessa hyökkäyksessa osumien lukumäärään vaikuttaa **Onnistumisen Marginaali**, sekä aseen **Rekyyli.** Osumien lukumäärä on 1 + OM / Rekyyli. Eli ylimääräiseen osumaan tarvitaan rekyylin verran marginaalia.

Jokainen osuma antaa oman vahinkonopan, jotka sitten lasketaan yhteen.

> **Pahan Pekan tarina...**
>
> Paha Pekka lataa lippaan täydeltä konepistoolilla motoristia. Motoristi on 6 metrin päässä Pekasta, ja Konepistoolin kantama on 15 metriä, joten Pekka on Lyhyellä kantamalla ja heittää vaikeusastetta 6 vastaan. Konepistoolin tulinopeus on 15, ja Pekka vetää täyden sarjan. Hän saa +4 bonuksen hyökkäykseen tulinopeudesta. Pekalla on Ampumataito 3, joten hän heittää kolmea noppaa: 9,8,7, ja lisää Räplänsä +1, saaden kokonaistuloksen 14. Motoristi yrittää väistöliikkeitä kahdella nopalla ja -2 haitalla, mutta saa vain 3, joten vaikeusaste on edelleen 6. Pekka osuu ja saa OM 8. Konepistoolin rekyyli on 2, mutta Pekka on vahva kaveri, joten hänen Ruhonsa +2 alentaa rekyylin 1:een joten Pekka saa yhteensä 9 osumaa motoristiin! Motoristilla on nahkarotsiin ommeltu teräslevyjä, joista hän saa Panssariluokan 2 luoteja vastaan. Konepistoolin Vahinkoluokka on 3, joten jäljelle jää vahinkoluokka 1, josta tulee vain 1d2 vahinkoa. Pekka heittää siis 8D2 vahinkoa ja saa: 1, 2, 2, 2, 2, 2, 1, 1, 2 eli yhteensä 15 vahinkoa! Motoristi lentää seinään ja veri roiskuu. Pekka heittää Vakavan lävistävän vamman motoristille: 9! Osuma lävistää sydämen. Motoristi kuolee välittömästi.

#### Keskivahinko-kaava

Jos hahmo saa kerralla niin paljon osumia, että ei millään jaksaisi heittää kaikkia vahinkonoppia, varsinkin jos osumat joutuisi heittämään useassa erässä, niin taistelua voi nopeuttaa laskemalla käyttämällä **keskivahinko-kaavaa**. Tällöin jokainen osuma tekee `VL + vahinkomuuttujat` vahinkoa, ja vahinko kerrotaan osumien lukumäärällä.

Lopputulos on hyvin lähellä nopan keskiarvoa (jää vähän alle), mutta voi nopeuttaa peliä huomattavasti. Yleisesti ottaen pelaaja saa päättää haluaako heittää vahinkonoppansa, vai käyttää nopeaa laskukaavaa.



> **Esimerkki**
>
> Rat Bratz päästää 50 ammuksen sarjan Warrior-5 Minigun gatling-konekivääristään käytävää pitkin juokseviin vihollisiin ja saa 24 osumaa. Aseen Vahinkoluokka on L4+1 (Rat on modannut asettaan). Läpäisy 3 riittää läpäisemään kokonaan vihollisten panssarin, joten Rat tekee D8+1 vahinkoa per osuma. Rat jakaa 24 osumaansa 3 kohteen kesken, josta tulee 8 osumaa per kohde. Ratin pelaaja ei jaksa heitellä niin montaa noppaa, vaan käyttää keskivahinko-kaavaa. VL L4+1 keskivahinko on 5, joten jokainen kohde saa 5*8 = 40 vahinkoa. Eiköhän se ollut siinä...

### Harhaluodit

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

> **Esimerkki**
> 
> Neo on joutunut keskelle kahden katujengin tulitaistelua, ja piileskelee auton takana, kun huomaa, että sivukujalta ilmestyvä sinijää-narkkari ryntää häntä kohti suu sinisen vaahdon peitossa kirves kourassaan. Neo menee paniikkin, ja ryntää pakoon. Harmi vaan, että hän juoksee suoraan jengiläisten tulituksen keskelle.
> 
> PJ toteaa, että alueella on juuri vaihdettu erittäin suuri määrä luoteja, ja päättää harhaluotien määräksi n. 50, josta tulee 5 harhaluotinoppaa. PJ heittä 5D10: 3, 7, 5, 9, 8. Ampujat ovat noin 15m päässä Neosta, joten harhaluodin osumaluku on 7, eli Neo ottaa 3 osumaa! Osumien VL on 3, ja Neolla on PL 2 luotiliivit, joten hän saa 3D2 vahinkoa, josta tulee yhteensä 4 pistettä. Siitähän tulee lievä haava!
> 
> Koska sinijäänarkkari juokse Neon perään, niin tämäkin ottaa samanmoiset osumat: 10, 10, 6, 7, 1 - eli neljä (4) osumaa. Ilman panssaria tästä tulee 4D6 vahinkoa: PJ heittää 14 vahinkoa, mikä riittää vakavaan vammaan (Sinijää nostaa kestävyyttä melkoisesti). Narkkari ottaa osumaa polvilumpioon, ja tipahtaa, mutta jatkaa silti suu vaahdossa ryömien eteenpäin.

### Rekyyli

Mikäli aseessa on rekyyli suurempi kuin 1, sitä voi alentaa mikäli asetta käytetään tukevasti tuettuna, esimerkiksi jalustalta, tai hahmo on tarpeeksi voimakas. Tuki ja voimakkuus eivät päde saman aikaan, vaan ainoastaan paras etu lasketaan.

- Välttävästi tuettu ase: -1 rekyyli
- Hyvin tuetty ase: -2 rekyyli
- Voimakas Ruho: -1 rekyyli per +2 Ruho.


### Kriittiset osumat
Jos aseella ei ammuta sarjatulta, eli käytetään tulinopeutta 1-4, niin kriittinen onnistumien aiheuttaa **kriittisiä osumia**. Sarjatulta ampuessa kriittinen onnistuminen aiheuttaa jo heti enemmän osumia, joten ylimääräistä etua siitä ei lasketa.

Kriittisen osuman seurauksena vahinko kerrotaan **kriittisen kertoimella**. Eli jos sait triplakriittisen, niin teet triplavahingon, ja niin edelleen.

### Tähtäys
Hahmo voi käyttää 1-5 toimintopistettä tähtäykseen, jolloin hän saa +1 per toimintopiste välittömästi tähtäystä seuraavaan hyökkäykseen. Hän kuitenkin viivyttää vuoroaan tähtäyksen aikan, joten jos joku ehtii toimimaan häiritsevästi tässä välissä, hahmo menettää tähtäyksen edun. Varsinainen hyökkäys voi venyä seuraavalle kierrokselle, mutta hahmo joutuu kuitenkin päättämään heti kuinka monta pistettä aikoo käyttää tähtäykseen.

Kannattaa käyttää vaikka noppa (D6 toimii tähän hyvin) merkitsemään muistiin paljonko toimintopisteitä olit jo käyttänyt tähtäykseen. Jos hahmo haluaa ampua ennen kuin on käyttäny kaikki aikomansa pisteet, tulee hänen tehdä Vaikea **Taisteluvalmius**-testi, jossa onnistuessaan hän saa muuttaa suunnitelmiaan.

### Kriittinen Tähtäys
Hahmo voi yrittää tähdätä heikkoihin kohtiin kohteessa. Tämä on mahdollista vain, jos hahmo ampuu kertatulta, eli käyttää tulinopeutta 1, mutta myös jos hän ampuu [[#Purskeet|Purskeita]]. Tähdätessään heikkoihin kohtiin, Pelinjohtaja määrää muutoksen vaikeusasteeseen, riippuen siitä kuinka vaikea kyseiseen kohtaan on tähdätä.

Oletuksena vaikeusaste riippuu siitä millainen panssari kohteella on yllään.

Onnistuessaan heikkoon kohtaan tähdätty hyökkäys tekee automaattisesti kriittisen, joko x2 tai x3 kertoimella, riippuen ruumiinosasta ja vaikeusasteesta.

| Kohteen Panssari | Vaikeusaste (x2) | Vaikeusaste (x3) |
| ---------------- | ---------------- |:---------------- |
| Ei Panssaria     | +4               | +8               |
| Kevyt            | +6               | +10              |
| Keskiraskas      | +8               | +12              |
| Raskas           | +10              | +15              |

### Yliläpäisy
Jos oleellista, niin taistelussa voidaan huomioida **Yliläpäisy**, jolloin projektiilit voivat läpäistä yhden kohteen, ja osua toiseen kohteeseen sen takana. Yliläpäisy tapahtuu automaattisesti, mikäli aseessa on vähintään 1 piste läpäisyä jäljellä sen jälkeen kun läpäisy on vähentänyt panssarin nolliin. Tällöin ammus jatkaa matkaansa kohteen läpi, ja sen *efektiivinen läpäisy* on jäljellä oleva läpäisy.

Osumat toissijaisiin kohteisiin voidaan ratkaista esim. *harhaluodeilla*, tai mikäli se on haluttu efekti, niin hyökkääjä voi käyttää [[#Hyökkääminen|Hyökkäyksen]] **onnistumismarginaalia** ottaakseen ylimääräisen yliläpäisykohteen. Yliläpäisy voi jatkua myös toissijaisen kohteen jälkeen, mikäli vain läpäisyä riittää, mutta jokainen läpäisty kohde vähentää Läpäisyarvoa yhdellä.

> [!Example]
> **Driver** on karaistunut NWFL Troggi, joka joutuu puolustamaan ryhmäänsä hyökkäävältä laumalta mutanttisusipetoja keskellä erämaata. Driver on ladannut automaattihaulikkoonsa APN Panssarineula-ammuksia, ja lataa sarjan kohti hyökkäävää laumaa. Koirat tulevat kivassa letkassa kahdessa rivissä, joten Driver pyrkii osumaan kahteen letkan ensimmäiseen. Hyökkäysheitosta tulee 15 ja kohteet ovat optimaalisella kantamalla, joten Driver osuu OM 7. Hän käyttää 4 OM saadakseen kumpaankin kohteeseen toissijaisen Yliläpäisykohteen. Jäljelle jäävällä OM 3 hän saa toisen osuman. Kohteilla on PL 1 ja ammuksissa on LL 3, joten yliläpäisyyn jää (3 - 1 (PL) - 1 (yliläpäisy)) LL 1. Ammuksissa on x6 osuma-kerroin joten kumpikin ensisijainen kohde ottaa 6d4 vahinkoa. Ensimmäinen peto ottaa 16 vahinkoa ja toinen 15 vahinkoa. kumpikin pedoista kuolee osumiin. Yliläpäisyn kohteet ottavat kumpikin 3 osumaa LL 1, mikä riittää läpäisemään panssarin PL 1, joten kumpikin ottaa 3d4 vahinkoa: 9 ja 6 mikä riittää vakvaan ja toinen lievään vammaan. Vamma-heitoista tulee 6, 9. Kaksi koirista kuolee, kolmas tipahtaa ja vuotaa kuiviin, mutta neljäs jatkaa matkaansa, vaikkakin haavoittuneena.

## Lähitaistelu

### Hyökkäys Lähitaistelussa
Lähitaistelussa hyökkäys ratkaistaan testaamalla **Taistelulajit**, tai **Nyrkkitappo**-taitoja, vaikeusasteena kohteen **Peruspuolustus.**

**Nyrkkitappo**-taidolla voi ainoastaan hyökätä, mutta hahmo voi toki yrittää **Väistää** hyökkäystä tekemällä **Väistäminen**-testin. Väistön tulos on tällöin hahmon uusi puolustus-arvo.

**Taistelulajit**-taidolla voi pyrkiä myös tekemään **vastahyökkäyksen**, jolloin tehdäänkin [[core-mechanics#Vastakkaistesti|vastakkaistesti]], jonka voittaja onnistuu hyökkäyksessä, oli hän sitten alunperin hyökkääjä, tai puolustaja.

Hyvä onnistuminen mahdollistaa paremman lopputuloksen, ja hahmo voikin käyttää **Onnistumismarginaaliaan** seuraaviin efekteihin:

- **Lisävahinko:** +1 vahinkomuuttuja per 4 OM
- **Lisäosuma:** +1 osuma per 4 OM
- **Läpäisy:** +1 läpäisy per 4 OM
- **Kohdistettu hyökkäys:** Kohdistat hyökkäyksen tiettyyn ruumiinosaan. Jos aiheutat Vamman, voit muuttaa vamman tulosta +/- 1 per 4 OM. Saat täten enemmän valinnanvaraa ja mahdollisuuden tappavampiin, tai vähemmän tappaviin iskuihin.

### Lähitaistelun tekniikat
Eri taistelulajit mahdollistavat jonkin verran erilaisia taistelutekniikoita, joista tässä lisää. Käytetty tekniikka määrittelee hyökkäyksen vahingon.

#### Perustekniikka (kaikki)
Nyrkillä naamaan. Mikä voisi mennä pieleen? **Vahinkoluokka** on 1 + Ruho.

#### Paini (Nyrkkitappo)
Painissa pyritään saamaan vastustaja lukko-otteeseen, jossa vastustaja ei voi liikkua. Urheilupiireissä tämän jälkeen on tapana luovuttaa, mutta kadulla se yleensä tarkoittaa, että liikuntakyvytöntä pyritään vahingoittamaan eri keinoin lisää.

Paini vie 2 **Toimintopistettä**, ja se ratkaistaan aina vastakkaistestinä. Painin **Vahinkoluokka** on aina 0, mutta Painimatsin voittaja voi yrittää ilmaiseksi halutessaan joko **Vääntää**, tai **Murskata** kohdetta. Tällaisen tempauksen **Vahinkoluokka** on `Ruho+1`. Häviäjä on toimintakyvytön, kunnes voittaja päästää irti. Jos häviäjä käyttää **sisupisteen**, hän voi normaaleiden Sisun etujen lisäksi yrittää painia vastaan. Voittaja voi joka kierros yrittää **Vääntää** tai **Murskata** toimintakyvytöntä uhriaan.

## Räjähteet ja erikoiset aseet



