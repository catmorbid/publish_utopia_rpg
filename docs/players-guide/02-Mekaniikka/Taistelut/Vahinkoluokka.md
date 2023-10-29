§---
share: true
---
# Vahinkoluokka

Kun hahmot ottavat osumaa, toimitaan seuraavasti:

Aseilla on **Vahinkoluokka** ja **Läpäisykyky**, joita käytetään määrittämään kuinka paljon vauriota sillä voi saada aikaiseksi, ja kohteen **Panssariluokka** vähentää vahinkoa. Vahinkoluokan perusteella saadaan **Vahinkonoppa**.

- **Läpäisykyky** vähennetään kohteen **Panssariluokasta**. Panssariluokka voi vaihdella **Vahinkotyypin** mukaan.
	- **Negatiivinen Läpäisy** lisätään kohteen PL:ään, mikäli PL on 1 tai enemmän.
- **Panssariluokka** vähennetään hyökkääjän **Vahinkoluokasta**.
- Lopullisen vahinkoluokan perusteella perusteella saadaan **Vahinkonoppa.**
- Vahinkonopan päälle lisätään **vahinkomuuttujat**, jos niitä on.

## Panssariluokka ja Vahinkotyyppi
Pelissä on neljä erilaista vahinkotyyppiä:
- **[V]iiltävä** vahinko on terävien esineiden aiheuttamia viiltoja ja pistoja. Erilaiset lähitaisteluaseet tekevät usein viiltävää vahinkoa. Viiltävä vahinko aiheuttaa **Lävistyksiä ja Viiltoja.**
- **[L]ävistävä** vahinko on lähinnä luotien tai muiden nopeasti liikkuvien pienten esineiden aiheuttamaa ja se aiheuttaa **Lävistyksiä ja Viiltoja**
- **[M]urskaava** vahinko aiheuttaa **Murtumia**, useimmiten johtuen tylppien lyömäaseiden aiheuttamista iskuista
- **[P]olttava** vahinko aiheuttaa **Palovammoja**. Tuli ja kuumuus, mutta myös erilaiset energia-aseet tekevät Polttavaa vahinkoa.

Erilaiset hyökkäykset käyttävät yhtä edellämainituista vahinkotyypeistä, ja vastaavasti eri panssareilla on erilainen Panssariluokka kutakin vahinkotyyppiä kohtaan. Käytät siis aina aseen vahinkotyyppiä vastaavaa Panssariluokkaa kun lasket panssarin vaikutusta hyökkäykseen.
## Vahinkonopat ja -muuttujat

Vahinkoluokan perusteella saadaan Vahinkonoppa (ks. taulukko). Pelaajat voivat suoraan kirjoittaa ylös hyökkäystensä Vahinkonopan ja vahinkomuuttujan hahmolomakkeeseen helpottamaan laskemista, koska panssariluokka ainoastaan muuttaa vahinkonoppaa asteittain pienemmäksi.

> [!example] **Pahan Pekan tarina...**
>
> Motoristi pamauttaa nyrkkiraudalla Paha Pekkaa naamariin ja heittää hyökkäyksestään 9. Pekka oli päättänyt, että ei halua väistää, vaan käyttää Peruspuolustustaan, joka on vain 6. Motoristi osuu pekkaan marginaalilla 3. Nyrkkiraudan vahinkoluokka on M2, ja tämän päälle Motoristin **Ruhosta** tulee vielä +2, joten vahinkoluokka on  yhteensä 4. Pekalla on luotiliivit, joista kuitenkin tulee Murskaavaa vahinkoa vastaan vain Panssariluokka 1, mikä vähentää vahinkoluokan 3:een. Motoristi heittää 1D6 vahinkoa, ja saa tulokseksi 6! No nyt taisi sattua Pekkaa leukaan!

| Vahinkoluokka | Vahinko   | min    | avg    | max    |
| ------------- | --------- | ------ | ------ | ------ |
| -4            | 1/16      | 0.0625 | 0.0625 | 0.0625 |
| -3            | 1/8       | 0.125  | 0.125  | 0.125  |
| -2            | 1/4       | 0.25   | 0.25   | 0.25   |
| -1            | 1/2       | 0.5    | 0.5    | 0.5    |
| 0             | 1         | 1      | 1      | 1      |
| 1             | 1d2       | 1      | 1.5    | 2      |
| 2             | 1d4       | 1      | 2.5    | 4      |
| 3             | 1d6       | 1      | 3.5    | 6      |
| 4             | 1d8       | 1      | 4.5    | 8      |
| 5             | 1d10      | 1      | 5.5    | 10     |
| 6             | 1d12      | 1      | 6.5    | 12     |
| 7             | 1d8+1d6   | 2      | 8      | 14     |
| 8             | 2d8       | 2      | 9      | 16     |
| 9             | 1d10+1d8  | 2      | 10     | 18     |
| 10            | 2d10      | 2      | 11     | 20     |
| 11            | 1d12+1d10 | 2      | 12     | 22     |
| 12            | 2d12      | 2      | 13     | 24     |
| 13            | 1d10+2d8  | 3      | 14.5   | 26     |
| 14            | 2d10+1d8  | 3      | 15.5   | 28     |
| 15            | 3d10      | 3      | 16.5   | 30     |
| 16            | 1d12+2d10 | 3      | 17.5   | 32     |
| 17            | 2d12+1d10 | 3      | 18.5   | 34     |
| 18            | 3d12      | 3      | 19.5   | 36     |
| 19            | 3d10+1d8  | 4      | 21     | 38     |
| 20            | 4d10      | 4      | 22     | 40     |


