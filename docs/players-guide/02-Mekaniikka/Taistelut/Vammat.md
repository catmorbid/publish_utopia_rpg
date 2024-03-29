---
share: true
---
# Haavapisteet ja vammat

Vahinkonopilla heitetty lopullinen vahinko merkitään ylös **Haavapisteinä**. Jos hahmo on kärsinyt vähintään yhtä paljon haavapisteitä kuin hahmon **Kuntopisteet (KP)**, niin hahmo menettää toimintakykynsä, mutta tokenee kunhan haavapisteitä on vähemmän kuin hahmon *Kuntopisteitä*.

Jos hahmo ottaa kerralla tarpeeksi paljon vahinkoa, voi hän saada **Vammoja**. Vammautumisen **raja-arvot** lasketaan hahmon muun [Statistiikan](../../03-Hahmot/Statistiikka.md) mukana, ja niihin vaikuttaa hahmon [Kestävyys](../../03-Hahmot/Statistiikka.md#Kestävyys).

**Lievät Vammat** hankaloittavat elämää, mutta ovat yleensä helposti parannettavissa. Lievästä vammasta tulee aina -1 haitta toimiin kivusta.

**Vakavat Vammat** ovat usein kuollettavia, tai vaikeuttavat elämää pysyvästi. Aivovauriot, tuhoutuneet raajat, jne. Vakavat vammat aiheuttavat aina -2 haitan toimiin kivusta ja särystä.

**Kuollettavat Vammat** aiheuttavat aina äkillisen kuoleman. Peli on ohi, eikun rollaamaan uutta hahmoa!

Jos hahmo saa vamman, hän heittää nopalla vahinkotyypin mukaisesta taulukosta, vamman vakavuuden osoittamasta sarakkeesta. Jos käy tuuri ja jäät henkiin, niin vammat tulee kirjata ylös hahmolomakkeeseen, jotta voidaan myöhemin ratkaista niiden parantuminen.

> **Pahan Pekan tarina...**
>
> Pekalla on Kestävyys 16 (mikä on tosi hyvä!), joten hänen lievän vamman raja on 4 vahinkoa, ja vakavan 8. Motoristi osui Pekkaan tehden 6 pistettä vahinkoa, mikä ylittää lievän vamman rajan. Pekka heittää D10 vammastaan: 8. Pekka saa kovan iskun päähän ja menettää vähän vähäistä älyään (1 piste vauriota Dataan) ja on 1 kierroksen pökerryksissä. Tämä ei näytä hyvältä. Lähteeköhän kohta henki?

## Vaikutukset
Vammoilla on erilaisia vaikutuksia. Vamma itsessään on kivulias ja hankala, mutta jos siitä ei tule mitään mainittavia erikoisia vaikutuksia, niin sen vaikutukset jäävät esteettisiksi. Hoitamaton vamma kuitenkin altistaa hahmon uusille vammoille ja jokaisesta olemassaolevasta vammasta tulee +1 vammaheittoon samantyyppisiä vammoja vastaan. Samantyyppiseksi vammaksi lasketaan sellainen vamma, jossa on a) sama vahinkotyyppi ja b) sama vakavuus. Eli jos hahmo saa yhden lievän palovamman, niin se ei vaikuta vakavien palovammojen vakavuuteen, mutta toinen lievä palovamma on helposti pahempi.

### Kipu
Jos hahmon on **Kivuissaan**, kärsiin hän taistelun ulkopuolella Haitan kaikkiin fyysisiin ja älyllisiin toimiin. Jos hahmo on **Tuskissaan**, niin haitta pätee myös taistelussa. Kipua voi pyrkiä turruttamaan esim. lääkkeillä. Merkitse kipu rastittamalla asianmukainen laatikko hahmolomakkeessa.
### Pökertyminen
Pökertynyt hahmo saa -4 kaikkiin toimiinsa, ja hänellä on vain puolet Toimintopisteistä käytössä, ja hän voi ainoastaan yrittään liikkua, tai puolustautua edellämainituilla haitoilla. Lähitaistelussa pökertyneen kohteen Peruspuolustus puolitetaan.

### Kuolontesti
Kuolontestillä mitataan koska vakavat vauriot, kuten kova verenvuoto aiheuttaa kuoleman. Testaa erikseen mainituin väliajoin `Karaistumista`, vaikeustasolla 10. Jos epäonnistut testissä, niin hahmo kuolee. Taitava ensihoitaja voi saada tällaisen hahmo vielä elvyytettyä, mutta useimmiten peli on siinä kohta ohi.

