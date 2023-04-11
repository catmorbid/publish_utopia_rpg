---
share: true
---
# Ampuma-aseet

**Tarkkuus:** Aseen tarkkuus lisätään hyökkäystestiin muuttujana.

**Läpäisyluokka (LL)**: Vähennä läpäisyluokka panssariluokasta. Panssariluokka ei voi tippua alle nollan. Negativiinen LL nostaa panssariluokkaa, mutta sillä ei ole vaikutusta, jos kohteella ei ole panssaria lainkaan.

**Vahinkoluokka (VL):** Vahinkoluokka kertoo aseen vahingoittavan potentiaalin. Vähennä Vahinkoluokasta Panssariluokka.  Vahinkoluokan mukana on ilmaistu hyökkäyksen vahinkotyyppi: Lävistävä (L), Murskaava (M), tai Polttava (P). Jos vahinkotyypiksi on ilmaistu enemmän kuin yksi vahinkotyyppi, niin Panssarointi katsotaan heikoimman mukaan, ja vammat menevät saman vahinkotyypin mukaan. Viimeisenä merkintä voi myös olla vahinkomuutos, joka merkitään +/- merkinnällä. Esim. `L4+1` tarkoittaa 4 luokan vahinkoa, mutta vahinkonoppaan tulee +1 muutos.

**Toimintopisteet (TP):** Kuinka monta toimintopistettä maksaa yksi hyökkäys aseella.

**Tulinopeus (TN):** Kuinka monta ammusta voi kuluttaa yhdessä hyökkäyksessä. Kerroin tulinpeuden perässä kertoo, että ase ampuu useamman projektiilin kerralla, ja varsinainen tulinopeus kerrotaan tällä luvulla, kun selvitetään sarjatulen etua.

**Kantama (KM)**: Aseen Optimaalinen kantama, tai Minimikantama ja Optimaalinen kantama, jos ilmoitettu kaksi lukua.

**Rekyyli (RK)**: Aseen rekyyli, eli kuinka helposti aseella saa ylimääräisiä osumia ensimmäisen osuman jälkeen.

**Koko (KO)**: Aseen koko määrittelee kuinka monta taakkapistettä esineen kantaminen vie. Jos hahmolla on mukana enemmän varusteita kuin hänen sallittu maksimitaakkansa, vaikeutuu liikkuminen. 

**Lipaskoko (LK):** Kuinka monta ammusta aseeseen on kerralla ladattu.

