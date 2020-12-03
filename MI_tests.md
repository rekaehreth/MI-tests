# MI tesztek a 2020/20201/1 szemeszterben 

Ebben a dokumentumban megtalálható az összes kérdés a 2020/2021/1-es MI előadást ellenőrző canvas tesztekből, illetve a hozzájuk tartozó ~~helytelen válaszok~~ és helyes válaszok. Elsőként a helyes válasz(ok) vannak feltűntetve. 
## Első teszt - MI fogalma
### Az alábbiak közül melyik NEM utal a mesterséges intelligencia jelenlétére egy szoftverben? 
- A szoftver optimális megoldást talál a kitűzött problémához. 
- ~~A megoldandó feladatnak hatalmas a problématere.~~
- ~~A szoftverbe különleges technológiák vannak beépítve.~~ 
- ~~A szoftver viselkedése intelligens jegyeket mutat.~~
### Mire utal egy algoritmussal kapcsolatban a kombinatorikus robbanás fogalma? 
- Az algoritmus kezelhetetlenül nagy memóriát igényel és/vagy a futási ideje óriási. 
- ~~Az algoritmus NP-teljes.~~
- ~~Az ilyen algoritmus nagyságrendekkel több megoldást tud előállítani adott időegység alatt.~~
- ~~Az algoritmus végtelen iklusba tud kerülni.~~
### Mit várunk el egy útkereső algoritmustól? 
- Azt, hogy egy irányított gráfban egy adott csúcsból kiinduló megadott csúcsok valamelyikébe érkező irányított utat találjon meg. 
- ~~Azt, hogy megadja egy irányított gráfban egy adott csúcsból kiinduló összes többi csúcsba vezető valamelyik utat.~~
- ~~Azt, hogy egy irányított gráfban egy adott csúcsból kiinduló megadott csúcsok valamelyikébe érkező optimális költségű irányított utat találjon meg.~~
- ~~Azt, hogy megadja egy irányított gráfban egy adott csúcsból kiinduló összes többi csúcsba vezető optimális költségű utat.~~
### Hogyan definiáljuk az optimális költség fogalmát? 
- Egy csúcsból egy másik csúcsba vezető utak költségeinek minimuma. 
- Egy csúcsból csúcsok halmazába vezető utak költségeinek minimuma. 
- ~~Egy csúcsból csúcsok halmazába vezető utak költségeinek infímuma.~~
- ~~Egy csúcsból egy másik csúcsba vezető utak költségeinek infímuma.~~
### Mely állítások igazak az alábbiak közül? 
- A kínai szoba elmélet az MI szkeptikusok érveit erősíti
- A Turing kiritérium cáfolataként született meg a kínai szoba elmélet. 
- ~~A Turing kritérium és a kínai szoba elméletegyaránt az erős MI hívők érveit erősítik.~~
- ~~A Turing kritérium az MI szkleptikusok érveit erősíti.~~
### Mikor nevezhetünk egy feladatot útkeresési problémának? 
- Amikor a megoldás egy irányított gráf egy útjának feleltethető meg.
- Amikor a feladat problématerének elemei ugyanazon csúcsból kiinduló irányított utak.
- ~~Csak akkor, ha a feladat olyan állapottér modellel rendelkezik, amelyben a megoldást egy műveletsorozat írja le.~~
- ~~Amikor egy gráfban keressük egy adott csúcsból az összes többibe vezető optimális utakat.~~
### Hogyan nyerhető ki egy útkeresési probléma megoldásakor kapott útból a feladat megoldása? 
- Sokszor az út élei mutatják a feladat megoldásához szükséges lépéseket. 
- Néha az út végpontja szimbolizálja a feladat egy megoldását. 
- ~~Az út csúcsai a feladatok különböző megoldásai.~~
- ~~Az út élei a feladat különböző megoldásait szimbolizálják.~~
### Mely állítások igazak egy 𝛿-gráfra?
- Csúcsaiból véges sok irányított él indul ki.
- Végtelen sok csúcsa lehet. 
- ~~Csúcsaiba véges sok irányított él fut be.~~
- ~~Éleinek költsége pozitív valós szám.~~
### Egy útkeresési feladat gráfreprezentációjához meg kell adni a ... 
- startcsúcsot
- reprezentációs gráfot
- ~~megoldási utakat~~
- ~~alkalmazandó heurisztikákat~~
### Az alábbiak közül melyek tartoznak a Turing kritériumok közé? 
- automatikus következtetés
- természetes nyelvű kommunikáció
- megszerzett ismeret tárolása
- ~~optimális megoldás megtalálása~~
### Allítsa párba: mely fogalmak kapcsolhatók egymáshoz!
| Fogalom | Pár | 
| ------- | --- |
| hatalmas problématér | kombinatorikus robbanás | 
| kínai szoba elmélet | MI szkeptikusok | 
| útkeresési feladat | probléma modell | 
| heurisztika | intuíció |
### Egy hiperút egy bejárása
- a hiperút összes hiperélét legalább egyszer érinti.
- a hiperút egy hiperélét legfeljebb annyiszor érinti, ahány közönséges irányított út vezet a hiperútban a hiperút kezdőcsúcsából a hiperél kezdőcsúcsába. 
- ~~kört nem tartalmazhat.~~
- ~~a hiperút egy hiperélét legfeljebb annyiszor érinti, ahány közönséges irányított út vezet a hiperútban a hiperút kezdőcsúcsából a hiperél kezdőcsúcsába.~~
## Második teszt - Modellezés
### Hogyan NEM csökkenthető egy állapottér modell bonyolultásga? 
- Csökkentjük a célállapotok számát. 
- ~~Növeljük az állapotok számát, de új műveleteket vezetünk be.~~ 
- ~~Szigorítjuk az állapotok invariáns tulajdonságát.~~
- ~~Szigorítjuk a műveletek értelmezési tartományát.~~
### Mitől NEM függ egy reprezentációs gráf bonyolultsága? 
- A csúcsai be-fokának számától. 
- ~~A csúcsainak és éleinek számától.~~
- ~~A csúcsai ki-fokának számától.~~ 
- ~~A köreinek gyakoriságától, és hosszuk sokféleségétől.~~ 
### Melyik NEM része a probléma dekompozíciós modellnek? 
- Az állapotok definiálása. 
- ~~Az egyszerű problémák megadása.~~
- ~~Dekompozíciós műveletek definiálása.~~
- ~~A kiinduló probléma leírása.~~ 
### Milyen egy dekompozíciós operátor? 
- Egy problémát több problémának a sorozatára képez le. 
- ~~Egy problémát több problémának a halmazára képez le.~~
- ~~Egy problémát megadott problémák egyikével helyettesít.~~ 
- ~~Egy probléma-sorozatot részsorozatokra bont fel.~~
### Az alábbiak közül melyek NEM elemei az állapottér modellnek? 
- állapotgráf
- heurisztika 
- ~~műveletek~~
- ~~kezdő állapot vagy annak leírása~~
### Mely állítások igazak az állapotgráfra az alábbiak közül? 
- Csúcsai az állapotokat szimbolizálják. 
- Startcsúcsa a kezdőállapotot szimbolizálja. 
- Élei a műveletek végrehajtásait szimbolizálják. 
- ~~Célcsúcsai a modellezett feladat megoldásai.~~
### Az alábbi feladat-modellezések közül melyeknél NEM egyezett meg a problématér a reprezentációs gráf startcsúcsból kivezető útjaival? 
- integrál számítás
- n-királynő probléma
- ~~Hanoi-tornyai probléma~~ 
- ~~8-as kirakó játék~~
### Melyik ot-okozati összefüggések igazak az alábbiak közül? 
- Az állapotgráf csúcsainak száma kihat a megoldó algoritmus hatékonyságára. 
- Az állapotgráfbeli körök hossza és száma kihat a problématér bonyolultságára. 
- ~~A megoldó algoritmus számíási bonyolultsága kihat a problématér bonyolultságára.~~
- ~~Az optimális megoldások száma kihat az állapotgráf bonyolultságára.~~
### Hogyan csökkenthető egy állapottér modellben a műveletek kiszámítási bonyolultsága? 
- Az állapotokat extra információval egészítjük ki. 
- Szigorítjuk az állapotok invariáns állítását. 
- ~~Több heurisztikát építünk be a modellbe.~~
- ~~Szigorítjuk a műveletek előfeltételét.~~ 
### Mely fogalmak kapcsolhatók egymáshoz? 
| Fogalom | Pár | 
| ------- | --- | 
| dekompozíciós operátor | hiperél | 
| állapot | csúcs | 
| művelet | irányított él | 
| dekompozíciós folyamat | hiperút| 
### Melyek a feltételei a visszafelé haladú keresésnek? 
- A reprezentációs gráf kétirányú éleket tartalmazzon és legyen ismert valamelyik célállapot. 
- ~~A reprezentációs gráf startcsúcsából az összes célcsúcsba vezető úton kétirányú élek legyenek.~~
- ~~A reprezentációs gráf kétirányú éleket tartalmazzon és legyen ismert az összes célállapot.~~
- ~~A reprezentációs gráf startcsúcsából valamelyik célcsúcsba vezető úton kétirányú élek legyenek.~~
### Mi célt szolgál a probléma-redukciós operátor? 
- Az állapottér modell egy műveletére megadja, hogy a művelet segítségével mely állapotokból lehet eljutni adott állapotok egyikébe. 
- ~~Egy állapottér modell egy műveletének inverze.~~
- ~~Megadja, hogy egy állapot mely állapotokból érhető el egy állapottér modellben.~~
- ~~Egy problémát egyszerűbb problémákra vezet vissza.~~
## Harmadik teszt - Lokális keresések
### Az alábbi módszerek közül melyiknél változhat ftás közben a globális munkaterület mérete? 
- Tabu keresésnél
- ~~Hegymászó módszernél~~
- ~~Szimulált hűtésnél~~
- ~~Véletlen újraindított hegymászó módszernél.~~
### Melyik állítás NEM igaz a lokális keresésekre az alábbiak közül
- Csak egy lokálisan legjobb megoldást képes megtalálni
- Ezek mohó stratégiájú algoritmusok
- ~~Az aktuális csúcs környezetéből választja az új aktuális csúcsot.~~
- ~~Memóriája az aktuális csúcs környezetének tárolására korlátozódik.~~
### Tekinthető-e a hegymászó módszer a tabu keresés speciális változatának?
- Nem, amennyiben a hegymászó módszer nem tárolja el az eddig megtalált legjobb kiértékelő függvényértékű csúcsot. 
- Igen, amennyiben a hegymászó módszer tulajdonképpen egy egyelemű tabu halmazt használ, amely az előző aktuális csúcsot tárolja csak. 
- ~~Nem, mert a tabu keresés felismeri a köröket, a helgymászó algoritmus nem.~~
- ~~Nem, mert a tabu keresés véletlen módon választ új csúcsot.~~
### Hány helyen használ a szimulált hűtés algoritmusa véletlenített módszert? 
- Kettő. A következő csúcs kiválasztásához, illetve annak elfogadásához. 
- ~~Nulla. Ez ugyan egy nem-determinisztikus módszer, de nem használ véletlenítést.~~
- ~~Egy. A következő aktuális csúcs kiválasztásához.~~
- ~~Három. A következő aktuális csúcs kiválasztásához, annak elfogadásához, és a hűtési ütemterv változtatásához.~~
### Mely állítások igazak az alábbiak közül? 
- A heurisztika egyszerre csökkentheti az algoritmus memória igényét és a futási idejét. 
- A heurisztikát a feladatot megoldó algoritmusba közvetlenül építjük be. 
- ~~A heurisztika garantálja, hogy az algoritmus hatékonysága jobb lesz.~~
- ~~A heurisztika garantálja, hogy az algoritmus az optimális megoldást találja meg.~~
### Melyek az alábbiak közül a tabu keresés hátrányai? 
- Zsákutcába érve a keresés megáll. 
- A tabu halmaz méretét csak kísérletezéssel lehet beállítani. 
- ~~Képes felismerni, és elkerülni a kisebb köröket.~~
- ~~Kicsi a memória igénye.~~
### Mely állítások NEM igazak a lokális keresésre az alábbiak közül? 
- Körmentes gráfokban nem akad el.
- Talál megoldást, ha van megoldás.
- ~~Kicsi memóriát használnak.~~
- ~~Erősen összefüggő gráfokban nem akadnak el.~~
### Melyek az alábbiak közül a hegymászó módszer hátrányai? 
- Körök mentén végtelen működésbe kezdhet.
- Zsákutcába érve a keresés megáll. 
- Nem garantál optimális megoldást. 
- ~~Kicsi a memória igénye.~~
### Hogyan hat a heurisztika információ tartalma egy kereső rendszer futási idejére? 
- Nagyobb információ tartalom mellett a lépések száma csökkenhet. 
- Nagyobb információ tartalom mellett egy lépés futási ideje nő. 
- Minél kisebb az információ tartalma, annál gyorsabban tud új lépést választani. 
- ~~Minél nagyobb az információ tartalma, annál jobb lesz a hatékonyság.~~
### Mely algoritmusok születtek a hegymászó módszer zsákutcában való beragadásának elkerülésére? 
- Lokális nyaláb keresés (local beam search)
- Szimulált hűtés algoritmusa
- Véletlen újraindított keresés (random start search)
- ~~Tabu keresés~~
### Mi a lokális keresések általános vezérlési stratégiája? 
- Az aktuális csúcs(ok) krnyezetéből választunk egy (vagy több) viszonylag jó csúcsot!
- ~~Az aktuális csúcs környezetéből válasszuk a legjobb csúcsot!~~
- ~~Az aktuális csúcs(ok) környezetéből válasszuk a legjobb csúcsot (csúcsokat)!~~ 
- ~~Az aktuális csúcs szomszédjai közül válasszuk a legjobb csúcsot!~~
### A tabu keresésnél használt kiértékelő függvény, amellyen össze tudjuk hasonlítani az aktuális csúcs gyerekeit, heurisztikus stratégiának számít? 
- Igen, ez a függvény a konkrét feladatból származik. 
- ~~Nem, mert ezt csak az olyan feladatoknál használhatjuk, amelyek állapottér modell-lel rendelkeznek. Ez tehát egy modell-függő stratégia.~~
- ~~Nem, mert ilyen függvényt minden tabu keresés használ.~~
- ~~A heurisztikának nincs köze a vezérlési stratégiához.~~
## Negyedik teszt - Visszalépéses keresés
### Mely fogalmak kapcsolhatók egymáshoz a visszalépéses keresés esetén? 
| Fogalom | Pár | 
| ------- | --- | 
| globális munkaterület | irányított út | 
| keresési szabály | visszalépés | 
| másodlagos vezérlési stratégia | sorrendi szabály | 
| második változat | mélységi korlát figyelés | 
### Mit tartalmaz a visszalépéses keresések globális munkaterülete? 
- A startcsúcsból kiinduló egyik utat és annak csúcsaiból kivezető még nem vizsgált éleket. 
- ~~A reprezentációs gráfot és külön annak a startcsúcsból kiinduló egyik útját.~~
- ~~Ez eddig bejárt startcsúcsokból kiinduló utakat azok csúcsaiból kivezető még nem vizsgált élekkel együtt.~~
- ~~Ez eddig bejárt részgráfot és külön annak a startcsúcsból kiinduló egyik útját annak csúcsaiból kivezető még nem vizsgált élekkel együtt.~~
### Melyek a visszalépéses keresés keresési szabályai? 
- A nyilvántartott út végcsúcsaiból kivezető egyik él hozzávétele az úthoz, illetve az utolsó élének elvétele. 
- ~~A nyilvántartott út utolsó csúcsának kiterjesztése, illetve az utolsó él elvétele.~~
- ~~A nyilvántartott úthoz egy újabb ivezető él hozzávétele, illetve az utolsó él elvétele.~~
- ~~A nyilvántartott út kiterjesztése, illetve a visszalépés.~~
### Mi a visszalépéses keresés általános vezérlési stratégiája? 
- A visszalépés szabályát csak a legvégső esetben válasszuk.
- ~~A visszalépés szabálya mindig elsőbbséget élvez a többi keresési szabállyal szemben.~~
- ~~A továbblépést meghatározó sorrendi és a vágó szabályok.~~
- ~~Zsákutcába jutva mindig a visszalépés szabályát kell választnai.~~
### Melyik állítás NEM igaz a visszalépéses keresés második változatára az alábbiak közül? 
- A körfigyelés elhagyása mindenképpen gyorsítja a megolsá megtalálását. 
- ~~A körfigyelés elhagyása növeli a memória igényét.~~
- ~~A körfigyelés elhagyása kicsi mélységi korlát mellett gyorsíthatja a futási időt.~~
- ~~A körfigyelés elhagyása végtelen fák esetén mindenképpen gyorsítja a megoldás megtalálását.~~
### Melyek az alábbiak közül a visszalépéses keresés hátrányai?
- Ugyanazt a részgráfot többször is bejárja.
- Kezdetben hozott rossz döntést csak sok visszalépés árán korrigálja. 
- ~~Nehéz az implementációja.~~
- ~~Nagy a memória igénye.~~
### Képzelje maga elé a 4-királynő probléma 2. állapottér modelljének állapotfáját. (Minden csúcsból négy él vezet ki.) Hány startcsúcsból kivezető utat vizsgál meg ebben a visszalépéses keresés második változata, ha a mélységi korlát 2?
- 21
- ~~8~~
- ~~16~~
- ~~20~~
### Mely állítások igazak a visszalépéses keresés második változatára az alábbiak közül? 
- Minden 𝛿-gráfban talál megoldást, ha annak hossza rövidebb, mint a mélységi korlát. 
- Minden 𝛿-gráfban terminál. 
- ~~Minden 𝛿-gráfban megmutatja, hogy van-e megoldás.~~
- ~~Minden 𝛿-gráfban talál megoldást, ha van.~~
### Mely állítások NEM igazak a visszalépéses keresés második változatára az alábbiak közül? 
- Képes megtalálni a legrövidebb megoldást, ha van. 
- A körfigyelés önmagában is elég ahhoz, hogy garantáltan termináljon. 
- ~~A mélységi korlát figyelés önmagában is elég ahhoz, hogy garantáltan termináljon.~~
- ~~Ha van megoldás a mélységi korláton belül, akkor talál megoldást.~~
### Melyek az alábbiak közül a visszalépéses keresés előnyei? 
- Ha van (mélységi korláton belül) megoldása, akkor talál egyet. 
- Mindig terminál.
- Kicsi a memória igénye. 
- ~~Véges 𝛿-gráfban optimális megoldást talál.~~
### Mely állítások NEM igazak az alábbiak közül? 
- A sorrendi szabály egy heurisztikus vezérlési stratégia. 
- Vágó szabály nem alkalmazható sorrendi szabályokkal együtt. 
- ~~A sorrendi és a vágó szabály egyaránt épülhet heurisztikára.~~
- ~~A mélységi korlát felfogható egy speciális vágó szabálynak.~~ 
### Képzelje maga elé a Hanoi tornyai probléma állapotgráfját három korong esetén. A startcsúcsból kivezető utak közül hányat vizsgál meg a visszalépéses keresés második változata, ha a mélységi korlát 3? 
- ~~8~~
- ~~9~~
- ~~14~~ 
- 15
## Ötödik teszt - Gráfkeresés
### Mit tartalmaz a gráfkeresés globális munkaterülete?
- A startcsúcsból kiinduló eddig felfedezett összes utat a nyílt csúcsokkal együtt.
- ~~A reprezentációs gráfot, de külön megcímkézve benne a már bejárt csúcsokat.~~
- ~~A reprezentációs gráf egy tetszőleges részgráfját.~~
- ~~Csak a nyílt csúcsok halmazát.~~
### Melyek a gráfkeresés keresési szabályai? 
- A nyílt csúcsok kiterjesztései. 
- ~~Egy újabb él hozzávétele a kereső gráf egyik csúcsához.~~
- ~~A továbblépés (újabb él felfedezése) és a visszalépés.~~
- ~~A továbblépés (egy csúcsból kivezető összes él felfedezése) és a visszalépés.~~
### Mi a gráfkeresés általános vezérlési stratégiája? 
- Minden lépésben a legígéretesebb nyílt csúcsot választja a kiterjesztés. 
- ~~A legutoljára felfedezett nyílt csúcs kiterjesztése.~~
- ~~A startcsúcsból legkisebb költségű úton elérhető nyílt csúcs kiterjesztése.~~
- ~~A startcsúcsból legkisebb költésgű már felfedezett úton elérhető nyílt csúcs kiterjesztése.~~
### Mely csúcsokat nevezzük a gráfkereséseknél nyílt csúcsoknak? 
- A keresőgráf azon csúcsait, amelyek gyermekeit még nem, vagy nem eléggé jól ismerjük, ennél fogva kiterjesztésre várnak. 
- ~~A keresőgráf azon csúcsait, amelyekből kivezető éleket még nem fedeztük fel.~~
- ~~A keresőgráf azon csúcsait, amelyeket még nem terjesztettünk ki.~~
- ~~A reprezentációs gráf azon csúcsait, amelyeket még nem terjesztettünk ki.~~
### Mit mutat a gráfkereséseknél a szülőre visszamutató pointerfüggvény (𝜋)?
- A keresőgráfbeli csúcsok egyik szülőjét. 
- ~~A reprezentációs gráfbeli csúcsok legjobb szülőjét.~~
- ~~A keresőgráfbeli csúcsok legjobb szülőjét.~~
- ~~A reprezentációs gráfbeli csúcsok egyik szülőjét.~~
### Mit mutat a gráfkereséseknél a különbségfüggvény (g)?
- A startcsúcsból a keresőgráfbeli csúcsokhoz, a keresőgráfban vezető egyik út költségét. 
- ~~A startcsúcsból a keresőgráfbeli csúcsokhoz vezető egyik út költségét.~~
- ~~A startcsúcsból a keresőgráfbeli csúcsokhoz, a keresőgráfban vezető legolcsóbb út költségét.~~ 
- ~~A startcsúcsból a keresőgráfbeli csúcsokhoz a szülőire visszamutató pointerfüggvény által kijelölt út költségét.~~
### Mikor nevezünk egy kiértékelő függvényt csökkenőnek? 
- Ha egy csúcs függvényértéke soha nem nő, viszont mindig csökkent valahányszor olcsóbb odavezető utat találunk hozzá. 
- ~~Ha egy csúcs értéke csak akkor változik, de akkor csökken, ha egy olcsóbb odavezető utat találunk hozzá.~~ 
- ~~Ha egy startcsúcsból kiinduló már felfedezett út mentén a csúcsok függvényértékei monoton csökkennek.~~
- ~~Ha az algoritmus által kiterjesztett csúcsok függvényértékei monoton csökkennek.~~
### Hogyan lehet a keresőgráf korrektségét fenn tartani? 
- Minden kiterjesztés után bejárjuk a kiterjesztéssel elért gyerekcsúcsok leszármazottait (ha vannak), és kijavítjuk azok korrektségét. 
- Olyan kiértékelő függvényt használunk, amely kizárja, hogy egy már korábban kiterjesztett csúcshoz minden addiginál olcsóbb odavezető utat találjunk a startcsúcsból. 
- ~~Visszahelyezzük az OPEN halmazba azt a zárt csúcsot, amelyhez minden addiginél olcsóbb odavezető utat találtunk a startcsúcsból.~~
- ~~Amikor egy minden addiginél olcsóbb odavezető utat találunk egy csúcshoz, akkor módosítjuk a szülőre visszamutató pointerfüggvény értékét és a költségfüggvény értékét.~~
### Mikor mondjuk a keresőgráf egyik csúcsára, hogy korrekt? 
- Ha a szülőre visszamutató pointerek a keresőgráfra nézve optimális utat jelölnek ki hozzá a startcsúcsból, és ennek az útnak a kötlségét mutatja a költségfüggvény. 
- Ha optimális és konzisztens. 
- ~~Ha a gráfkeresés már kiterjesztette a gyerekeit is.~~
- ~~Ha a költségfüggvény értéke a visszamutató pointerfüggvény általá kijelölt szülő csúcsánál mért költségfüggvény értékének, és a szülőtől hozzávezető él költségének összege.~~
### Mely állítások igazak az alábbiak közül a gráfkeresés általános algoritmusára? 
- Véges 𝛿-gráfban mindig terminál. 
- Egy csúcsot legfeljebb véges sokszor terjeszt ki még végtelen nagy 𝛿-gráfok esetén is. 
- Véges 𝛿-gráfban talál megoldást, ha van. 
- ~~Véges 𝛿-gráfban optimális megoldást talál, ha van megoldás.~~
### Mely állítások NEM igazak az alábbiak közül a gráfkeresés általános algoritmusára? 
- Körmentes 𝛿-gráfban talál megoldást, ha van. 
- 𝛿-gráfban mindig terminál. 
- ~~Csökkenő kiértékelő függvényt használva soha nem terjeszt ki inkorrekt csúcsot.~~
- ~~Véges 𝛿-gráfban talál megoldást, ha van.~~
### Mely fogalmak kapcsolhatók egymáshoz a gráfkereséseknél? 
| Fogalom | Pár | 
| ------- | --- | 
| globális munkaterület | keresőgráf | 
| keresési szabály | kiterjesztés | 
| pointerfüggvény | szülőcsúcs | 
| csökkenő kirétékelő függvény | korrektség |
## Hatodik teszt - A* algoritmus
### Lehet-e sorrendi heurisztika egy nem-informált gráfkeresés másodlagos vezérlési stratégiája?
- Igen-
- ~~Nem.~~
- ~~Csak akkor, ha már az elsődleges vezérlési stratégia is alkalmaz heurisztikát.~~
- ~~A másodlagos stratégiában nem lehet heurisztikát beépíteni.~~
### Mit jelent a gráfkereséseknél a megengedhetőség fogalma? 
- Olyan heurisztikus függvényt, amely alulról becsüli egy reprezentációs gráfban a csúcsokból a célba vezető optimális út költségét. 
- ~~Olyan gráfkereső algoritmust, amelyik optimális megoldást talál, ha van.~~
- ~~Olyan algoritmust, amely lépésről lépésre szűkíti a megoldások halmazát, amít az már csak az optimális megoldásokat tartalmazza.~~
- ~~Olyan gráfkereséseket, amelyek kiértékelő függvényében megengedett a heurisztika használata.~~
### Melyik állítás NEM igaz az azonosan nulla függvényről? 
- Nem választható kiértékelő függvénynek. 
- ~~Becsli a célba vezető optimális út költségét.~~
- ~~Megengedhető és monoton megszorításos.~~
- ~~Nem tartalmaz extra ismereteket, azaz heurisztikát.~~
### Melyik gráfkereső algoritmust nevezik A* algoritmusnak? 
- Amelyik kiértékelő függvénye g+h alakú, ahol h nem-negatív és megengedhető. 
- ~~Amelyik kiértékelő függvénye g+h alakú, ahol h nem-negatív, megengedhető és monoton megszorításos.~~
- ~~Amelyik garantáltan optimális megoldást talál, ha van.~~
- ~~Amelyik kiértékelő függvénye g+h alakú, ahol h megengedhető, és garantáltan optimális megoldást talál, ha van.~~
### Mi az alábbiak közül az A algoritmus tulajdonsága?
- 𝛿-gráfban megengedhető heurisztikával optimális megoldást talál, ha van. 
- ~~Heurisztikus függvénye megengedhető.~~
- ~~𝛿-gráfban egy csúcsot legfeljebb egyszer terjeszt ki.~~
- ~~𝛿-gráfban optimális megoldást talál, ha van.~~
### Mely állítás NEM igaz a következetes (A<sup>c</sup>) algoritmusra? 
- A kiterjesztéseinek száma akár a kiterjesztett csúcsok száma mínusz egynek a kettő hatványa is lehet. 
- ~~Egy csúcsot legfeljebb egyszer terjeszt ki.~~
- ~~Amikor egy csúcsot kiterjeszt, már ismeri a csúcsból odavezető optimális utat.~~
- ~~Optimális megoldással temrinál, ha van megoldás.~~
### Mennyi a B algoritmus kiterjesztéseinek száma legrosszabb esetben, ha a kiterjesztett csúcsok száma k? 
- <sup>1</sup>/<sub>2</sub> k<sup>2</sup>
- ~~2 <sup>k-1</sup>~~
- ~~k~~
- ~~k log<sub>2</sub> k~~
### Mikor mondjunk egy A- algoritmust jobban informáltnak egy másiknál? 
- Ha a heurisztikus függvényének értéke a nem célcsúcsokban nagyobb, mint a másik algoritmus heurisztikus függvényének értéke. 
- ~~Ha kevesebb csúcs kiterjesztése mellett terminál.~~
- ~~Ha a memória igénye nem nagyobb a másikénál.~~
- ~~Ha a heurisztikus függvényének értéke a nem célcsúcsokban közelebbi becslést ad, mint a másik algoritmus heurisztikus függvényének értéke.~~
### Mikor mondhatjuk a gráfkereséseknél egy heurisztikus függvényről azt, hogy monoton megszorításos? 
- Ha bármelyik él költsége nagyobb-egyenlő, mint a a különbség, amit úgy kapunk, hogy az él kezdőcsúcsának függvényértékéből levonjuk a végcsúcsának függvényértékét. 
- ~~Ha a függvényt használó gráfkeresés működési grafikonja monoton növekvő.~~
- ~~Ha a függvény megengedhető és nem negatív.~~
- ~~Ha a függvény alulról becsüli minden csúcsában a hátralevő optimális költséget.~~
### Melyik állítás igaz az egyenletes gráfkeresésre? 
- Optimális megoldást talál, ha van
- Egy már kiterjesztett csúcshoz soha nem talál minden addiginál olcsóbb utat. 
- ~~Kiértékelő függvénye az élek élköltségeit egységnyinek teikinti.~~
- ~~Dijkstra legröbidebb utak algoritmusának szinonímája.~~
### Az alábbiak közül melyek a megengedhető gráfkereső algoritmusok?
- A algoritmus
- B algoritmus
- Egyenletes gráfkeresés
- A** algoritmus
### Mely fogalmak kapcsolhatók egymáshoz a gráfkereséseknél? 
| Fogalom | Pár | 
| ------- | --- | 
| mélységi gráfkeresés | nem-informált gráfkeresés | 
| A* algoritmus | optimális megoldás | 
| B algoritmus | Martelli | 
| memória igény | zárt csúcsok száma |
## Hetedik teszt
### 1
### 2
### 3
### 4
### 5
### 6
### 7
### 8
### 9
### 10
### 11
### 12
## Nyolcadik teszt
### 1
### 2
### 3
### 4
### 5
### 6
### 7
### 8
### 9
### 10
### 11
### 12
## Kilencedik teszt
### 1
### 2
### 3
### 4
### 5
### 6
### 7
### 8
### 9
### 10
### 11
### 12
## Tizedik teszt
### 1
### 2
### 3
### 4
### 5
### 6
### 7
### 8
### 9
### 10
### 11
### 12
## Tizenegyedik teszt
### 1
### 2
### 3
### 4
### 5
### 6
### 7
### 8
### 9
### 10
### 11
### 12
## Tizenkettedik teszt 
### 1
### 2
### 3
### 4
### 5
### 6
### 7
### 8
### 9
### 10
### 11
### 12