### Kykyvauriot
Merkitse kyvyn kohdalle 1 piste kykyvauriota (9 pisteen ruudukko). Kykyvaurio vähentää välittömästi kyvyn arvoa, ja vaikutus on pysyvä, kunnes kykyvauriot on parannettu.

## Murtumat

Tylpät aseet, nyrkiniskut, taklaukset ja erilaiset murskaukset voivat aiheuttaa Murtumia. Murtumat eivät yleensä ole yhtä hengenvaarallisia kuin vaikka viiltohaavat, mutta ovat silti kaikenkaikkiaan ikäviä.

| D10 | Lievä Murtuma                                                         | Vakava Murtuma                                                                                  |
| --- | --------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------- |
| 1   | Ai, sattuu! 1d4 ylimääräistä vahinkoa.                                | Kivulias osuma, mutta mitään ei tainnut mennä rikki? Kärsit 1d10 vahinkoa.                      |
| 2   | Osuma jalkaan. -1 Notku.                                              | Toinen jalka murtuu pirstaleiksi. -3 Notku.                                                     |
| 3   | Osuma käteen. -1 Ruho.                                                | Käsi murskautuu ja on käyttökelvoton. -3 Ruho.                                                  |
| 4   | Osuma selkään. Nyt meni hermoon! -1 Spiidi.                           | Selkäranka vaurioituu. -3 Spiidi. 1 Kierros pökertynyt.                                         |
| 5   | Kova tälli korvia pitkin. -1 Skarppi.                                 | Tärykalvot puhkeavat iskun voimasta. -3 Skarppi. 1 Kierros pökertynyt.                          |
| 6   | No nyt osui nenään! Naama ei ole entisensä. -1 Karuus.                | Kasvot ruhjoutuvat tunnistamattomiksi. Karuus -3, Psyko -2. 1 Kierros pökertynyt.               |
| 7   | Isku palleaan vie ilmat pihalle. Hahmo on 1 kierroksen pökerryksissä. | Kova isku keskiruumiseen. Kuolet 1D6 minuutissa sisäiseen verenvuotoon. 3 Kierrosta pökertynyt. |
| 8   | Kova isku päähän. -1 Data. 1 kierros pökertynyt.                      | Saat vakavan aivovamman. -3 Data, -3 Karuus. Menetät tajunnan.                                  |
| 9   | Suoraan silmään. Näkökyky menee 1D6 kierrokseksi.                     | Nenä survoutuu aivoihin. Menetät tajunnan ja kuolet 1D6 kierroksessa.                           |
| 10  | Kova isku kalloon. Testaa Karaistuminen VA15, tai menetät tajunnan.   | Osuma kalloon. Kallo menee murskaksi ja aivot roiskuvat pitkin katukivetystä.                   |

## Viiltohaavat

Viiltävä ja Lävistävä vahinko voi aiheuttaa Viiltohaavoja.

| D10 | Lievä Viiltohaava                                                                                     | Vakava Viiltohaava                                                                                        | 
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

## Palovammat

Palovammojen taulukko

| D10 | Lievä Palovamma                                                                                                           | Vakava Palovamma                                                                                                                                 |
| --- | ------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------- |
| 1   | Polttaa! Ota 1D2 vahinkoa.                                                                                                | Olet tuskissasi. Ota 1D10 vahinkoa.                                                                                                |
| 2   | Poltat kätesi. -1 Ruho.                                                                                                   | Tuli polttaa hermojasi. Lamaannut kivusta 1D4 kierrokseksi ja otat 2D6 vahinkoa.                                                  |
| 3   | Poltat jalkasi. -1 Notku.                                                                                                 | Jalkasi palaa karrelle. -2 Notku, 1D6 vahinkoa.                                                                                                  |
| 4   | Poltat kasvosi. -1 Karuus.                                                                                                | Kätesi palaa karrelle. -2 Ruho, 1D6 vahinkoa.                                                                                                    |
| 5   | Sokeudut. -2 Skarppi. Et näe mitään, ja tarvitset välitöntä ensiapua.                                                     | Keskiruumis palaa karrelle. -2 Ruho ja -2 Psyko. 1D6 vahinkoa.                                                                                   |
| 6   | Lahje syttyy tuleen. Ota 1 vahinko joka kierros, kunnes saat tulen sammumaan. Ota 1D4 vahinkoa.                           | Poltat kasvosi pahasti. Et ole enää entisensä. -2 Psyko ja -2 Karuus. 1D8 vahinkoa.                                                              |
| 7   | Hiha syttyy tuleen. Ota 1 vahinko joka kierros, kunnes saat tulen sammumaan. Ota 1D4 vahinkoa.                            | Menetät molemmat silmäsi. -4 Skarppi ja -2 psyko. Et näe mitään. 1D8 vahinkoa.                                                                   |
| 8   | Saat ikäviä palovammoja keskiruumiseen. Ota 1D6 vahinkoa. Ruho -1.                                                        | Tuli polttaa sisuskalujasi. Lyyhistyt ja huudat kivusta. Kuolet 1D10 kierroksessa, mutta jatkat huutamista koko tämän ajan.                      |
| 9   | Erittäin kivuliaita vammoja. Ota 1D10 vahinkoa. -1 kaikkiin toimiin kivusta.                                              | Raajasi sulaa kuumuudesta, ja siitä jää jäljelle hiiltynyt luuranko. Olet tuskissasi. Ota 2D12 vahinkoa.                          |
| 10  | Leimahdat kunnolla liekkeihin! Ota 1D4 vahinkoa joka kierros, kunnes liekit on tukahdutettu. -2 kaikkiin toimiin kivusta. | Leimahdat liekkeihin ja hetken päästä sinusta jää hiiltynyt, kuollut kasa lihaa ja luita. Lähialueiden kannibaalit valmistautuvat grillijuhlaan. |

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

