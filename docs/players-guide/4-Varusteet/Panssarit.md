---
share: true
---
# Panssarit

**Panssariluokka**: Ilmoitetaan vahinkotyypin mukaan. Lävistävä (L), Murskaava (M), ja Polttava (P).

| Panssari              | L    | M    | P    | Tyyppi      | Muuta                   | Hinta (CR) |
| --------------------- | ---- | ---- | ---- | ----------- | ----------------------- | ---------- |
| Panssaroidut vaatteet | 1    | 0    | 1    | Kevyt       | -                       | 100        |
| Nano-Armor vaatteet   | 2    | 2    | 2    | Kevyt       | Itsekorjautuva          | 1000       |
| Kevyet Luotiliivit    | 2    | 1    | 1    | Kevyt       | -                       | 500        |
| Nahkapanssari         | 2    | 3    | 3    | Keskiraskas | -                       | 400        |
| Metallipanssari       | 3    | 1    | 2    | Raskas      | -                       | 600        |
| Raskaat luotiliivit   | 3    | 2    | 1    | Keskiraskas | -                       | 1000       |
| Sotilaspanssari       | 4    | 2    | 3    | Keskiraskas | -                       | 3000       |
| Rynnäkköpanssari      | 5    | 3    | 4    | Raskas | Tiivis                  | 6000       |
| Kevyt Voimahaarniska  | 6    | 4    | 6    | Keskiraskas | Ruho +2 | 10000      |
| Raskas Voimahaarniska | 10    | 9    | 10    | Super-Raskas      | Ruho +4 | 30000      |

## Panssarityypit

### Kevyt
Ei haittaa liikkeitä. Helppo piilottaa vaatteiden alle. 1 Taakkapiste. Kestää 10 pistettä panssarivahinkoa ennen kuin hajoaa.

### Keskiraskas
Maksimi liikenopeus x4. Urheilu, Väistöliikkeet ja Peruspuolustus -2. 2 Taakkapistettä. On mahdollista piilottaa paksun vaatekerran alle. Kestää 20 pistettä panssarivahinkoa ennen kuin hajoaa

### Raskas
Maksimi liikenopeus x3. Urheilu, Väistöliikeet ja Peruspuolustus -5. 4 Taakkapistettä. Ei voi piilottaa. Kestää 30 pistettä panssarivahinkoa ennen kuin hajoaa.

### Super-Raskas
Maksimi liikenopeus x2. Urheilu, Väistöliikket ja Peruspuolustus - 8. 6 Taakkapistettä. Ei voi piilottaa. Kestää 40 pistettä ennen kuin hajoaa.

### Suojavyö
Suojavyöt ovat kehittyneitä puolustusjärjestelmiä, jotka pystyvät luomaan energiakentän käyttäjänsä ympärille, kun käyttäjään kohdistuu suuri määrä energiaa, esim. luoteja, plasmaa, tai lasersäteitä, mutta se ei suojaa lainkaan lähitaistelussa. Suojavyö ei haittaa käyttäjänsä liikeitä lainkaan, ja sen voi pukea minkä tahansa muun panssarin päälle ilman haittoja. Suojavöissä on rajallinen määrä käyttökertoja, jotka kuluvat joka kerta kun hahmoa vastaan hyökätään projektiili- tai energia-aseella. Lisäksi useimmat mallit eivät toimi kuin kerran kierroksessa. Lataukseen voi käyttää sopivankokoisia E-Cell paristoja.

### Voimahaarniska ja Ulkoranka
Voimahaarniskat ja Ulkorangat hyödyntävät ulkoista virtalähdettä avustaakseen käyttäjän liikkeitä. Kevyimmillään voimahaarniskat ovat ulkorankoja, jotka puetaan käyttäjän ylle, mutta jotka jättävät osan käyttäjästä vailla suojaa. Ulkorankoja käytetään usein esim. teollisuudessa, jossa tärkeintä on parantunut suorituskyky. Voimahaarniskat j Ulkoranka kantavat aina oman painonsa, eikä niistä kerry **taakkaa**.

#### Kykyarvot
Ulkoranka tai voimahaarniska määritttää arvot sekä **Ruholle**, että **Notkulle**. Nämä arvot yliajavat hahmon luontaiset arvot, koska ne ovat panssarin omia arvoja. Eli jos panssarin kyky on parempi kuin hahmon kyky, on hahmolla panssarin kanssa paremmat kyvyt, mutta jos hahmon luontaiset kyvyt ovat paremmat, niin hän joutuu käyttämään panssarin huonompia kykyjä.

Ne vaikuttavat johdettuihin arvoihin myös  sillä poikkeuksella, että hahmon Kestävyys ei voi tulle heikommaksi voimahaarniskan kanssa, vaikka Ruho-arvo olisikin heikompi.

Jos voimahaarniskan kykyarvo on merkitty suluissa esim. `(Skarppi +1)`, niin kykyarvon käyttö on valinnaista, ja hahmo voi käyttää luontaista kykyään, mikäli se on parempi.

#### Panssarin Kesto
Voimahaarniskan kesto joko 40 tai 20 pistettä. Täysi voimahaarniska kestää 40 pistettä panssarivahinkoa, kun taas kevyempi ulkoranka kestää vain 20 pistettä.

### Panssarivahinko

Panssarit kestävät tietyn määrän osumia ennen kuin hajoavat. Tämä riippuu panssarin tyypistä. Panssarivahinko per osuma riippuu lopullisesta Vahinkoluokasta, sen jälkeen kun on vähennetty panssariluokka.

Panssarivahinko lasketaan aina ensin päällimmäiseen panssarikerrokseen, ja sen tuhouduttua, lasketaan vahinkoa seuraaviin kerroksiin.

| Läpäisevä Vahinkoluokka | Panssarivahinko / osuma  |
| ----------------------- | ----------------------------- |
| 0 tai alle              | Ei vahinkoa.                  |
| 1-4                     | ½                             |
| 5+                      | 1                             |

### Panssarikerrokset

Kevyita panssareita voi pitää raskaampien alla, mutta kerroksien latominen päälle aiheuttaa ylimääräistä taakkaa, ja antaa +1 taakkahaitan per kerros. Eli kahdesta panssarista tulee +2 taakka. 

Panssariluokka on marginaalisesti parempi ja parhaimman panssariluokan arvoon lisätään +1 bonus jos Panssariluokkien ero on korkeintaan 4 pistettä. 4 pistettä suuremmalla erolla toinen kerros ei hyödytä lainkaan, mutta taakka toki lasketaan silti.