| Ase                                                | TRK  | Tyyppi      | LL   | VL   | TP   | TN    | KM     | RK   | KO   | LK   | Hinta |
| -------------------------------------------------- | ---- | ----------- | ---- | ---- | ---- | ----- | ------ | ---- | ---- | ---- | ----- |
| Smichter, P16, 9x19mm                              | 0    | Pistooli    | 0    | L3   | 2    | 4     | 7      | 1    | 1    | 15   | 250   |
| Smichter, P19 GT, 9x19mm                           | 0    | Pistooli    | 0    | L3   | 2    | 10    | 6      | 1    | 1    | 20   | 350   |
| Smichter P26 Compact, 10x25mm                      | 0    | Pistooli    | 0    | L3+1 | 2    | 3     | 5      | 2    | 1    | 8    | 450   |
| Magnon Arms, 83K Standard Police Issue, 10x25mm    | 0    | Pistooli    | 0    | L3+1 | 2    | 3     | 8      | 2    | 1    | 12   | 650   |
| Krieger, Eagle, .44 Magnum                         | 0    | Pistooli    | 0    | L4   | 3    | 2     | 8      | 2    | 1    | 7    | 400   |
| Manhunt, Magnum 187, 15x42mm                       | 0    | Pistooli    | 0    | L6   | 4    | 1     | 10     | 4    | 1    | 6    | 1700  |
| Smichter, PG55 Shokkipistooli, SP1                 | +1   | Pistooli    | 2    | ML3  | 3    | 2     | 8      | 1    | 1    | 7    | 1200  |
| Megacorp, SHG-21 "Hunter's Blade", SP1             | +2   | Pistooli    | 2    | ML3  | 2    | 4     | 12     | 1    | 1    | 12   | 3400  |
| Manhunt, MP3 Micro SMG, 9x19mm                     | 0    | SMG         | 0    | L3   | 2    | 15    | 5      | 1    | 2    | 30   | 700   |
| Manhunt UZ-1 "Modern Killer" 4.8x30mm              | +1   | SMG         | 2    | L2   | 2    | 20    | 9      | 1    | 2    | 40   | 2400  |
| Von Krauer's CZ-203 "Urban Horror", 4.8x30mm       | -1   | SMG         | 2    | L2   | 3    | 40    | 8      | 1    | 3    | 120  | 6660  |
| Krieger, MaG-68 rynnäkkökivääri, 6.66x47mm         | +1   | Kivääri     | 0    | L5   | 3    | 10    | 50     | 3    | 4    | 20   | 1500  |
| Manhunt, XB3 rynnäkkökivääri, 6.66x47mm            | +0   | Kivääri     | 0    | L5+1 | 3    | 15    | 40     | 3    | 5    | 60   | 2250  |
| Krieger, HAR-5400 "Nightbringer", 7.5x50mm         | +2   | Kivääri     | 1    | L6+1 | 3    | 12    | 60     | 4    | 5    | 30   | 4850  |
| Winchester Sports, M34 Basic, 7.5x50mm             | +1   | Kivääri     | 1    | L6   | 3    | 3     | 50     | 4    | 4    | 15   | 1400  |
| Winchester Sports, M102 Extreme, 8.8x66mm          | +1   | Kivääri     | 2    | L7   | 4    | 2     | 60     | 5    | 5    | 10   | 2600  |
| Winchester Sports, HP422 Rynnäkkökivääri, 7.5x50mm | +1   | Kivääri     | 1    | L6   | 3    | 8     | 50     | 3    | 4    | 24   | 2800  |
| NFWL DDR2086 Warhammer, 5.2x49mm                   | +0   | Kivääri     | 3    | L4   | 3    | 5-30  | 45     | 1    | 5    | 120  | 9000  |
| Megacorp, SS-88 Sniper, 8.8x66mm + yönäkötähtäin   | +3   | Kivääri     | 2    | L7+1 | 4    | 1     | 20-200 | 5    | 6    | 6    | 4200  |
| Megacorp, K18 Shokkikivääri, SP2                   | +2   | Kivääri     | 4    | L6   | 3    | 3     | 80     | 2    | 4    | 10   | 7600  |
| Manhunt, Double Long, 12g                          | +2   | Haulikko    | -1   | L3   | 3    | 2     | 15     | 1    | 4    | 2    | 600   |
| Manhunter, Double Short, 12g                       | +4   | Haulikko    | -1   | L3+1 | 2    | 2     | 4      | 1    | 1    | 2    | 500   |
| Manhunt, Triple Medium, 12g                        | +3   | Haulikko    | -1   | L3   | 3    | 3     | 8      | 1    | 3    | 3    | 900   |
| Manhunt, Triple Short, 12g                         | +4   | Haulikko    | -1   | L3+1 | 3    | 3     | 4      | 1    | 1    | 3    | 800   |
| Manhunt, Quad Death, 12g                           | +3   | Haulikko    | -1   | L3   | 3    | 4     | 8      | 1    | 5    | 4    | 2400  |
| Winchester Sports, M18 Pumppuhaulikko, 12g         | +3   | Haulikko    | -1   | L3   | 3    | 3     | 6      | 3    | 4    | 8    | 800   |
| Winchester Sports, CAR-5 Automaattihaulikko, 12g   | +2   | Haulikko    | -1   | L3   | 3    | 6     | 6      | 2    | 5    | 12   | 1800  |
| Krieger M600 Raskas konekivääri, 8.8x66mm          | +0   | Konekivääri | 2    | L7   | 4    | 10    | 75     | 4    | 6    | 40   | 12500 |
| Krieger M90 Konekivääri, 6.66x47mm                 | +0   | Konekivääri | 0    | L5   | 3    | 3-15  | 60     | 3    | 5    | 90   | 4800  |
| Megacorp GT2000 Gatling-konekivääri, 6.66x47mm     | +0   | Konekivääri | 0    | L5   | 3    | 30    | 40     | 4    | 6    | 120  | 6000  |
| Smichter Warrior-5 Gatling-konekivääri, 5.2x49mm   | +0   | Konekivääri | 3    | L4   | 4    | 10-50 | 40     | 2    | 6    | 300  | 12000 |