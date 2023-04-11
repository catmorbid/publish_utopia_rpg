---
share: true
---
# Lähitaistelu

## Hyökkäys Lähitaistelussa
Lähitaistelussa hyökkäys ratkaistaan testaamalla **Taistelulajit**, tai **Nyrkkitappo**-taitoja, vaikeusasteena kohteen **Peruspuolustus.**

**Nyrkkitappo**-taidolla voi ainoastaan hyökätä, mutta hahmo voi toki yrittää **Väistää** hyökkäystä tekemällä **Väistäminen**-testin. Väistön tulos on tällöin hahmon uusi puolustus-arvo.

**Taistelulajit**-taidolla voi pyrkiä myös tekemään **vastahyökkäyksen**, jolloin tehdäänkin [[../Ydinmekaniikka#Vastakkaistesti|vastakkaistesti]], jonka voittaja onnistuu hyökkäyksessä, oli hän sitten alunperin hyökkääjä, tai puolustaja.

Hyvä onnistuminen mahdollistaa paremman lopputuloksen, ja hahmo voikin käyttää **Onnistumismarginaaliaan** seuraaviin efekteihin:

- **Lisävahinko:** +1 vahinkomuuttuja per 4 OM
- **Lisäosuma:** +1 osuma per 4 OM
- **Läpäisy:** +1 läpäisy per 4 OM
- **Kohdistettu hyökkäys:** Kohdistat hyökkäyksen tiettyyn ruumiinosaan. Jos aiheutat Vamman, voit muuttaa vamman tulosta +/- 1 per 4 OM. Saat täten enemmän valinnanvaraa ja mahdollisuuden tappavampiin, tai vähemmän tappaviin iskuihin.

## Lähitaistelun tekniikat
Eri taistelulajit mahdollistavat jonkin verran erilaisia taistelutekniikoita, joista tässä lisää. Käytetty tekniikka määrittelee hyökkäyksen vahingon.

### Perustekniikka (kaikki)
Saapasta munille, nyrkillä naamaan ja lopuksi polvella nenään. Mikä voisi mennä pieleen? Perustekniikka on yksinkertainen voimaan ja kokoon pohjautuva tapa tuottaa vauriota aseettomassa taistelussa.
**Vahinkoluokka:** $1+Ruho$
**Toimintopisteet:** 2

### Paini (Nyrkkitappo)
Painissa pyritään saamaan vastustaja lukko-otteeseen, jossa vastustaja ei voi liikkua. Urheilupiireissä tämän jälkeen on tapana luovuttaa, mutta kadulla se yleensä tarkoittaa, että liikuntakyvytöntä pyritään vahingoittamaan eri keinoin lisää.
**Vahinkoluokka:** 0, **Murskaus/Vääntö:** $Ruho$
**Toimintopisteet:** 2

Paini vie 2 **Toimintopistettä**, ja se ratkaistaan aina vastakkaistestinä. Painin **Vahinkoluokka** on aina 0, mutta Painimatsin voittaja voi yrittää ilmaiseksi halutessaan joko **Vääntää**, tai **Murskata** kohdetta. Tällaisen tempauksen **Vahinkoluokka** on $Ruho$. Häviäjä on toimintakyvytön, kunnes voittaja päästää irti. Jos häviäjä käyttää **sisupisteen**, hän voi normaaleiden Sisun etujen lisäksi yrittää painia vastaan. Voittaja voi joka kierros yrittää **Vääntää** tai **Murskata** toimintakyvytöntä uhriaan.

### Ninjapotku (Karate, Neo-Judo, Doi-K'han)

> [!quote]
> Joku naseva sitaatti tähän

Ninjapotku on nopea potkutekniikka, joka voi olla melko tehokas pienenkin rääpäleen käsissä, koska sillä pyritään hyödyntämään voiman sijasta nopeutta. Tehokkuudessaan se ei pärjää muille iskutekniikoille, mutta on parempi kuin ei mitään.
**Vahinkoluokka:** $2+\frac{Notku}{2}$
**Toimintopisteet:** 2

### Väkipotku (Karate)
Karaten vahvuutena on väkevät potkut, joihin saadaan mukaan valtavasti voimaa. Tällainen hyökkäys voi lamaannuttaa isonkin kohteen, mutta tekniikan hallitseminen vaatii kokonaisvaltaista kehon hallintaa.
**Vahinkoluokka:** $Ruho+Notku-4$
**Toimintopisteet:** 3


### Väkilukko (Neo-Judo)
Väkilukot ovat Neo-Judon väkeviä tekniikoita, joilla taltutetaan isotkin körmyt. Onnistuessaan väkilukolla kohteen saan niin hyvään solmuun, että tämä ei kykene laisinkaan toimimaan aiheuttamatta itselleen suunnatonta kipua.
**Vahinkoluokka**: 6, vahinko pätee ainoastaan, jos kohde pyrkii liikkumaan tai pyristelemään irti lukosta.
**Läpäisy:** 4
**Toimintopisteet**: 4
**Erikoista**: Väkilukon vaikeusaste on kohteen $Puolustus + 4$. Jos lukko onnistuu, niin kohde ottaa vahinkoa joka kerta kun tämä pyrkii irtautumaan lukosta. Irtautua voi yrittää vain voimalla, tekemällä `Urheilu`-testin, tai käyttämällä `Pako`-taitoa. Mutta vaikeusasteena on alkuperäinen Neo-Judon toiminnon hyökkäyksen aste.

### Varjoisku (Doi-K'han)
Mystisen varjotekniikan kulmakivi on yksinkertainen varjohyökkäys, jossa taistelija kanavoi sisäistä energiaansa niin nopeaan iskuun, että sitä on lähes mahdoton havaita paljaalla silmällä. Taistelija voi tehdä iskun nopeana salamaiskuna, tai käyttää siihen enemmän aikaa. Mitä enemmän toimintopisteitä taistelija käyttää iskuun, sitä enemmän vahinkoa hän saa aikaan. Tekniikka on kuitenkin mielelle rasittavaa, ja jokainen käytetty TP antaa yhden [[../../3-Hahmot/Kuormitus|kuormituspisteen]].

**Vahinkoluokka:** $TP*2+Psyko/2$
**Toimintopisteet:** 1-3
**Erikoista:** Puolustautuminen hyökkäystä vastaan -2 haitalla. 1 Kuormituspiste per käytetty TP.