Hahmo voi vammojen seurauksena, tai jotakin muuta kautta kärsiä **kykyvaurioista**. Kykyvaurio kohdistuu yhteen kykyyn, ja vähentään aina välittömästi kyvyn arvoa vaurion verran. Kykyvaurio voidaan ilmaista esimerkiksi muodossa: `-1 Notku`, jolloin tämä tarkoittaa 1 pistettä kykyvauriota Notkun **lukemaan**.

Kykyvauriot merkitään hahmolomakkeeseen kyvyn kohdalle. Jos hahmo ottaa kymmenen pistettä kykyvauriota mihin tahansa kykyyn, niin hän rampautuu pysyvästi.

Kykyvaurion vaikutus on **pysyvä**, eli hahmon kyky heikkenee ilmaistun lukeman verran. Kykyvaurioita voi onneksi pyrkiä paikkamaan lääketieteellisin keinoin, ja toki on mahdollista, että hahmo aina treenaa itsensä takaisin kuntoon, jolloin hänen siis tulee käyttää kokemuspisteitä kykyjensä nostamiseksi taas. Jos hahmo nostaa kykyjään kokemuspisteillä, kun hänellä on kykyvauriota, niin hän poistaa ensin kykyvauriot, ja vasta kun kaikki kykyvauriot on poistuneet, hän voi nostaa kykyä paremmaksi kuin se oli ennen vauriota.

Kykyvaurioita voi yrittää parannella hankkiutumalla asiantuntevaan hoitoon, mutta hoito ottaa aikansa ja maksaa rahaa. Toipumisaikana tulee olla vuodelevossa, ja välttää liiallista aktiviteettia. Jos kaikkia vaurioita ei saatu korjattua, joutuu hahmo odottamaan, että on toipunut ennen kuin voi astua uudelleen leikkurin pöydälle. Jokainen vauroitunut kyky vaatii oman operaationsa.

| Hoidon laatu   | Kykyvaurion korjaaminen                                | TEK | Hinta | Toipumisaika |
| -------------- | ------------------------------------------------------ | --- | ----- | ------------ |
| Lihanleikkaaja | Kyky paranee 1d4-2 pisteellä. Se voi siis myös laskea! | 0   | 500   | 3d10 vrk     |
| Amatööri       | Kyky paranee 1d4-1 pistettä.                           | 1   | 1000  | 3d8 vrk      |
| Ammattilainen  | Kyky paranee 1d6 pistettä                              | 2   | 2000  | 3d6 vrk      |
| Laadukas       | Kyky paranee 2d4 pistettä                              | 3   | 4000  | 3d4 vrk      |
| Eliitti        | Kyky paranee 2d6 pistettä                              | 4   | 5000  | 2d6 vrk      |
| Huippulaatua   | Parantaa kaikki kykyvauriot                            | 5   | 6000  | 1d6 vrk      |

### Nanolääketiede
Voit ostaa minkä tahansa operaation **Nanolääketieteellisenä** hoitona, jossa nanobotit hoitavat vaurioiden korjauksen, mutta näissä hinta on **nelinkertainen** ja **TEK 4**, mutta toipumisaika on ilmoitetun ajan **minimiaika**. Eli toipumisaika 3d8 vrk olisi vain 3 vrk.