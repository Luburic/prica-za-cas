## Zadatak

Napravi interaktivnu obrazovnu priču: jednu samostalnu HTML stranicu, objavljenu kao artifact i poslatu kao .html fajl za rad bez interneta. Priča objašnjava publici šta je tema koristeći konkretne priče gde se korak po korak izlažu pojmovi i ostavlja jasan mentalni model na koji se kasnije nadograđuje. Koristi se na času: nastavnik priča uz nju, a tempo određuje onaj ko klikne.

## Ulazni podaci

- **Tema:** OPISATI U REČENICI ILI DVE
- **Publika i predznanje:** NAVESTI DA LI JE ZA NAROD ILI ZA ODREĐEN RAZRED U ŠKOLI
- **Primarni izvor informacija:** NAVESTI UDŽEBNIK KOJI SE KORISTI ILI DRUGI IZVOR
- **Jezik i pismo:** srpski, latinica, ekavica
- **Dužina:** Priča treba da se ispriča u DEFINISATI minuta.
- **Smernice:** OPISATI U PAR PARAGRAFA ŠTA ŽELITE DA SE PRIKAŽE

## Način rada

1. Proveri činjenice u izvorima; ništa iz sećanja.
2. Pošalji kratak plan i odmah nastavi: priča u jednoj rečenici, lanac pojmova, analogija, scene, stanice sa pitanjima, rasplet.
3. Pre predaje prođi celu priču u pregledaču (računar, telefon, tamna tema, konzola bez grešaka). Zatim pročitaj sav tekst kao celinu: lanac bez rupa, pojam pre upotrebe, jezik po meri publike, tačne činjenice.
4. Kod ispravki menjaj samo traženo i objavi na isti link.

## Principi

Primeni principe multimedijalnog učenja (Majer) i teoriju kognitivnog opterećenja. Svaki izbor im služi.

- **Koherentnost:** jedan proces; bez izmišljenih međukoraka, sporednih tema i ukrasa.
- **Signaliziranje:** u svakom trenutku jedno mesto za gledanje; boje imaju stalno značenje.
- **Prostorna i vremenska bliskost:** tekst stoji uz ono što objašnjava i javlja se zajedno sa slikom.
- **Segmentiranje:** sve ide na klik; ništa ne prelazi samo.
- **Prethodna obuka:** na početku pregled cele teme i glavnih segmenata; pojam se uvodi pre upotrebe.
- **Redundantnost i modalitet:** tekst je kratak jer nastavnik priča; slika nosi objašnjenje.
- **Personalizacija:** obraćanje na „ti”, primeri iz života publike.
- **Od konkretnog ka apstraktnom:** stvaran svet, zumiranje ka apstraktnom, pa povratak na celu sliku.
- **Generativnost:** pogled izbliza prvo pokaže, pa pusti učenika da proba.
- **Bez zavodljivih detalja:** animacija i zvuk samo kad pomažu razumevanju.

## Priča

- Lanac od X pojmova. Svaka stanica je pojam i jedno pitanje na dugmetu (npr. „Šta je munja?”) ili poziv (npr. „Otvori svoj laptop”). Najviše jedan do dva nova pojma po stanici.
- Jedna analogija nosi celu priču.
- Stvaran proizvod ili mesto koje publika zna, po mogućstvu lokalno.
- Svet pamti napredak: objašnjeno ostaje uključeno i označeno.
- Rasplet: udaljavanje do cele slike ili premotavanje puta, pa jedna do dve završne rečenice i „Pogledaj ponovo”.

## Interakcija

Scena zauzima ceo ekran. Svaka stanica ide istim tokom: zasvetli jedno dugme na mestu radnje → prozor sa strane, kratak tekst bez animacije → „Dalje” otvara pogled izbliza u istom prozoru, sa animacijom; kad se završi, „Dalje” zasija → prozor se zatvara, posledica se odigra na sceni i kamera je prati → zasvetli sledeće dugme.

- Prozor ne pokriva stanicu, jer se kamera pomeri; na telefonu se otvara odozdo.
- Bez automatskog prelaska, izbora brzine i dugmadi van prozora.
- Ispod scene su samo tanka traka (tačke za svaku celinu, Zvuk, Ispočetka, Ceo ekran) i zatvoren Mali rečnik, sa napomenom o pojednostavljenjima i izvorima.
- Tastatura i daljinski za prezentacije rade; skok na tačku vraća tačno stanje sveta.

## Tekst

- Strana ima naslov do sedam reči i do tri kratka pasusa (40 do 80 reči). Uz pogled izbliza idu najviše dve rečenice.
- Svaki termin izbaci, zameni ili uvedi. Uveden termin je podebljan prvi put, objašnjen i upisan u rečnik. Pretpostavi manje predznanja nego što misliš.
- Brojevi su u lokalnom formatu, sa jedinicom i poređenjem sa nečim poznatim. Primeri i pojednostavljenja su označeni.
- Bez crtica kao interpunkcije, bez „nije X, nego Y”, bez dvotačke posle koje sledi otkriće i bez šablonskih fraza.

## Stil

Ilustrovan stvaran svet, ni fotografija ni šema: 2D presek sa dubinom u SVG-u. Veselo i staloženo, toplo i deci i starijima. Kamera putuje kroz jedan neprekinut svet i zumiranjem prelazi između nivoa razmere. Tamna tema je noćna verzija sveta. Tipografija je krupna i čitljiva (tekst oko 20 px). Animacije su spore i mirne.

## Zvuk

Zvuk se sintetizuje u pregledaču (Web Audio, bez fajlova): ambijent prema mestu kamere, tiha muzika po fazama, kratki efekti za ključne događaje. Počinje posle prvog klika, stiša se dok je prozor otvoren, a dugme za isključivanje pamti izbor. Ništa ne sme da zamara pri ponavljanju; jačinu proveri offline renderom.

## Tehnika

Spolja samo fontovi sa Google Fonts (sa rezervnim fontom) i biblioteke sa dozvoljenih CDN-ova (npr. Three.js r128 sa cdnjs). Stanice su zapisane kao podaci, animacije se mogu prekinuti, smanjeno kretanje se poštuje, dugmad su pristupačna, a na telefonu nema vodoravnog skrola.