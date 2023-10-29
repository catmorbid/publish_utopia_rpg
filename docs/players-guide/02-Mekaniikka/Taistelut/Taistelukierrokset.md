---
share: true
---
# Taistelukierrokset

Taistelu jaetaan kierroksiin. Yksi kierros vastaa noin 6 sekuntia pelin maailmassa. Yhden kierroksen aikana kukin osallistuja saa toimia niin monta kertaa kuin ehtii **Toimintopisteidensä** puitteissa. Lähtökohtaisesti taistelut alkavat siitä, että joku **tekee aloitteen**, eli julistaa ensimmäisen toiminnon. Aloitteen tekijällä on aina etulyöntiasema, mutta muut toimijat voivat yrittää väliin, mikäli ovat tietoisia siitä, että nyt alkaa tapahtua. Siksi taistelun alkaessa määritetään aina **Aloite**, mikä määrää sen kuka saa tehdä taistelun *ensimmäisen* toiminnon.

Aloitetta varten testataan **Taisteluvalmius**-taitoa. Paras lukema voittaa. Aloitteentekijä saa aina **Edun** aloitetta heitettäessä. Jos hahmo joutuu yllätetyksi, ei hän saa heittää aloitetta lainkaan, vaan häviää sen automaattisesti.

Aloitteen voittaja saa **edun** ensimmäiseen **toimintoonsa**, jonka jälkeen edetään siinä järjestyksessä kenellä on eniten **toimintopisteitä**. Jos hahmoilla on saman verran toimintopisteitä, voit verrata hahmojen Spiidi-kykyä, ja toimia suurimman Spiidin mukaisessa järjestyksessä. Jos yhdellä hahmolla on niin paljon toimintopisteitä, että hän on jatkuvasti muita taistelijoita edellä, saa hän tosiaan toimia aina kun hänellä on eniten toimintopisteitä. Tämä voi kuulostaa epäreilulta, mutta niin se vaan menee.

> [!example] **Pahan Pekan tarina...**
>
> Motoristilla oli kierroksen alussa 4 toimintopistettä, joista hän käytti jo 2 pistettä Pahan Pekan iskun väistämiseen, ja saikin ilmaisen iskun. Paha Pekka puolestaan menetti loput kierroksestaan, jouduttuaan pökerryksiin. Motoristi voi siis toimia uudestaan, ja päättää pamauttaa nyrkkiraudalla pökerryksissä olevaa Pekkaa naamaan. Motoristi heittä kolmella nopalla 9,8,4 josta paras on 9, ja tähän tulee -3 motoristin kyvyistä ja humalatilasta.  Lopputulos 6 on enemmän kuin Pekan peruspuolustus 5, joten Motoristi Osuu. Taas. Hän heittää vahingon D6:lla (se laskettiin, jo, joten ei tarvitse laskea uudestaan) ja saa tulokseksi 2 pistettä vahinkoa. Tästä ei tule vammaa, mutta Pekan HP tippuu nolliin, ja hän menettää tajuntansa.

```mermaid
flowchart TD
    A[Taistelu alkaa] -->|Määritä Aloite| B
    B[Voittaja saa ensimmäisen toiminnon ja siihen Edun] --> C
    C[Toiminnon julistus] -->|Vähennä Toimintopisteet| D
    D[Toiminnon Ratkaisu] -->|Suorita Testi| E
    E[Määritä lopputulos] -->F
    F{Onko taistelu ohi?} -->|Ei toimintopisteitä| H
    F -->|Ei toimintakykyisiä vastustajia/pelaajia| I
    F -->|Toimijoita jäljellä| G
    G[Seuraava toimija] -->|Kenellä on eniten toimintopisteitä?| C
    H[Uusi kierros]
    I[Lopetus]
```


Jokaisen toiminnon jälkeen hahmo vähentää toimintopisteistään toiminnon pistemäärän verran. Niin sanottu "standardi" toiminto on 2 pistettä. Tämä antaisi keskivertohahmolle 2 toimintoa joka kierroksessa.

Toimintopisteitä voi **säästää**: Jokainen 2 säästettyä toimintopistettä säästää ensikierrokselle yhden toimintopisteen.

Uuden kierroksen alettua hahmon toimintopisteet nollautuvat lukemaan: $Toimintopisteet + Säästetyt Toimintopisteet / 2$.

Joitain toimintoja voi myös tehdä **Reaktioina**, jolloin toiminnon voi julistaa kesken toisen hahmon vuoroa, esimerkiksi puolustautuakseen. Hahmolla pitää tällöin olla riittävä määrä toimintopisteitä käytettävissä. Tekemällä reaktion hän myös viivyttää seuraavaa toimintoaan, koska hänellä on seuraavaksi vähemmän toimintopisteitä käytössään.


| Toiminto               | TP  | Kuvaus                                                         | Reaktio | Testi                             |
| ---------------------- | --- | -------------------------------------------------------------- | ------- | --------------------------------- |
| Liikkuminen            | 1-5 | Hahmo voi liikkua liikenopeutensa verran.                      | Ei      | `Urheilu`, tarvittaessa           |
| Aseeton hyökkäys       | 2   | Hahmo voi hyökätä ilman aseita                                 | Ei      | `Taistelulajit` tai `Nyrkkitappo` |
| Melee hyökkäys         | 2-4 | Hahmo voi hyökätä lähitaisteluaseella                          | Ei      | `Taistelulajit`                   |
| Vastahyökkäys          | 2-4 | Puolustus ja hyökkäys lähitaistelussa                          | Kyllä   | `Taistelulajit`                   |
| Ampuminen              | 2-4 | Hahmo voi ampua kohdetta                                       | Ei      | `Ampumataito`                     |
| Jatkuva sarjatuli      | 1   | Täyden sarjatulen jatkaminen                                   | Ei      | `Ampumataito`                     |
| Väistäminen            | 2   | Hahmo pyrkii väistämään hyökkäyksen                            | Kyllä   | `Väistäminen`                     |
| Suojautuminen          | 1   | Hahmo hyödyntää läheistä suojaa                                | Kyllä   | Ei testiä.                        |
| Kranaatin virittäminen | 1   | Hahmo virittää kranaatin toimintavalmiiksi                     | Ei      | Ei testiä                         |
| Heittäminen            | 2-4 | Hahmo käyttää heittoasetta, esim. kranaattia tai heittoveistäå | Ei      | `Urheilu + Notku`                 |
|                        |     |                                                                |         |                                   |

> [!example] Pahan Pekan tarina...
>
> Paha Pekka herää sivukujalta, roskiksesta, jonne hänet on raahattu menetettyään tajuntansa pubissa. Hän huomaa makaavansa useiden ihmisruhojen ja rotan raatojen seassa, kuolemankatku sieraimissaan, kärpästen ympäröimänä. Pekka kömpii ulos ja tonkii ruhoja ja löytää sisälmysten keskeltä vanhan konepistoolin, sekä vähän ammuksia. Vihasta soikeana hän ryömii ulos ja suuntaa pubin etuovelle. Paha Pekka astuu sisälle pubiin, ja etsii motoristin, jolta sai hetki sitten turpaansa, aikeenaan teloittaa vihamiehensä siihen paikkaan. Motoristi huomaa Pekan, tämän ollessa vain muutaman metrin päässä, mutta tässä kohtaa Pekka painaa jo liipaisimen pohjaan. Pekka heittää aloitteen **Edulla** ja saa tulokseksi 12, kun taas yllätetty motoristi saa vain 7. Pekka saa ensimmäisen vuoron...