Pelaaja heittää yhden **vahinkonopan** per Osuma ja laskee luvut yhteen: summa on hyökkäyksen lopullinen vahinko. Jos vahinkonoppaan pätee **vahinkomuuttujia**, lisätään muuttujat kerrottuna osumien määrällä noppien summaan.

Vahinkoluokat seitsemästä (7) ylöspäin antavat toisen nopan. Tällöin heitetään kumpaakin noppaa osumien verran.

> **Esimerkki**
>
> **Anargil** ampuu sarjan Örkkimotoristiin, jolla on yllään metallipanssari. Anargilin konepistoolissa on on läpäisy 0 ja VL 4+2. Örkin PL on 3, joten Anargilin aseen vahinkoluokka on enää 1, eli hän heittää vahinkona 1D2+2 per osuma. Yhteensä 3 osumaa tarkoittaa, että Anargil aiheuttaa 3D2+6 vahinkoa örkkiin.

## Minimivahinko

Jos vahinkoluokka on 0 tai pienempi, niin ase tekee minimivahinkoa. Minimivahinko on 1 + vahinkomuuttujat. Jos vahinkoluokka laskee alle 0, niin minimivahinko puolitetaan joka askeleelta. Vaikka vahinkoluokka olisi alle 0, niin iso määrä osumia voi silti saada jotakin aikaan, jolloin se kannattaa laskea.

> [!Example] **Esimerkki**
> 
> Rat Bratz on nenäsillään voimahaarniskaan sonnustautuneen vihollisen kanssa. Hänellä on käsissään luotettu Warrior-5 minigun, ja hän päästää tyypilliseen tapaan täyden sarjan kohti vihollista. Rat on varustautunut panssarinläpäisevillä ammuksilla, joten aseessa on Läpäisy 5, mutta vahinko on vain L4+1 (rat on modannut asettaan). Rat saa hyökkäyksestään tulokseksi 33(!!) ja sarjatuli pysyy hallinnassa, joten vihollinen ottaa yhteensä peräti 13 osumaa. Kohteen Panssariluokka läpäisevää vahinkoa vastaan on kuitenkin 10, joten läpäisynkin kera lopputulos on -1, eli ase tekee vain minimivahinkoa. Minimivahinko on 2/2, eli 1 per osuma, joten yhteensä Rat tekee 13 vahinkoa kohteeseen. Koska osumia on aivan tolkuton määrä, on tämä ihan riittävästi Vakavaan Vammaan! Rat heittää vammasta 7. Kohde ottaa mittavia vaurioita sisäelimiin, tipahtaa koristen maahan ja pystyy ainoastaan ryömimään eteenpäin.

>[!info] Vaihtoehtoinen sääntö: Minimivahingon vahinkotyyppi
>Jos hyökkäys tekee minimivahinkoa, niin hyökkäyksen vahinkotyyppi muuttuu, koska hyökkäys ei läpäise kohdetta riittävästi. Tämä vaikuttaa ainoastaan hyökkäyksen tekemiin vammoihin. Viiltävä ja Lävistävä vahinko muuttuu Murskaavaksi, mutta Polttava ja Murskaava vahinko pysyy entisellään.
## Vahinkoskaala
Tyypilliset vahinkoluokat on tarkoitettu henkilökohtaiseen välienselvittelyyn, eivätkä ne päde laisinkaan jos mukaan tulee isoja tykkejä, kuten panssarivaunuja, hävittäjiä, avaruusristeilijöitä, ja ties mitä muuta. Vahinkoluokka voidaan kuitenkin skaalata sujuvasti eri kokoiseen kärhämöintiin. Jos isommalla aseella ammutaan pienempää kohdetta, niin vahinkoon voidaan heittää skaalan mukainen kerroin. Samaten pienemmän skaalan aseilla jos pyritään vahingoittamaan isomman skaalan kohteita, jaetaan vahinko skaala-kertoimella. Samaten Panssariluokka on 4-kertainen pienemmän skaalan aseistusta vastaan.

| Skaala                  | Kerroin (vs. henk.koht.) | Esimerkkejä                                                 |
|-------------------------|--------------------------|-------------------------------------------------------------|
| Henkilökohtainen        | 1                        | Tyypillinen katukärhämöinti jengiläisten välillä            |
| Ajoneuvot               | 4                        | Motoristi-jengien välinen yhteenotto sotilasvoimien välillä |
| Suuret kulkuneuvot      | 16                       | Tankit, mechat, valtameriristeilijät, avaruusristeilijät    |
| Massiiviset kulkuneuvot | 64                       | Lentotukialukset, avaruusrahtialukset, avaruusasemat        |


> [!Example] Iso skaala vs. pieni skaala
>  **Ajoneuvo-luokan** aseissa on x4 skaala-kerroin ihmisenkokoisia kohteita vastaan, joten 20mm konekivääri, jossa on VL 5 tekisi 1d10x4 vahinkoa ihmisenkokoiseen kohteesen, kun taas ajoneuvoon kohdistettuna se on ihan vain 1d10. 


> [!Example] Pieni skaala vs. iso skaala
>  9mm konepistooli Ajoneuvoa vastaan tekee 1/4 vahingon. Jos ajoneuvossa on PL 1, niin konepistoolia vastaan se on PL 4, joten VL 3 vähenee VL -1:een, mikä tekee 1/2 vahinkoa per osuma. Hyökkääjä tekee 10 osumaa, joten läpi menee 5 pistettä. Tämä jaetaan vielä neljällä, joten kohteeseen tulee vain 1 piste vahinkoa.




[Vammat](./Vammat.md)